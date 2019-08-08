# how to install mysql

=> 1 Update the apt package manager index by typing following command: <br>
`sudo apt update` <br>
=> 2
Now to install mysql-server package run below command <br>
`sudo apt install mysql-server`<br>
=> 3
Now confirm the installation and check MySQL version typing following command: <br>
`mysql -v`<br>
=> 4
After completing installation MySQL will start automatically. Check MySQL version by typing: <br>
`sudo systemctl status mysql`<br>
=> 5
and how to open mysql <br>
`mysql -u root -p`<br>
=> 6
After installation, we have to improve MySQL security by typing the following: <br>
`sudo mysql_secure_installation` <br>

<br>

For nodemon <br>
`npm install -g nodemon`
<br>
some time this command is working but if this will not woking so use this command <br>
`sudo npm - g nodemon --save`<br>
or <br> 
`sudo npm - g nodemon`
