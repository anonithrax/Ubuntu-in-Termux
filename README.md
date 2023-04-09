# Ubuntu-in-Termux
Ubuntu in Termux: Run Ubuntu Linux on Your Android Device

Ubuntu is a popular Linux distribution that is widely used for development and server purposes. Termux is an Android terminal emulator that allows you to run Linux applications on your Android device. In this tutorial, we will show you how to install Ubuntu on Termux and how to use it to upload a repository to GitHub.

Installing Ubuntu on Termux
Before installing Ubuntu on Termux, make sure you have a stable internet connection and enough storage space on your Android device. Follow the steps below to install Ubuntu on Termux:

1-Install Termux from the Google Play Store :
https://play.google.com/store/apps/details?id=com.termux

2-Open Termux and type the following command to update the package list:
```console
apt update
```

3-Install the required packages by typing the following command:
```console
apt install wget proot -y
```

4-Download the Ubuntu file by typing the following command:
```console
wget https://raw.githubusercontent.com/Neo-Oli/termux-ubuntu/master/ubuntu.sh
```

5-Give execution permission to the Ubuntu file by typing the following command:
```console
chmod +x ubuntu.sh
```

6- Run the Ubuntu installation script by typing the following command:
```console
./ubuntu.sh
```

7- The installation process will start, and it may take several minutes to complete. Once the installation is complete, you will be prompted to set a username and password for your Ubuntu installation.

# For any further queries feel free to join my discord :
https://discord.gg/Dk5vPE4q9E
