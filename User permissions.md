# User management and permissions

## Adding users and assigning them to a group

After booting up my virtual server, and connecting via SSH, I add two users.

![Add users](screenshots/Add_users.png)

Next, I create a group ('labstaff') and assign my new users to it.

![Group created](screenshots/Add_users.png)


Having confirmed that they are successfully assigned to the group, I create a directory and a file to practice permissions. I assign labstaff read and write permissions.

![Group permissions](screenshots/group_permissionconfig.png)

To test that permissions are working correctly, I switch over to Bill.

![Bill permissions](screenshots/Bill_permissions.png)

Next I created a temporary user with no access to the directory, to ensure that they will be denied permission.

![Tempuser](screenshots/Tempuser_permission.png)

I then give Bill sudo (root) privileges, and verify.

![Bill_sudo](screenshots/Bill_sudo.png)

With everything working as expected, I take a snapshot in Virtualbox.

![Snapshot](screenshots/Snapshot3.png)
