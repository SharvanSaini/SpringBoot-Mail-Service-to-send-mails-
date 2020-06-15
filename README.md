# SpringBoot-Mail-Service-to-send-mails-

Using SMTP Service

To get this service first to on the less secure app access using this url- https://myaccount.google.com/lesssecureapps?pli=1

Now go to application.properties update your mail which you give the access in less secure app

There is a ftl template in resource>template>email-template.ftl, outlook design and content your mail.


Testing will be perform in Postman

Post Method- http://localhost:8902/sendingEmail

{
"to":"svnnsaini1008@gmail.com",          // Reciver mail id
"from": "sharvansaini9819@gmail.com",  // sender mai id which is in application.properties file
"subject":"notification",
"name":"Sharvan Saini"
}
