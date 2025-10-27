# **The printer will not power on**

Troubleshooting Steps to Resolve:

1. Move the printer to a known-good power outlet or BBU.

2. Use a known-good power adapter

3. If the printer will not power on using a known good power source (outlet/BBU) and when using a known good power cord, gather model/serial/printer name and escalate for replacement.


**The printer has power but will not print**

Troubleshooting Steps to Resolve:

1. Has the printer ever worked at the affected location and/or has it ever worked in the expected fashion? If yes, proceed to step 2. If not, and this is a new printer to the location, it may not be configured in the database properly. Escalate to the client’s database administrator.
2. Ask the caller (or verify yourself by VNC into a terminal) does Aloha indicate the affected printer is ‘OFFLINE’ when the user goes from the Floating Logo screen to the login screen? Does the POS indicate any other kind of error regarding the printer? (Not communicating, Out of Paper, etc).

a.       If the POS indicates an error with the printer, this is likely a problem with communication between the printer and the POS.

1. Perform a Self Test : power off the printer, have the caller hold the ‘FEED’ button while powering the printer back on. This should cause the printer to print out a diagnostics chit, which will confirm the printer is physically capable of printing. If yes, proceed to step 4. If not, gather model/serial/printer name and escalate for replacement.
2. Verify the printer is plugged into the correct port on the terminal, as configured in the database. Refer to the “Where do my printers connect” section below.
3. Swap out the printer serial/network cable with a known good cable. If a known-good cable resolves the issue, the cable was bad and will need to be replaced. If not, it’s either the printer or the terminal com port. Proceed to step 5.

a. If this is a remote printer, there will be two cables involved: From the terminal COM port to the wall jack and from the printer to its wall jack. These will need to be swapped separately to test both.

1. Swap the printer to a known good terminal. If the affected printer works at a known-good location, and when using a known-good cable, then the COM port on the original terminal is probably bad. This will require the terminal be replaced.

a. Alternatively, if there is an empty COM port on the terminal not in use, we may be able to change the port setting for the printer in the database to use the empty com port instead. However this is dependent on whether we, as Support, are both able and authorized to make database changes for the client. Refer to client documentation or Leadership.

1. If the printer still doesn’t print at a known-good terminal, and when using a known-good cable, the com port on the terminal is likely the issue and the printer should be escalated for replacement.

Other Steps to resolve:
- Verify printer groups
- Verify printer routing



# **Printer is printing gibberish, or wild characters**

If a site calls in stating that the printer was working fine then started printing gibberish perform the following:

1. Have the site hold down the FEED button for 20 seconds to clear printer cache in the printer
2. Power down the terminal that drives this printer – while the terminal is rebooting – delete the PRT*.LOG files on the FS in the Data folder (any file beginning with PRT and ending in .LOG)
3. When the terminal starts back up, verify that it prints correctly. If this does not resolve the symptom, proceed to the next step
4. Many/most printers (especially remote printers/non-receipt) utilize an adapter piece, which converts one cable connection into another (e.g. converts an RJ-45 cable into a DB-9 connection). These adapters can be present at both the terminal COM port and also at the printer itself. These adapters should be individually swapped out with a known good adapter (if one is available) to determine if one of these has gone bad. If a known-good adapter resolves the issue, escalate to have the adapter(s) replaced. If known good adapters do not resolve the issue, proceed to the next step
5. Keep in mind many managers will confuse that the adapter is a separate piece and not part of the cable itself. You will need to be clear in your description of the adapter to ensure it is not overlooked.
6. Swap in a known-good printer to the affected location. Does the problem persist at that location? The affected printer could be failing as well and may require replacement if none of the above works.