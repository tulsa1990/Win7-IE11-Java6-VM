# Windows 7 Internet Explorer 11 Java 6 Virtual Machine

Instructions for setting up a Virtual Machine (VM) to access an old Java 6 webapp. I developed these instructions using macOS Sierra 10.12.5.

## Step 1: Install VirtualBox

Download and install the latest version of VirtualBox from [here](https://www.virtualbox.org/wiki/Downloads). I download VirtualBox 5.2.26 using the "OS X hosts" link.


## Step 2: Download Virtual Machine

Download the VM with Windows 7 with IE 11 from [here](https://developer.microsoft.com/en-us/microsoft-edge/tools/vms/).

Match these download options:

![Download options](https://d.pr/RE2nUA+)

Download the zip file. This might take a while depending on your internet bandwidth.

## Step 3: Import the Virtual Machine
Uncompress the "IE11.Win7.For.Windows.VirtualBox.zip" file. You should end up with a folder containing a vmdk file and an ovf file. Launch the "IE11 - Win7.ovf" file in Finder. Keep the defaults and click Import.

![Virtual machine import](https://d.pr/zqjV6z+)

Once the import has completed your VirtualBox Manager window should look like this.

![VirtualBox Manager import](https://d.pr/i/Wk4K7A+)




## Step 4: Start the Virtual Machine
Start the virtual machine. When asked to Select a location for you network click cancel.
![Select Network Location](https://d.pr/lsRIUZ+)


## Step 5: Install Java 6 Update 45
From inside the VM, download Java 6 from [here](http://www.oracle.com/technetwork/java/javase/downloads/java-archive-downloads-javase6-419409.html). I choose "Windows x86 Offline" from the "Java SE Runtime Environment 6u45" section. You will need to need to accept the license agreement and sign in to your Oracle account. Save the "jre-6u45-windows-i586.exe" file to your Download folder and run the installer.

## Step 6: Run Java Webapp
Using Internet Explorer navigate to the webapp URL. Enable the plugin when prompted. When warned that Java was blocked because it is out of date, choose "Run this time".

![Java Blocked](https://d.pr/B3wf6m+)






