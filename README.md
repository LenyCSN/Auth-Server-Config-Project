# CSN150 Auth-Server-Config-Project
### Objective: Using an Ubuntu 22.04 (LTS) server without ssh keys (for simplicity) through Digital Ocean, as well as another basic server to test out security policies, a server with several security policies will be configured to enable 2FA through Google Authenticator and configure Jail2ban to set up timed banning policing. As well as using Postfix to forward email traffic through Gmail for the purpose of sending automated emails alerts for attempted login failures.
### Equipment:
1. Ubuntu 22.04 (LTS) Server
2. Another server/computer to test ssh banning policies (you don't want to fail the ssh from the computer you're going ssh for configurations because your ip will be banned for the configured amount of time. Another device should be used for testing purposes)

---

### Documentation Links:
1. [Deploying initial Ubuntu 22.04 LTS Server](https://www.digitalocean.com/community/tutorials/initial-server-setup-with-ubuntu-22-04)

2. [Google Authentication deployment](https://www.linuxbabe.com/ubuntu/two-factor-authentication-ssh-key-ubuntu)

3. [Postfix deployment with Gmail forwarding SMTP traffic](https://tonyteaches.tech/postfix-gmail-smtp-on-ubuntu/)

4. [Fail2ban](https://www.digitalocean.com/community/tutorials/how-to-protect-ssh-with-fail2ban-on-ubuntu-22-04)

5. [ip address ban log tutorial](https://www.the-art-of-web.com/system/fail2ban-log/#google_vignette)

---

### Steps Followed:
1. Deployed initial Ubuntu 22.04 LTS Server.
2. Google Authentication deployment.
3. Postfix deployment with Gmail.
4. Fail2ban config
5. Reset and bring up all systems
6. Test banning policies with another computer/server and ssh.

---

### Problems Encoutered:
1. SMTP traffic functions normally, but automated sending functionality isn't functioning properly.
