Create vm on your laptop using Virtual box
Note:
This gist is made for the UIM team. This is series#1 of many on-coming tutorials.

Assumptions:
Your host machine is your windows laptop

Steps:
Get required softwares
Install VBox and Vagrant
Get code from gitHub
Create vm and access it
1. Get required softwares
On your windows explorer, go to '\\kucsa02-i8607\C$\Users\Administrator\Downloads`
When prompted for user name and password, enter administrator/interOP@8607
Copy the following files on to your laptop
 VirtualBox-5.2.4-119785-Win.exe
 vagrant_2.0.1_x86_64
 Git-2.15.1.2-64-bit (in case you do not already have this)
2. Install VBox and Vagrant
Double click and install both softwares leaving default choices. After you installation, it will ask you to restart the box, restart it.
3. Get code from gitHub
Create any folder of your choice on your laptop. Lets call it "uimbox" inside c:. Hence you have c:\uimbox
Go to git bash, run
  cd c:\
  mkdir data
  cd uimbox
In gitbast, from inside uimbox folder, git clone https://github-isl-01.ca.com/kucsa02/uim.git
  git clone https://github-isl-01.ca.com/kucsa02/uim.git
  cd uim
4. Create vm and access it
  ````
   vagrant up //Please note: This step will take about 1 hour first time, next time onwards, it will take about 3-5 min. 
   vagrant ssh
