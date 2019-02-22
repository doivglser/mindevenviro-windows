# mindevenviro-windows

* the same scripts like mindevenviro-debian but without X11 - Apps

# M1ND3V3NV1R0 DevOps (testing v0.1.1B)

		  codecounter: code without blank lines, without comments and without thirdparty

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

* user@host:/mnt/c/Users/$USER/Documents/ "git clone git@github.com:doivglser/mindevenviro-windows.git" 

* The above step should clone mindevenviro-windows, in to your Documents folder in Windows 10.

* do within the Debian App: ln -s /mnt/c/Users/$USER/Documents/mindevenviro-windows /home/$USER/ ($USER in Windows 10 and $USER in the Debian App may differ.)

* In your home/$USER/ folder you should have a Sym-link from Documents to your home/$USER/ folder in the Debian App.

* "cd mindevenviro-windows"

* "user@host:~/mindevenviro-windows/sudo mde-setup"

* You can edit your Projects with your favorite IDE, I use in Windows 10: "Notepad++", from within Windows Explorer in the Documents folder.