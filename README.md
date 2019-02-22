# mindevenviro-windows TESTING

* the same scripts like mindevenviro-debian but without X11 - Apps

# M1ND3V3NV1R0 DevOps (testing v0.0.1B)

		  codecounter: code without blank lines and without comments

- Lines =1866

- Words =8411

- Chars =65555

# Install

* Make a shortcut on the desktop, right-click, New, shortcut, write powershell and click Next. 
* A new link is created. Right-click on the Powershell shortcut and run as administrator. 
* Type the following line in the Powershell: 

### "Enable WindowsOptionalFeature Online Feature Name Microsoft Windows Subsystem Linux." 

* You may need to reboot. 

* After this setting, enter, in the Microsoft Store, linux, choose debian and install it.

* Run the Debian app, and type in the command line: "sudo apt-get -y -f --fix-missing install git".

* do: cd /mnt/c/Users/$USER/Documents/ ($USER is your User-Name in Windows and you must run your Windows as administrator.)

* do: "pwd" you should be in "/mnt/c/Users/$USER/Documents/"

* user@host:/mnt/c/Users/$USER/Documents/ "git clone https://github.com/doivglser/mindevenviro-windows.git" 

* The above step should clone mindevenviro-windows, in to your Documents folder in Windows 10.

* do within the Debian App: ln -s /mnt/c/Users/$USER/Documents/mindevenviro-windows /home/$USER/ ($USER in Windows 10 and $USER in the Debian App may differ.)

* In your home/$USER/ folder you should have a Sym-link from Documents to your home/$USER/ folder in the Debian App.

* "cd mindevenviro-windows"

* check the entry in the /etc/sudoers file: "cat /etc/sudoers" if your username ist not listed then edit.

* "user@host:~/mindevenviro-windows/sudo mde-setup"

# USAGE:

* You can edit your Projects with your favorite IDE, I use in Windows 10: "Notepad++", from within Windows Explorer in the Documents folder.

* run: "sudo sCRYPtUPdater -w 30 testpython/" to check syntax with a workflow interval of 30 minutes in to your testpython folder. (you can use an other folder also.)

* run: "ls /usr/local/bin" to see scripts may work

* update your Virus definitions: "sudo freshclam"

* start your Antivirus protection for all Users on your Windows machine: "sudo /etc/init.d/clamav-daemon start"

* check if Antivirus is running: "sudo /etc/init.d/clamav-daemon status"

* check if apache2 is running: "sudo /etc/init.d/apache2 status"

* check if mysql is running: "sudo /etc/init.d/mysql status"

* run: "sudo dwww-index++ -f" and "sudo dwww-index++ -i" to update the manual pages for dwww.

* Run on Windows IE or an other Browser you like: http://127.0.1.1/dwww/ for Debian Manual Pages

* Run on Windows IE or an other Browser you like: http://127.0.1.1/testphp/ for for your PHP stuff.

# PROBLEMS

* maintenance/set_mysql_passwd doesn't work anymore

* shi3lD doesn't work