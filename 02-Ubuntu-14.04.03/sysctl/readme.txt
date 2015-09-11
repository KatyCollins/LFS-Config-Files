
sysctl

--------------------------------------------
Description:
--------------------------------------------

This is the way to set system parameters that can change the way that the system functions.

More documention can be found at:
https://www.kernel.org/doc/Documentation/sysctl/

At this time, the documentation that I can find on this is fairly limited.  So, I am keeping these files as a way for me to figure out what all of parms do and to create a documentated sysctl.conf file that explains what all the parms in the "sysctl -a" ouput do.

--------------------------------------------
Files:
--------------------------------------------

sysctl_a.conf
	this is what happens when you enter "sysctl -a" at the CLI
	it gives you a full list of system parameters

sysctl.conf
	stored in /etc/sysctl.conf
	any uncommented settings here will be effective as of the next reboot
		you can make it effective immediately after saving the file by entering "sudo sysctl -p"

	



---------------------------------------------