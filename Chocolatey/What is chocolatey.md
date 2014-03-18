#What is Chocolatey?

Choclatey is a **package installer** that allows a windows system to install packages 
much like linux does. This is very helpful because as a programmer or any user for that matter goes about the task of installing different programs on their system.

Some more intricate programs require that dependencies be installed on your system before the required program is installed. This is package isntallers really shine. *All* dependencies of the required prgoram are found and installed by the package isntaller without the need for input from the user. This will save you *alot* of time.


Installing Chocolatey
=====================

Now that we know what a package manager is we shall install chocolatey for windows.

1. Open a command prompt window as an administrator
2. Copy the following text as is into the window:
	>@powershell -NoProfile -ExecutionPolicy unrestricted -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%systemdrive%\chocolatey\bin
3. Enjoy the Chocolatey goodness!!

Using Chocolatey
==================

The script that was run also puts chocolatey in the PATH variables so now you can use it in any directory from the command line.

2 Basic commands you will need to know:

+cinst - This will install whatever package you specified

+cuninst - This will uninstall a specified package

Example
--------
>Let's say you've all of a sudden gotten a interest in big data and you want to go ahead and start using a noSQL database. The one that you've heard is very good is called MongoDB but you have no idea how to install the correct version even after going onto the website because the isntructions are so convuluted. Incoming Chocolatey goodness to the rescue.

**This is quite a conundrum let's solve it using Chocolatey**
1. Open a command prompt window
2. cinst mongodb
3. now you have mongo 

Notes
--------
There is a full list of all the different packages you can install using Chocolatey. These can be found on the chocolatey website at https://chocolatey.org/packages 

Also a good package for all to install would be the Git package. It will allow for easy integration with windows gui, such as the right click menu. The command as ever is cinst git. Play around with chocolatey and find out what otehr pakcages you can install using it. Things such as VLC media player and Java SDK can all be installed using Chocolatey so please do not hesitate to bathe yourself in the Chocolatey goodness.
