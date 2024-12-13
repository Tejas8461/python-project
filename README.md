from plyer import notification
import time
def desktop_notifier(title, message):
   notification.notify(title=title,
       message=message,
       app_name='Your App Name',  
       timeout=10)
if _name_ == "_main_":
   title = "Sample Notification"
   message = "This is a notification from your Python script."
   desktop_notifier(title, message)
   time.sleep(0)
