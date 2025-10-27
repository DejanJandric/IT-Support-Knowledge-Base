There are a few ways to open the System Properties window, we will show the three fastest:

1. Right-click the My computer/Computer/This PC icon and then select Properties to open the System window.
2. Using Run box  – type „sysdm.cpl“ and hit Enter or press „OK“ button.\*\*
3. Via Control Panel – open Control Panel, click on the „System“ icon, and then on „Advanced system settings“. It will open the system properties 3d tab, Advanced.

Change computer name:

1. First open System Properties in one of the ways described above.
2. The first tab is labeled Computer Name. Click on it if it is not active already.
3. Near the bottom there is a description for Computer Name, to change it click on the button „Change“.
4. Enter the new computer name in the appropriate box. In this window, we can also change the workgroup, or join the computer to a domain.
5. Click on the "OK" button to apply changes.

The computer name will not become active until the device is restarted and it is advisable to do it as soon as possible, to avoid potential name conflicts in the network.

# **DOMAIN/WORKGROUP**

To set workgroup or join/disjoin computer to the domain:

1. First open System Properties in one of the ways described above.
2. The first tab is labeled Computer Name. Click on it if it is not active already.
3. Near the bottom there is a description for Computer Name, to change it click on the button „Change“.
4. Enter the workgroup name in the appropriate box. If the domain is used, click on the radio button and enter the domain name. You will be prompted for a domain account.
5. Hit the „OK“ button to apply changes.

# **ENVIRONMENTAL VARIABLES**

The environmental variables store data that is used by the operating system and other programs. Among other things, they store information about the operating system environment. This information includes details such as the operating system path, the number of processors used by the operating system, and the location of temporary folders. For example, the WINDIR environment variable contains the location of the Windows installation directory. Programs can query the value of this variable to determine where Windows operating system files are located.
To access the Environmental Variables window we would click on Environmental Variables at bottom of the System Properties Advanced tab.

# **LOCAL GROUP POLICY OBJECTS**

Local Group Policy is changed with tool called Local Group Policy editor. Easiest way to start it would be by typing gpedit.msc in Run or search box. After clicking “OK” or running search result, following screen should open.

Out of all settings in LGPO Editor, HRS industry support uses only Windows Settings > Security Settings > Local Policies. We check there if the user has proper access rights, set password policies, set network login rights, type of communication protocol used, etc. Most of these settings are grouped in “User Rights Assignments” and “Security Options” categories.

# **WINDOWS REGISTRY**

Windows Registry can be edited manually using programs such as RegEdit.exe, although these tools do not expose some of the registry's metadata such as the last modified date. Optional and/or third-party tools similar to RegEdit.exe are available for many Windows versions. The fastest way to start Registry Editor would be to type "regedit" in the Run box or search field and then hit “OK” or click on search result.

Registry Editor allows users to perform the following functions:

- Creating, manipulating, renaming, and deleting registry keys, subkeys, values, and value data
- Importing and exporting.REG files (Registration entries - text-based human-readable files for exporting and importing portions of the registry), exporting data in the binary hive format
- Loading, manipulating, and unloading registry hive format files (Windows NT systems only)
- Setting permissions based on ACLs (Windows NT systems only)
- Bookmarking user-selected registry keys as Favorites
- Finding particular strings in key names, value names, and value data
- Remotely editing the registry on another networked computer

# **EVENT VIEWER**

- The two fastest ways to start Event Viewer are:

1. Using Search box – type “event”, click on top result, and then click “Open”.

2. Using Run box – type “eventvwr.msc” in the box and hit the “OK” button or press *Enter*.

# **VISUAL C++ and .NET framework**

Applications written for Windows OS sometimes need additional components to work as intended. The best example would be the DirectX framework for games. Program installers usually install all additional software, but that is not always the case. HRS Industry POS systems and related modules need Microsoft Visual C++ and .NET framework for proper functioning.

Microsoft Visual C++ (MSVC) is a compiler from Microsoft for the C, C++, and C++/CLI programming languages. MSVC is proprietary software; it was originally a standalone product but later became a part of Visual Studio and was made available in both trialware and freeware forms. It features tools for developing and debugging C++ code, especially code written for the Windows API, DirectX, and . NET. Many applications require redistributable Visual C++ runtime library packages to function correctly and these packages are often installed independently of applications.

.NET Framework is a software development platform made up of tools, programming languages, and libraries for building and running many different types of applications on Windows. It is part of the .NET platform, a collection of technologies for building apps for Linux, macOS, Windows, iOS, Android, and more. There are a few versions of .NET, and the latest is 4.8. Since the framework is now considered deprecated, no new instances are announced.

# **How to set auto login**

1. Click **Start** button
2. In the search bar, type in "**Run**" and open the **Run.exe**
3. In Run.exe type this command **control userpasswords2**
4. Check the box **"Users must enter a username and password to use this computer" (if it is already checked, go to step 5.)**
5. Select the user that you would like to be logged in automatically every time Windows starts
6. Uncheck the **"Users must enter a username and password to use this computer"**
7. A Window will pop up prompting you for the password for the selected account, enter it
8. 1. Hit "**Ok**" and then hit "**Apply**"
