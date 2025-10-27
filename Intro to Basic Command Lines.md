Command line queries for services are commands used in terminal or command prompt to check the status, start, stop, restart, or manage various services on your system. These commands are fundamental for diagnosing, controlling, or automating software support tasks on servers or desktops.

| Platform        | Check Status          | Start/Stop             | Restart                  |
| --------------- | --------------------- | ---------------------- | ------------------------ |
| Windows         | sc query wuauserv     | net start wuauserv     | Restart-Service wuauserv |
| PowerShell      | Get-Service wuauserv  | Start-Service wuauserv | Restart-Service wuauserv |
| Linux (systemd) | systemctl status sshd | systemctl start sshd   | systemctl restart sshd   |
| Linux (service) | service ssh status    | service ssh start      | service ssh restart      |

These commands are essential when handling application support, troubleshooting, and diagnostics for both Windows and Linux environments;
**Stopping and Starting a Service from Command Line**
To stop or start a service, from a Command Prompt run the following command string:

- net stop servicename
- net start servicename

**Query Service Information**
In order to query the service information, from a Command Prompt run the following command string:
sc qc <span style="color:red">servicename</span>
The results you will get will show as follows: **[SC] QueryServiceConfig SUCCESS**
To set the service as Automatic, from a command line type the following: sc config EdcSvr start= auto

| Startup Type        | Command      |
| ------------------- | ------------ |
| Automatic           | auto         |
| Automatic (Delayed) | delayed-auto |
| Manual              | demand       |
| Disabled            | disabled     |

**Run the Service under a Specific Account**
To set the service to logon with a specific account, from a command prompt you would use the following command string:
_sc config service obj= .\username password= password TYPE= own_
To set to the service to logon with the local account, the command string would be the following:
_sc config servicename obj= LocalSystem password= LocalSystem_

**Set the Failure Actions for the Service and Set the Reset Period**
To set the failure actions for the service and the reset period, from a command prompt type:
_sc failure servicename actions= restart/xxxxxx/restart/xxxxxx/""/xxxxxx reset= xxxxx_

**Define Dependencies**
To set the dependencies for a service, from the command prompt use the following command string:
_sc config servicename depend= dependency_

