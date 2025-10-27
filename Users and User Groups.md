Local users and groups management console snap-in is built in Computer Management, so after we open it, we can start working with users and groups. We can use the Run box to open the management console (MMC) with only local users and groups snapping in by typing “lusrmgr.msc” and pressing Enter.

Once we open Users snap in, to add a user, we would right-click anywhere inside the window and select “New User…” from the context menu. A new user window will open, and we must fill in the username and password. Other fields and settings are optional.

In the Groups window, we create new groups or add/remove users to/from existing groups. For example, to add a user, we would select a group, right-click on it and choose the “Add user” option from the context menu. To remove a user from a group, we would open a specific group, select a specific one from the list of users, right-click on it and choose the option “Remove user”

- **net user <_USERNAME_> <_PASSWORD_> /add** - Creates account with specific password
- **net user <_USERNAME_> /delete** – Removes user from Windows
- **net localgroup <_GROUPNAME_> <_USERNAME_> /add** - Adds account to a group
