
# Basic Idea

This project is to buildup a **android login/register on remote server**. We use wampserver as server, couple of `.php` files
has been created to connect the android and server, here are some main technology I've used in this project:

* wampserver mysql
* PHP
* android: volley
* android: string request, requestqueue


# Important notes  

You need to change `C:\wamp64\bin\apache\apache2.4.37\conf\extra\httpd-vhosts.conf` as:  

* change `Require local` to `Require all granted`



# demo  

## Local Client demo

![](https://www.cnblogs.com/images/cnblogs_com/haochen273/1456081/o_ezgif-2-814340ba6a01.gif)

## Remote Server demo

![](https://www.cnblogs.com/images/cnblogs_com/haochen273/1456081/o_123.PNG)

# Reference

<https://www.javatpoint.com/android-volley-library-registration-login-logout>