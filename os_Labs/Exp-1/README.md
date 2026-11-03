# Experiment 2: Install Ubuntu Linux Using Oracle VirtualBox

## Aim

To install Oracle VirtualBox, create a virtual machine, and install Ubuntu Linux on it.

## Requirements

* Windows PC or laptop
* Internet connection
* At least 25 GB of free storage
* Ubuntu ISO file
* Oracle VirtualBox software

## Introduction

Oracle VirtualBox is software that allows us to run another operating system inside our existing operating system. In this experiment, we use VirtualBox to install and run Ubuntu Linux without removing Windows.

## Step 1: Download Oracle VirtualBox

1. Open the official VirtualBox website.
2. Download VirtualBox for your operating system.
3. Open the downloaded installer.
4. Follow the installation instructions.
5. Open VirtualBox after installation.

**Download:** [Oracle VirtualBox](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html)

## Step 2: Download Ubuntu Linux

1. Open the official Ubuntu website.
2. Download the Ubuntu Desktop ISO file.
3. Save the file in a location that is easy to find.

**Download:** [Ubuntu Desktop](https://ubuntu.com/download/desktop)

## Step 3: Create a Virtual Machine

1. Open Oracle VirtualBox.
2. Click **New**.
3. Enter the name `Ubuntu Linux`.
4. Select the downloaded Ubuntu ISO file.
5. Choose the Linux operating system type and Ubuntu (64-bit), if available.
6. Allocate memory (RAM). **4 GB is a reasonable starting point** if your computer has enough memory.
7. Create a virtual hard disk of around **25–30 GB or more**.
8. Review the settings and finish creating the virtual machine.

*Note: The available options may look slightly different depending on your VirtualBox version.*

## Step 4: Install Ubuntu

1. Select the Ubuntu virtual machine.
2. Click **Start**.
3. Follow the Ubuntu installation instructions displayed on the screen.
4. Select your language and keyboard layout.
5. Choose the installation option.
6. Create your username and password.
7. Complete the installation and restart the virtual machine when prompted.

## Step 5: Start Using Ubuntu

After installation:

1. Log in using your username and password.
2. Open the Ubuntu desktop.
3. Open the Terminal using `Ctrl + Alt + T`.
4. Run the following commands to update the package information and installed software.

```bash
sudo apt update
sudo apt upgrade -y
```

Enter your password when prompted.

## Step 6: Test Ubuntu

Run these commands in the Ubuntu terminal to check that the system is working.

```bash
pwd
ls
whoami
uname -a
```

* `pwd` shows the current directory.
* `ls` lists files and folders.
* `whoami` displays the current username.
* `uname -a` displays system information.

## Result

Oracle VirtualBox was installed successfully, a virtual machine was created, and Ubuntu Linux was installed and started.

## Conclusion

In this experiment, I learned how to install VirtualBox, create a virtual machine, install Ubuntu Linux, and run basic commands in the Ubuntu terminal.

## References

* [Oracle VirtualBox Downloads](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html)
* [Ubuntu Desktop Download](https://ubuntu.com/download/desktop)
* [Official Ubuntu VirtualBox Guide](https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox)
