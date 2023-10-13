# Tool to spoof any Email address 
The above script creates a multipart MIMEM message with From, To and Subject headers and adds a MIMET body. Next, connect to the SMTP server specified in the configuration file, enable TLS encryption, and log in with the specified username and password. Finally, it sends the email using the sendmail() method of the SMTP server object. To use this script, Run it from your favorite IDE and Fill the Sender's name and Email then the receiver's too and the message you want to send.
Make sure your device is connected to the internet before doing this.
# Config.ini
Head over to the config.ini file and edit the field to your corresponding SMTP settings.
