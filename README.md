# Moonlander2-bfgminer



bfgminer for Moonlander2 USBs

Usage:

First run the AutoInstaller to compile and install cgminer.

	$ ./AutoInstaller

Wait for the AutoInstaller to finish and then use the Worker Generator to make executable bash file for running miner.

	$ ./Worker-Generator

First, choose a name for the bash script to be saved as, no spaces allowed.

	  Save As:
	  Exampe

Second, Insert chosen pool url.

	  Pool URL:
	  stratum+tcp://us2.litecoinpool.org:3333

Third, Insert worker name for selected pool.

	  Pool Worker:
	  Meap10.MLD

Forth, Insert worker password.

	  Worker Password:
	  x

Fifth, Select the frequency for running the Moonlander2

	  Frequency for Miner:
	  Usable Frequencies:
	  384, 450, 480, 540, 576, 600, 612, 625, 636, 648, 660, 672, 684, 700, 720, 744, 756, 768, 796, 832, 852, 876, 900, 924, 954.
	  **Use Cooling and Powered Hub for anything passed 600!**
	  600

Sixth, Now you can Insert any extra arguments for cgminer, If none just hit enter.

	  Extra Arguments For bfgminer:
	  Example: --suggest-diff 32
	  **If none hit Enter**
	  --suggest-diff 1

Once that's done, run the script just made with ./ infront of the name.

	$ ./Example

If all is done well, you should see something like this.



# Using the Shortcut-Generator

First run the Shortcut-Generator.

	  $ ./Shortcut-Generator

Second, choose a name to save Shortcut as use hyphens or underscores instead off spaces.

	  Save As:
	  Example


Third, type in the system username. example pi if running on Raspberry Pi.

	  Username for system:
	  pi

Fourth, type in the name of the file you made with the worker-generator.

	  Bash File:
	  Example

Once done there should be a Shortcut on the desktop of your machine.

When doubletapping the shortcut select run in terminal option.


