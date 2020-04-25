# OSDBIOSPrerequisitesTool
![UI](https://1.bp.blogspot.com/-hAkLcE0pWgo/XqROTpp9tCI/AAAAAAAAZHM/OFIDKVmePzwiLeIen_8FZy1j26a_NynKQCLcBGAsYHQ/s640/osdprereqTool_UI.png)


## New Features added:
 - checks for a config file remotely if enabled and exists. Gives us the ability to add or remove features if needed
 - Debugging mode, additional logging feature
 - Known Password list, this allows the tool to find the correct password for the BIOS to be able to configure it

## A few things I'd like to do:
 - Use the config to control system providers such as CCTK and the dell powershell module (which I can't get working) to support systems like HP
 - Make the powershell form open center of screen and bigger resolution when in UEFI mode for PE
 - Put a reboot button if system is not compliant and a continue if it is and remove the exit button
 - Hash the passwords in the config file or maybe have it look externally for it
 - Include task sequence logging
 - Remove the empty Model Information and Operating System group boxs and load the system info (like model, serial, ip, etc) in a box
 - Progress bar to display what step its on and what is left
 - Export button not working in the logging tab. I'd like to have it export the log to a share
 - It ultimately uses the Dell CCTK, running the commands (behind the scenes while logging them)
