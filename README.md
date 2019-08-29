# how to install mysql

=> 1 Update the apt package manager index by typing following command: <br>
`sudo apt update` <br>
=> 2
Now to install mysql-server package run below command <br>
`sudo apt install mysql-server`<br>
=> 3
THEN use mysql
=>4
update user set authentication_string=PASSWORD("enter_your_password") where user = 'root';
=>4
update user set plugin="mysql_native_password" where user="root"
=>5
flush privileges;
=>6
/etc/inot.d/mysql stop
=>7
/etc/inot.d/mysql start
============================
*now you can user your mysql*
=/////////
this is commend for open your mysql
sudo mysql -u root -p
====================
For nodemon <br>
`npm install -g nodemon`
<br>
some time this command is working but if this will not woking so use this command <br>
`sudo npm - g nodemon --save`<br>

[this video also helpfull to set password ]("https://www.youtube.com/watch?v=sG5Z4JqhRx8")
