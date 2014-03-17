#What is Chocolatey?

Choclatey is a **package installer** that allows a windows system to install packages 
much like linux does. This is very helpful because as a programmer or any user for that matter goes about the task of installing different programs on their system.

Some more intricate programs require that dependencies be installed on your system before the required program is installed. This is package isntallers really shine. *All* dependencies of the required prgoram are found and installed by the package isntaller without the need for input from the user. This will save you *alot* of time.


Installing Chocolatey
=====================

Now that we know what a package manager is we shall install chocolatey for windows.

1. Open a command prompt window as an administrator
2. Copy the following text as is into the window:
	@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%systemdrive%\chocolatey\bin
3. Enjoy the Chocolatey goodness!!

Using Chocolatey
==================

The script that was run also puts chocoaltey in the PATH variables so now you can use it anywhere you want.

2 Basic commands you will need to know:
+cinst - This will install whatever package you specified
+cuninst - This will uninstall a specified package

Example
--------
>Let's say you've all of a sudden gotten a interest in big data and you want to go ahead and start using a noSQL database. The one that you've heard is very good is called MongoDB but you have no idea how to install the correct verison even after goign onto the website. Incoming Chocolatey goodness to the rescue.
