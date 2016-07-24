## LAB2   - Creating a RDS Database in amazon cloud

### IT13008642 ###
### P.W.J.B Polkotuwa ###
### weekday ###

#### step1 #### - Create a DB subnet group

> First we have to create DB Subnet group to that we have to click Create DB subnet group button. 

![](http://i.imgur.com/ym63Y8u.jpg)


#### step2 #### - Give details of the subnet.

> Here we have to fill details like name description and availability zones.We can have only 2 subnets related to one VPC.

![](http://i.imgur.com/XqLlhWv.jpg)

#### step3 #### - create  subnet

> We have to click create button.

![](http://i.imgur.com/bpZL5Oe.jpg)

#### step4 #### - After creating subnet


![](http://i.imgur.com/4jo6HdO.jpg)

#### step5 #### - select DB engine

> In the navigation page click instances.then click launch instance button to start the Launch DB Instance Wizard.


> Then wizard opens on the Select Engine page.

![](http://i.imgur.com/HPwrkSX.jpg)

#### step6 #### - Selct MYSQL DB engine.

> In the Launch DB Instance Wizard window, click the Select button for the MySQL DB engine.

![](http://i.imgur.com/xsJzOju.jpg)

#### step7 #### - select production plan.

> Then select MYSQL RDS Free Usage Tier.

![](http://i.imgur.com/cLrMyXY.jpg)

#### step8 #### - Fill instance specifications.

> On the Specify DB Details page,we have to specify our DB instance information.

![](http://i.imgur.com/enr3F70.jpg)

#### step9 #### - provide master username and password.

> Then we have to give master username and master password.

![](http://i.imgur.com/rQFlLZS.jpg)

#### step10 #### -Configure Advanced settings.

> On the Configure Advanced Settings page,we have to provide additional information that RDS needs to launch the MySQL DB instance like VPC,VPC Security group.

![](http://i.imgur.com/lb91WFC.jpg)


#### step11  ####-View DB instance details.

> We can view our DB instance by clicking view DB instance button.

![](http://i.imgur.com/nr4UQ8q.jpg)


#### step12 #### - Creating DB instance.

> It will take few minutes to create the DB instance.

![](http://i.imgur.com/dWX11Vt.jpg)

#### step13 #### - Available DB.

> After creating the DB instance we can see status as available and we also can see the end point.


#### step14 #### - Create security group.

> Then we have to create security group by going to ec2 console.
![](http://i.imgur.com/HwoT49t.jpg)

![](http://i.imgur.com/rIhLduJ.jpg)

#### step15 #### - Add inbound rule for security group.

> Then provide details for security group and add inbound rule.

![](http://i.imgur.com/HFDcmJ3.jpg)

#### step16 ####  - Available DB instance.

> Then we can see our DB instance as available.

![](http://i.imgur.com/21yQcGP.jpg)

#### step17 #### - Connect DB instance using Xampp

> To connect DB instance using Xampp we have to give above command:


     mysql -h <endpoint> -P 3306 -u <mymasteruser> -p

![](http://i.imgur.com/gu0yWR5.jpg)

![](http://i.imgur.com/qLnUxRC.jpg)

#### step18 #### - Provide master password for DB instance.

> Then we have to give password.

![](http://i.imgur.com/mpabCdV.jpg)

### 2.1 - connect with MySQL workbench ###

####step1 - First we have to open MySQL Workbench and Crete a new database connection.

> There we have to provide below details.

Connection Name: Any name

Host name : enter endpoint  (remove “:3306” at end)

Enter User name and Password which are given for rds database instance.

Test connection and click on OK.

Now successfully we have connected the cloud database and below are screens for the same.

![](http://i.imgur.com/ZzpojCd.png)

![](http://i.imgur.com/inZHeVU.jpg)



#### step2 - create the database and related tables in cloud main database.


![](http://i.imgur.com/C7zaRb0.png)


#### step3  -  query data from rds database tables.

![](http://i.imgur.com/6aPnH5J.png)

#### step4  - update tables and insert values to tables.


![](http://i.imgur.com/oFdTzGz.png)










