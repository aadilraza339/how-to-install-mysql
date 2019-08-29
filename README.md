# how to install mysql

=> 1 Update the apt package manager index by typing following command: <br>
`sudo apt update` <br>
=> 2
Now to install mysql-server package run below command <br>
`sudo apt install mysql-server`<br>
=> 3
THEN use mysql <br>
=>4
update user set authentication_string=PASSWORD("enter_your_password") where user = 'root'; <br>
=>5
update user set plugin="mysql_native_password" where user="root"; <br>
=>6
flush privileges; <br>
=>7
/etc/inot.d/mysql stop <br>
=>8
/etc/inot.d/mysql start <br>
============================
*now you can user your mysql* <br>
=/////////
this is commend for open your mysql <br>
sudo mysql -u root -p
====================
For nodemon <br>
`npm install -g nodemon`
<br>
some time this command is working but if this will not woking so use this command <br>
`sudo npm - g nodemon --save`<br>

[this video also helpfull to set password ]("https://www.youtube.com/watch?v=sG5Z4JqhRx8")
