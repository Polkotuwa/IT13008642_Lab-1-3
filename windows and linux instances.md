#LAB 1 - ESBII  #
#### IT13008642 ####
#### P.W.J.B Polkotuwa ####
#### Weekday ####
# 1) Create an amazon windows instance in amazon cloud #

### step1 ### -*Accesing amazon EC2*
  
       

>After we signing into  the 
>AWS Managment console we can acccess amazon EC2 by clicking EC2 from the console home page.
                       

![step1](http://i.imgur.com/GmAQqzx.jpg)


### step2 ###-Select launch instance button.
> From the Amazon EC2 Console dashboard, click launch instance.

![step2](http://i.imgur.com/zERfQdg.jpg)

### step3 ### - Choose an Amazon machine image.
> we have to select AMI from Amazon AMI page.for creating windows instances we have to select one of Microsoft windows server AMI's.

![step3](http://i.imgur.com/WOP0vhx.jpg)

### step4 ### - Choose instance type

> After choosed AMI we have to select instance type and click configure instance details button.

![step4](http://i.imgur.com/cgVHLl8.jpg)

### step5 ### - Click Add Storage button

> In Configure instance page click add storage button.but dont change any details there.

![step5](http://i.imgur.com/so6eRmL.jpg)
### step6 ### - Click tag instance.
> In add storage page click tag instance.
![step6](http://i.imgur.com/PeKDhH8.jpg)


### step7 ### - Click review and launch.
> click review and launch in configure security group page.

![step7](http://i.imgur.com/POi4iga.jpg)

### step8 ### - click launch button.
> Click launch button in review page.

![step8](http://i.imgur.com/WePVunX.jpg)
### step9 ### - Create a key pair

> To secure login information for instances AWS use public-key cryptography.so we have to create private key when we launch our instances.

![step9](http://i.imgur.com/d1OPzF0.jpg)

### step10 ### - Download keypair

> when we login to windows instance using RDP we have to provide the administrator password for the windows instance.to obtain that administrator password we have to give private key.so we have to download it.


![step10](http://i.imgur.com/b5zvYNr.jpg)

### step11 ### - Launch instances

> By clicking launch button we can launch the instances.

![step11](http://i.imgur.com/O3bWHYY.jpg)


### step12 ### - view instances.

> To connect the instances we want ip address.we can get those details in view instance page.

![](http://i.imgur.com/62KG1y3.jpg)


### step13 ### - connect to instance

> To connect we have to click connect button and also we need administrator password.

![](http://i.imgur.com/QZkDWRI.jpg)


### step14/15 ### - Decrypting the password

> To decrypt the password we have to give private key pair which consists the Administrator password.

![](http://i.imgur.com/rMqfBTM.jpg)

### step16 ###  - After decrypting the password

> After decryption we can get the user-name and password for our instance.

![](http://i.imgur.com/iZm1fU8.jpg)
### step17 ### - Run windows instance using remote desktop connection.

> We can  instance using remote desktop connection for that we have to provide ip address of the instance.



![](http://i.imgur.com/q42HjOg.jpg)

### step 18 ### - Provide username and password for remote desktop connection.

    
> We have to provide admintrator username and password to connect  with instance using remote desktop connection.

![](http://i.imgur.com/pikPAMo.jpg)



### final step ### - Windows instance.

> Finally we can view the windows instance.

![](http://i.imgur.com/OGXRJDr.jpg)


**1.1 install software to Amazon EC2 windows instance**

> I installed IIS server in EC2 windows instance

### step1 ### - open server manager

> First we have to open server manager in ec2 instance.

![](http://i.imgur.com/Dq0s1sa.jpg)

### step2 ### - turn off iesc

> we have to turn off  Internet explorer enhanced security configuration.

![](http://i.imgur.com/EAryDlu.jpg)

### step3 ### - go to add roles and manage wizard

![](http://i.imgur.com/LlW1X5m.jpg)

### step4 ### - select web server IIS on web server roles.

![](http://i.imgur.com/IRJAGpR.jpg)

### step5 ### - installing

![](http://i.imgur.com/EUwAn4K.jpg)

### step6 ### - open IIS manager

> Then we have to open IIS Manager.

![](http://i.imgur.com/Q60j79P.jpg)

### step7 ### - start the IIS Server.

![](http://i.imgur.com/YIK36VU.jpg)

### step8 ### - Run IIS server.

![](http://i.imgur.com/9ippDLX.jpg)



# 2)Create an amazon linux instance in amazon cloud #

### step1 ### - Accessing amazon EC2

>After we login in to the amazon aws console we have to select amazon ec2 by clicking EC2 from the home page.

![](http://i.imgur.com/S82uhcM.jpg)


### step2 ### - select launch instance

> We have to click launch instance button in the page.

![](http://i.imgur.com/OePPRES.jpg)

### step3 ### - Choose amazon linux ami.

> From Amazon machine images(AMI) we have to select linux support AMI's like Amazon Linux and Red hat.

![](http://i.imgur.com/Jyy7oea.jpg)
### step4 ### - choose instance type.

> Select free tier eligable instance type and click configure instance details button.

![](http://i.imgur.com/6wyEh6r.jpg)

### step5 ### - Add storage

> click add storage button without changing details in the add storage page.

![](http://i.imgur.com/hHo5dss.jpg)

### step6 ### - Click review and launch.

> click review and launch in configure security group page.

![](http://i.imgur.com/xtAsC1C.jpg)

### step7 ### - Launch the instance

> click the launch button to  launch the instance we created.

![](http://i.imgur.com/RXAhk2K.jpg)

### step8 ### - Create new key pair and download

> AWS public key cryptography to secure login information for our instance.A linux instance has no password.we can use just key pair to login instance securely.
![](http://i.imgur.com/leHlezG.jpg)

### step9 ### - view instance details.

> We can view running instances in instance page.

![](http://i.imgur.com/HHzkmSK.jpg)

### step10 ### - Downlaod puttygen key generator and run it.

> We need this software to save private key.

![](http://i.imgur.com/cuV1Vih.jpg)

### step11/12 ### - Load .pem file 

> click load and locate it.then load it.

![](http://i.imgur.com/XV28aMO.jpg)

![](http://i.imgur.com/x3mvtV3.jpg)
### step13/14 ### - Save private key for the linux instance.

> Click save Private key.It displays a warning click yes for it.

![](http://i.imgur.com/NH7PPUA.jpg)

> Then save private key file in .ppk file extension.

![](http://i.imgur.com/ef07dW7.jpg)

### step15 ### - Run putty configuration to connect instance.

> We can also connect instance using browser.but alternatively we can connect using putty.

![](http://i.imgur.com/iYQOw7B.jpg)
### step16 ### - copy public DNS from the linux instance.

> we can get Public DNS from the amazon instance page.we have to copy it.

![](http://i.imgur.com/MPSSjMV.jpg)

### step17 ### - Create a seesion.

> copy Public DNS as a hostname and create a new session and save it.

![](http://i.imgur.com/gazcGUP.jpg)

### step18 ### - Give a login user-name.

> In data give login username as ec2-user.

![](http://i.imgur.com/h6Vsg1z.jpg)

### step19 ### - Browse for private key file.

> In SSH Auth browse private key file which created by using puttygen key generator and give it.

![](http://i.imgur.com/X7aMgsX.jpg)


### step20/21 ### - linux instance.

> Then we can work with linux instance.

![](http://i.imgur.com/dt7TWO5.jpg)

![](http://i.imgur.com/zH0L9ND.jpg)

**2.1 Run a c++ program inside Amazon EC2 linux instance**

### step1 ### - Create C++ file

> First we have to create c++ file in amazon ec2  linux instance.

![](http://i.imgur.com/BmxkIMi.jpg)


### step2 ### - install source packages.

> install sourse packages by giving *sudo yum groupinstall "Development Tools"* command

![](http://i.imgur.com/vzeaE9I.jpg)

#### step3 #### - c++ code

![](http://i.imgur.com/9EqALdY.jpg)


### step4 ### - run the C++ file

![](http://i.imgur.com/u5hfkS5.jpg)



