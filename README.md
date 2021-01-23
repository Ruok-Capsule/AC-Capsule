# AC-Capsule

# DONT USE THIS TUTORIAL NOW , I'M NOT DONE WITH THIS . I WILL INFORM YOU  (20.01.21) GREETZ RUOK


# AzerothCore-Linuxrepack
Ubuntu 20.04 repack WoW 3.3.5

Visit my compiled core www.capsule-corp.de
but i will give you a lite version

Based on AzerothCore spezial thanks to https://www.azerothcore.org/
is not mine work , i only compile this files with mods and eluna 
and also i will update this pack and build

My english is not good im a german guy so sorry for this  ;)

# Capsule tutorial
# Installation

***Step 1*** you will need Ubuntu 20.04
         <placeholder>

***Step 2*** install these packets 
         sudo apt-get update && sudo apt-get install git cmake make gcc g++ clang libmysqlclient-dev libssl-dev libbz2-dev libreadline-dev              
         libncurses-dev mysql-server libace-6.* libace-dev libace-6.4.5 libmariadb-dev  
         
        
         <you dont need all these packets 
         but maybe u will compile core later by yourself then you need all>

****Step 3*** Create Ubuntu user name it capsule < sudo adduser capsule > type and retype youre password 
         
         <It is important that the user is called capsule 
         because of the paths that are defined in the repack>
         <files have to be placed in /home/capsule/>
        
         Or if you use git clone then go in directory /home/capsule 
         and git clone https://github.com/Ruok-Capsule/AzerothCore-Linuxrepack.git
         
         make sure if your directory path is /root/capsule/ in directory capsule should be the folders bin end etc 
         

***Step 4*** Setup MySQL 
         
         <MySQL server is needed for World of Warcraft databases (char account world)>
         
         Run commands
         
         sudo mysql_secure_installation   <follow instructions>
         sudo mysql
         ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'password';    <edit 'password' to 'YOURPASSWORD'>
         FLUSH PRIVILEGES;
         exit

***Step 5*** *Optional* Install and setup webserver 
        
         <Webserver is needed for account creation for ingame accounts>
        
        
**Start  **       

