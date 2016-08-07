Default CentOS (7.2) server setup:

* Does a YUM update and installs:

    - curl
    - htop
    - nano
    - nmap
    - mosh
    - firewalld
    - mosh

* Opens firewall ports for:

    - ssh
    - mosh

* Create user:

   - jerome
   - sets up ssh keys for connectivity

* SSH:

   - disables Root login
   - disables password logins
   - enables key logins only
