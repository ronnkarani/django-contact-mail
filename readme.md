Using Django's built-in [Forms API](https://docs.djangoproject.com/en/3.0/ref/forms/api/)

Simple contact form that sends email for a Django website.

Also uses Django's built-in [email support](https://docs.djangoproject.com/en/3.0/topics/email/) to make this relatively painless and then send the emails for real using  an email service of your choice.


EMAIL SETTINGS in the settings.py file (for gmail)

* #### **EMAIL_BACKEND**

This setting specifies the backend that we are going to use for
sending an email in Django. There are multiple backends that Django
provides.

* #### **EMAIL_HOST**

This setting is to specify your email service provider. We are using the setting for Gmail.

* #### **EMAIL_HOST_USER**

It is the account name from which we will send an email.

* #### **EMAIL_HOST_PASSWORD**

The password of the email account that we are using.

* #### **EMAIL_PORT**

This is the setting for Gmail, you can get yours on the web. It is the port used by the SMTP server.

* **EMAIL_USE_TLS**

This setting specifies whether the Email uses a TLS connection or not. It is **True** for Gmail.

* #### **EMAIL_USE_SSL**

False for Gmail.

There are some more settings for email but for sending an email with Gmail, this much setup is enough.
