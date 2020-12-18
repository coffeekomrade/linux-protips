To change welcome message, edit 

/etc/ssh/sshd_config
 
>`sudo nano /etc/ssh/sshd_config`

Uncomment this line and add a banner file name (it will just say banner, remove #)

>Banner /etc/banner

Then edit /etc/banner 

>`sudo nano /etc/banner`

Restart SSH 

>`sudo /etc/init.d/ssh restart`