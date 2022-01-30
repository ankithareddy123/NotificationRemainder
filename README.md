# NotificationRemainder
import time
from plyer import notification
if __name__=='__main()__':
	while True:
		notification.notify(
 			title="All Day Remainder",
                        message="Drink Water",
			timeout=10
                )
                time.sleep(60*60)
