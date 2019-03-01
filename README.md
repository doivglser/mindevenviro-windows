# mindevenviro-windows TESTING

* the same scripts like mindevenviro-debian but without X11 - Apps

# M1ND3V3NV1R0 DevOps (testing v0.0.1B)

		  codecounter: code without blank lines and without comments

- Lines =1466

- Words =6892

- Chars =51354

# Install

### download https://sourceforge.net/projects/dos2unix/ to convert line endings to unix.

* Make a shortcut on the desktop, right-click, New, shortcut, write powershell and click Next. 
* A new link is created. Right-click on the Powershell shortcut and run as administrator. 
* Type the following line in the Powershell: 

### "Enable WindowsOptionalFeature Online Feature Name Microsoft Windows Subsystem Linux." 

* You may need to reboot. 

* After this setting, enter, in the Microsoft Store, "linux", choose "debian" and install it.

* Run the Debian app, and type in the command line: "sudo apt-get -y -f --fix-missing install git".

* do: "cd /mnt/c/Users/$USER/Documents/" 

* $USER is your User-Name in Windows and you must run your Windows as administrator.

* do: "pwd" you should be in "/mnt/c/Users/$USER/Documents/"

* user@host:/mnt/c/Users/$USER/Documents/ "git clone https://github.com/doivglser/mindevenviro-windows.git" 

* The above step should clone mindevenviro-windows, in to your Documents folder in Windows 10.

* do within the Debian App: "ln -s /mnt/c/Users/$USER/Documents/mindevenviro-windows /home/$USER/"

* $USER in Windows 10 and $USER in the Debian App may differ.

* In your home/$USER/ folder you should have a Sym-link from Documents to your home/$USER/ folder in the Debian App.

* do: "cd mindevenviro-windows"

* check the entry in the /etc/sudoers file: "cat /etc/sudoers" if your username ist not listed then edit.

* "user@host:~/mindevenviro-windows/sudo ./mde-setup" "sudo ./mde-setup" installs or updates mindevenviro-windows.

# USAGE:

* startup the environment: run: "startup" on new login to Windows 10.

* You can edit your Projects with your favorite IDE, I use in Windows 10: "Notepad++", from within Windows Explorer in the Documents folder.

* run: "sudo sCRYPtUPdater -w 30 testpython/" to check syntax with a workflow interval of 30 minutes in to your testpython folder.

* run: "ls /usr/local/bin" to see scripts

* update your Virus definitions: "sudo freshclam"

* start your Antivirus protection for all Users on your Windows machine: "sudo /etc/init.d/clamav-daemon start"

* check if Antivirus is running: "sudo /etc/init.d/clamav-daemon status"

* check if apache2 is running: "sudo /etc/init.d/apache2 status"

* check if mysql is running: "sudo /etc/init.d/mysql status"

* check if sendmail is running: "sudo /etc/init.d/sendmail status"

* run: "sudo dwww-index++ -f" and "sudo dwww-index++ -i" to update the manual pages for dwww.

* Run on Windows IE or an other Browser you like: http://127.0.1.1/dwww/ for Debian Manual Pages

* Run on Windows IE or an other Browser you like: http://127.0.1.1/testphp/ for for your PHP stuff.

# FEATURES

### Syntax Checker
* sudo sCRYPtUPdater --help
### Search script, uses find, nano, less, mupdf(not in windows)
### "dd" magic number test statement, converting the null byte in the pipeline
* sudo search --help
### Antivirus
* sudo /etc/init.d/clamav-daemon start
### Web Server
* sudo /etc/init.d/apache2 start
### MySQL Server
* sudo /etc/init.d/mysql start
### Monitors
* status | logdiskussage
### MTA
* sudo /etc/init.d/sendmail start

# Files

### .wH0rUNSon

* log file in $HOME

# Scripts

### search
### sCRYPtUPdater
### mysql_cp_db
### set_mysql_passwd
### mde-setup
### logdiskussage
### status

# GNU Tools

### nmon
### mutt
### nano
### mc

# Languages

###  Bash, PHP, MySQL, Python, Perl, HTML

# Thanks

### Google, StackExchange, GitHub

# Screenshots

![](https://raw.githubusercontent.com/doivglser/mindevenviro-windows/master/docs/startup_01.jpg)
![](https://raw.githubusercontent.com/doivglser/mindevenviro-windows/master/docs/notepadplusplusconvert2unix.png)
![](https://raw.githubusercontent.com/doivglser/mindevenviro-windows/master/docs/scritpupdater.png)
![](https://raw.githubusercontent.com/doivglser/mindevenviro-windows/master/docs/searchscript.png)
![](https://raw.githubusercontent.com/doivglser/mindevenviro-windows/master/docs/whorunson.png)

# PROBLEMS

* ERROR: ScanOnAccess: fanotify_init failed: Function not implemented
* The workaround from mindevenviro-fanciful doesn't work within the Debian App, the ERROR message persists.
