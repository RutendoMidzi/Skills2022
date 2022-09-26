#Task 3 -- Docker

>Task name:

Manage Docker microservices

>Task description:

Create a docker microservice

● Create a docker “ntp service” (based on the information in the following urls)

● Adapt configuration elements according to your network context. 
● Only a basic ntp server is required. Detailed ntp configuration elements are out of scope.

● Take screenshots indicating the success of your actions and save script files and related docs.

>Task source files:

Here is a selection of the many docker or GitHub webpages. 

URL:

https://hub.docker.com/r/ntpd/ntpd 
https://github.com/linuxkit/linuxkit/blob/master/pkg/openntpd/Dockerfile 
https://hub.docker.com/r/cturra/ntp 
https://github.com/cturra/docker-ntp 
https://chrony.tuxfamily.org/faq.html 


>Task preparation

Docker - In our system, docker is already installed. We just have to confirm by checking the version.


>Task implementation 

The ntp server is a Network Time Protocol that can synchronise the system clock with NTP servers,and manual input using  keyboard and wristwatch.

We can get it by pulling this container from Docker Hub. 

Then we run it


By default, this container uses CloudFlare's time server (time.cloudflare.com). 

To see details on the ntp status of your container


To test the service:






