# Project-1

##### This is first excerise of the darey.io project base learning, which is directed towards impacting the skills of LAMP (Linux, Apache, MySQL, PHP or Python, or Perl and get student familiar with the aws EC2 instance at the end.

  
    • WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS 
    • Step 1 — Installing Apache and Updating the Firewall 
    • Step 2 — Installing MySQL 
    • Step 3 — Installing PHP 
    • Step 4 — Creating a Virtual Host for your Website using Apache 
    • Step 5 — Enable PHP on the website

    
##WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS

##### cd ~/Downloads
      sudo chmod 0400 <private-key-name>.pem
      ssh -i <private-key-name>.pem ubuntu@<Public-IP-address>

![My AWS Console](https://user-images.githubusercontent.com/107949309/193410895-d517346d-53de-4d6a-919e-a1f6192049e9.png)

![creating  EC2 ](https://user-images.githubusercontent.com/107949309/193410902-8d5ad778-da6e-4075-ba65-7c3fc0b0826e.png)

![My AWS EC2  server running ](https://user-images.githubusercontent.com/107949309/193410904-d9b29df9-0853-4a23-9fd9-93d83e3969e5.png)

![Connecting to my server](https://user-images.githubusercontent.com/107949309/193411107-057638e6-4eaa-49d0-9701-39ca1c57b8b4.png)

##Step1—installing Apache and Updating the Firewall

    #update a list of packages in package manager
    sudo apt update

    #run apache2 package installation
    sudo apt install apache2
    sudo systemctl status apache2
     curl http://localhost:80
     http://<Public-IP-Address>:80
![starting-installation-apache2](https://user-images.githubusercontent.com/1079493

![after-apache2-installed ](https://user-images.githubusercontent.com/107949309/193411321-6c5b63c4-ccbf-46ae-a1dd-187b6db1c530.png)
09/193411230-55b62e83-9827-4f30-b785-ecd79165d8eb.png)

![switching ports 22 to 80 ](https://user-images.githubusercontent.com/107949309/193415564-b66a3abf-746b-4049-9308-8604649e07e8.png)

![Apache2  page ](https://user-images.githubusercontent.com/107949309/193411346-45ee6e1a-a6cb-4810-86ad-296a6793681b.png)

##Step2—Installing MySQL

![mysql ](https://user-images.githubusercontent.com/107949309/193411902-cbcb5e60-7460-4590-b171-91ecf8ccd632.png)

![mysql access privilege](https://user-images.githubusercontent.com/107949309/193411921-58c1d50f-d41b-4119-beb0-36b3abd1b236.png)

![my sql  finished config ](https://user-images.githubusercontent.com/107949309/193411923-dbfd8f8a-ae0c-40d1-a961-2cfb35038a2d.png)



##Step3—Installing PHP
![Php team install processing ](https://user-images.githubusercontent.com/107949309/193414225-24ccfd23-699c-42b8-b9a8-65ee6ffa716f.png)

  

##Step4—Creating a Virtual Host for your Website using Apache

![Reloading Apache final stage 1 Pj1](https://user-images.githubusercontent.com/107949309/193414813-ddb65409-88c6-4b19-ad94-3ce8a2bb1bbb.png)

![Hello Lamp aws server ](https://user-images.githubusercontent.com/107949309/193414626-fbf35cb5-b5ab-46c3-8816-d2b36fad6a61.png)


##Step5—Enable PHP on the website

![Final Php page ](https://user-images.githubusercontent.com/107949309/193414594-fc0e1eef-5d8e-4090-8539-fc5225416680.png)


![PHP 2  pj1](https://user-images.githubusercontent.com/107949309/193414548-53cb7589-7eab-4fba-81e2-577e99d1d80a.png)


![PHP 3  pj1](https://user-images.githubusercontent.com/107949309/193414530-ef554bcf-7375-4d77-8e5c-61d6843f9c38.png)




