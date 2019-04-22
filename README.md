# setting-the-project

1)The following are the links to the docker image files

https://cloud.docker.com/repository/docker/jnanesh10/api-access


https://cloud.docker.com/repository/docker/jnanesh10/order_vendor


2)The following are the links to the project code
https://github.com/supply-chain-using-dockers/vendor-ui

https://github.com/supply-chain-using-dockers/vendor-api

3)get the images from docker hub 

4)check if the api code works

**********IMPORTANT**************
please use the Mozzila Firefox browser to run this project . Chrome causes security issues which does not run the project as expected

5)run the api image

sudo docker run -d -p 3000:3000 jnanesh10/api-access
![mongo](https://user-images.githubusercontent.com/41481315/56488028-c6b71680-64fa-11e9-88a0-fe2a4eeebab3.png)


http://localhost:3000/place-order

in browser.You will get the following JSON object

6)if the api is working you are good to go for next part
  CHECK FOR NETWORK ISSUES IF THERE ARE ERRORS. PLEASE RESTART YOUR CONNECTIONS
  One of the common errors is MONGO ERROR. It has some issues connecting to database
   
7)run the front-end container docker
sudo docker run -d -p 4200:80 jnanesh10/api-access

8)go to localhost:4200

9)add the following extension for firefox

  https://addons.mozilla.org/en-US/firefox/addon/cors-everywhere/

10)There are 2 logins:
  
  username : pranav@skf.com
  password : skf@123
  
  username : pramod@componentsupplier.com
  password : componentsupplier
  
 11)Please wait for some time if content does not load 

  

