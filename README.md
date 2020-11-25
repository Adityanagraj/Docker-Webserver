# Docker-Webserver-Configuration
In this repository we will see how to configure apache webserver inside Docker
Step 1 : Laucnching the **centos container** using Docker with the name of  webserverconfig
![](https://i.postimg.cc/L8pDccsT/1.jpg)
Step 2  : checking is S/W httpd which provide webserver is present in docker or not using ***httpd***
![](https://i.postimg.cc/QdMLLKCS/2.jpg)
Step 3: if the httpd is not present in the docker lauched centos we can install the Httpd in sentos using **yum** command using ***yum install httpd***
![](https://i.postimg.cc/yYYpW4K8/3.jpg)
Step 4: Now its time to start httpd using **systemctl start httpd** but it fails inside docker 🤔
![](https://i.postimg.cc/MH4BWQxR/4.jpg)
Step 5 : we can see from where we get httpd sowtware using ***which*** command where we get the source from wher we get httpd
![](https://i.postimg.cc/MZcbL6zR/5.jpg)
Step 6: once we execute /usr/sbin/httpd we see our webserver gets kickin!!
![](https://i.postimg.cc/JnsJSxCm/6.jpg)
Step 7 : 🤩 Viola we see our webpage in the local IP 
![](https://i.postimg.cc/Zngw1nMs/7.jpg)
Step 8 : installing python3 inside centos
![](https://i.postimg.cc/tCcgMbC1/8.jpg)
Step 9 : Executing python code inside centos
![](https://i.postimg.cc/T1ZZntfP/9.jpg)

-----------------------------------------------
