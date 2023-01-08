# Moonlander2-bfgminer

# Currently only works up to Raspberry Pi Buster OS

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

Once that's done, run the script just made with ./ infront of the name.

	$ ./Example

If all is done well, you should see something like this.

	  bfgminer version 5.4.2-38-g106390a - Started: [2021-12-15 14:04:31] - [  0 days 00:15:42]
	  [M]anage devices [P]ool management [S]ettings [D]isplay options             [H]elp [Q]uit
	  Pool 0: us2.litecoinpool.o  Diff:7m  +Strtm  LU:[14:18:08]  User:Meap10.MLD
	  Block: ...466ce843948cbf24  Diff:12M (85.74T)  Started: [14:17:51]  I:13.58nBTC/hr
	  ST:3  F:0  NB:7  AS:0  BW:[ 54/ 15 B/s]  E:0.03  BS:1
	  1            |  3.40/ 3.30/ 3.29Mh/s | A:77 R:1+0(1.3%) HW:0/none
	  -----------------------------------------------------------------------------------------
 	  MLD 0:       |  3.38/ 3.30/ 3.29Mh/s | A:78 R:1+0(1.3%) HW:0/none
	  -----------------------------------------------------------------------------------------
	  [2021-12-15 14:11:53] Accepted 0059de96 MLD 0  Diff 11m/7m
	  [2021-12-15 14:11:54] Accepted 00636e9d MLD 0  Diff 10m/7m
	  [2021-12-15 14:12:02] Accepted 007dcc2f MLD 0  Diff 7m/7m
	  [2021-12-15 14:12:17] Accepted 00275bca MLD 0  Diff 25m/7m
	  [2021-12-15 14:12:27] Accepted 0077904a MLD 0  Diff 8m/7m
	  [2021-12-15 14:12:33] Accepted 002caaac MLD 0  Diff 22m/7m
	  [2021-12-15 14:12:35] Accepted 007e4fa6 MLD 0  Diff 7m/7m
	  [2021-12-15 14:12:37] Accepted 003f7644 MLD 0  Diff 15m/7m
	  [2021-12-15 14:12:55] Accepted 005de7fe MLD 0  Diff 10m/7m
	  [2021-12-15 14:12:55] Accepted 00052a2c MLD 0  Diff 193m/7m
	  [2021-12-15 14:12:58] Accepted 0008adce MLD 0  Diff 115m/7m
	  [2021-12-15 14:13:00] Accepted 006c8684 MLD 0  Diff 9m/7m
	  [2021-12-15 14:13:11] Accepted 005027d1 MLD 0  Diff 12m/7m
	  [2021-12-15 14:13:26] Accepted 001dcc7b MLD 0  Diff 33m/7m
	  [2021-12-15 14:13:27] Accepted 00061643 MLD 0  Diff 164m/7m
	  [2021-12-15 14:13:36] Accepted 006a1431 MLD 0  Diff 9m/7m


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


