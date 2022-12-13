Install any web-server on the VM and access using browser

Steps
    # Have to install the httpd server with help of command "sudo apt-get install"
    # It gives the httpd server package oin that we can select in our choice and install it in same manner as above 
    # We have to writedown the script in vagrant file notepad saveit and reload the vagrant 
    # Then we get the access to the webservice of the installed server

By acessing the webpage or server through httpd with vagrant is easily acessable to the public and its helps the client or coworker to check the looks 
and changes.
It can be assing by public host address and also the private ip address.

<img width="960" alt="2022-12-13 (3)" src="https://user-images.githubusercontent.com/118107382/207326059-fb7bf90f-4a4f-4a91-b5bd-6eb879b21e1a.png">
<img width="960" alt="2022-12-13 (1)" src="https://user-images.githubusercontent.com/118107382/207326091-f5b21934-62fc-469a-af6c-ea907e0951e0.png">
<img width="960" alt="2022-12-13 (2)" src="https://user-images.githubusercontent.com/118107382/207326106-b13d014c-d240-4909-9a08-6eefc337e043.png">


**HTTPD INSTALLATION

vagrant@vagrant-ubuntu-trusty-64:~$ sudo apt-get install httpd
Reading package lists... Done
Building dependency tree
Reading state information... Done
Package httpd is a virtual package provided by:
  nginx-naxsi 1.4.6-1ubuntu3.9
  nginx-light 1.4.6-1ubuntu3.9
  nginx-full 1.4.6-1ubuntu3.9
  nginx-extras 1.4.6-1ubuntu3.9
  lighttpd 1.4.33-1+nmu2ubuntu2.1
  bozohttpd 20111118-1+deb7u1build0.14.04.1
  apache2-mpm-itk 2.4.7-1ubuntu4.22
  nginx-core 1.4.6-1ubuntu3.9
  apache2-mpm-worker 2.4.7-1ubuntu4.22
  apache2-mpm-prefork 2.4.7-1ubuntu4.22
  apache2-mpm-event 2.4.7-1ubuntu4.22
  apache2-bin 2.4.7-1ubuntu4.22
  yaws 1.98-2
  webfs 1.21+ds1-9
  tntnet 2.2.1-1
  ocsigenserver 2.2.0-3
  mini-httpd 1.19-9.3
  micro-httpd 20051212-15
  ebhttpd 1:1.0.dfsg.1-4.3
  boa 0.94.14rc21-5
  aolserver4-daemon 4.5.1-16
  aolserver4-core 4.5.1-16
You should explicitly select one to install.

**WEB SERVER 

vagrant@vagrant-ubuntu-trusty-64:~$ sudo apt-get install -y apache2-bin
Reading package lists... Done
Building dependency tree
Reading state information... Done
apache2-bin is already the newest version.
apache2-bin set to manually installed.
0 upgraded, 0 newly installed, 0 to remove and 1 not upgraded.



