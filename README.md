FeedbackAndroid
===============
Based on this idea http://stackoverflow.com/questions/2020088/sending-email-in-android-using-javamail-api-without-using-the-default-built-in-a I created a small android library that allows the user to send feedback with a form using Javamail instead of the default email client on the phone. You need to configure a gmail account in order to send the emails.


![alt tag](http://i.imgur.com/Nu6zkV0.png)

How to use it
==============

To use it simply:

```
//Create your configuration email properties
//Configuration configuration = new Configuration(
                        "your_gmail_account_to_receive_email@gmail.com", "your_gmail_account_to_send_email@gmail.com",
                        "your_gmail_account_password_to_send_email@gmail.com", "Send feedback");

AlertDialogFeedBack newFragment = AlertDialogFeedBack.newInstance(configuration);
newFragment.show(fm, "tagDialog");
```             
