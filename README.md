# docker-lemp-stack
Docker lemp stack for multiple php projects

#How to use it
All you need to do is : 
  - Create the nginx config file in nginx/conf.d/ and map it to your PHP project located on apps/
  - Add the folder containing your PHP project
  - Add the virtual host on /etc/hosts : sudo nano /etc/hosts
  - Run docker-compose up -d
  - You rock now ;)
