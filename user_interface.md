# User interface

The user interface is a portal that allows a logged-in user to see all the applications they are allowed to use, and to access them. This interface is also where the user can set their parameters (eg. change the password, define email alias' and 
redirections).

<img src="/images/home_panel.jpg" width=800>

### Access problems

Access to the user interface can only be done by using a domain name. You can’t access it by using the local IP address of your server with your servers local IP address like this: https://your.server.ip.address/yunohost/sso/

You can create a redirection of a domain name to the IP address of your server by modifying `/etc/hosts` and by adding the following line:

```bash
your.server.ip.address domain.tld
```

By replacing `your.server.ip.address` for instance with `192.168.1.05` and `domain.tld` with your domain name or registering a domain name if you don’t already own one.

### Software

The user interface is based on this software: https://github.com/Kloadut/ssowat
