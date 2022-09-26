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

![unnamed](https://user-images.githubusercontent.com/58246129/192383815-ab8c0d68-9e63-4f7f-b1ed-af9cceb450d0.png)

Then we run it

![unnamed (1)](https://user-images.githubusercontent.com/58246129/192383851-2a40b252-7b27-4407-bf93-8d1a2388d684.png)

By default, this container uses CloudFlare's time server (time.cloudflare.com). 

To see details on the ntp status of your container

![unnamed (2)](https://user-images.githubusercontent.com/58246129/192383875-117512c0-6e39-4f1d-8dc6-af59d84d5431.png)

To test the service:

![unnamed (3)](https://user-images.githubusercontent.com/58246129/192383887-203b82eb-8ba3-4996-8044-2d68ef403012.png)





