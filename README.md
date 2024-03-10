## <ins>msgM8</ins>
### An SMS/MMS to email communication pipeline 

**msgM8** routes SMS/MMS messages received by an Australian mobile phone number to an email inbox.  The msgM8 phone number is provisioned by Twilio and the emails are sent using the SendGrid API.

The application is hosted on Twilio Functions and its execution is triggered by an incoming TXT or MMS message. 

The body of an email sent by **msgM8** contains the text content of the triggering TXT/MMS message, while multimedia files are included as attachments.

