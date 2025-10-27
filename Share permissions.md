# **NTFS and share permissions**

To see what kind of permissions are set on the **local file or folder**:

Right-click on the file/folder - Go to “Properties” - Click on the “Security” tab.

There are three types of share permissions: Full Control, Change and Read.

1. **Full Control:** Enables users to “read,” “change,” as well as edit permissions and take ownership of files.
2. **Change:** Change means that user can read/execute/write/delete folders/files within share.
3. **Read:** Read allows users to view the folder’s contents.

A file system organizes how data is stored on a drive and manages metadata such as permissions and file names.
NTFS, which stands for New Technology File System, is the modern file system used by Windows NT and subsequent Windows operating systems to store and retrieve files.

Before NTFS, Microsoft's older systems mainly used the File Allocation Table (FAT) system, designed for smaller disks and simpler folder structures.

NTFS supports larger file and disk sizes and offers more security features than FAT. Introduced in 1993 with Windows NT 3.1, NTFS is the default file system in Windows versions including Windows 10, 8, 7, Vista, XP, 2000, and NT.

![alt text](https://www.varonis.com/hs-fs/hubfs/Imported_Blog_Media/1-4.png?width=370&height=455&name=1-4.png)

When you share a folder and want to set the permissions for that folder – that’s a share. Essentially, share permissions determine the type of access others have to the shared folder across the network.

To see what kind of permissions you will be extending when you share a folder:

Right click on the folder
Go to “Properties”
Click on the “Sharing” tab
Click on “Advanced Sharing…”
Click on “Permissions”
And you’ll navigate to this window:

![alt text](https://www.varonis.com/hubfs/Imported_Blog_Media/2-4.png)

When using Share and NTFS permissions together, the most restrictive permission always takes precedence.

For example:

If share permissions are set to "Read" and NTFS permissions are "Full Control," the user will only have "Read" access when connecting through the share.

Conversely, if share permissions allow "Full Control" but NTFS permissions are "Read," the user's effective permission will still be "Read" due to the NTFS restriction.

This means the combined permission is the more limited one, ensuring tighter security. For managing access effectively, it is recommended to set share permissions at a broader level (e.g., Full Control) and use NTFS permissions for granular control, as NTFS permissions apply both locally and over the network. This approach maximizes flexibility and security without unintended permission escalation.

When managing permissions, if handling two separate sets—Share and NTFS permissions—is too complex, you can simplify by using only NTFS permissions.

Share permissions offer limited security with just three types (Read, Change, Full Control), whereas NTFS permissions provide greater flexibility and granular control for shared folders.

NTFS permissions apply whether access is local or over the network. To leverage this, set the share permissions for the folder to “Full Control.” This allows you to fully manage access through NTFS permissions without conflicts from share permissions interfering with your settings.

This approach optimizes security management and reduces complexity when configuring access to shared resources.

![alt text](https://user-gen-media-assets.s3.amazonaws.com/gemini_images/0d4f9b20-562f-4e21-b15a-7f9c2ea07459.png)
