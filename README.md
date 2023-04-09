# Ubuntu-in-Termux
Ubuntu in Termux: Run Ubuntu Linux on Your Android Device

Ubuntu is a popular Linux distribution that is widely used for development and server purposes. Termux is an Android terminal emulator that allows you to run Linux applications on your Android device. In this tutorial, we will show you how to install Ubuntu on Termux and how to use it to upload a repository to GitHub.

Installing Ubuntu on Termux
Before installing Ubuntu on Termux, make sure you have a stable internet connection and enough storage space on your Android device. Follow the steps below to install Ubuntu on Termux:

Install Termux from the Google Play Store.

Open Termux and type the following command to update the package list:

sql
Copy code
apt update
Install the required packages by typing the following command:
Copy code
apt install wget proot -y
Download the Ubuntu file by typing the following command:
bash
Copy code
wget https://raw.githubusercontent.com/Neo-Oli/termux-ubuntu/master/ubuntu.sh
Give execution permission to the Ubuntu file by typing the following command:
bash
Copy code
chmod +x ubuntu.sh
Run the Ubuntu installation script by typing the following command:
bash
Copy code
./ubuntu.sh
The installation process will start, and it may take several minutes to complete. Once the installation is complete, you will be prompted to set a username and password for your Ubuntu installation.
