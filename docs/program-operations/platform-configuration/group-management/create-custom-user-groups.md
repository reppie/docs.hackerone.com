---
title: "Create Custom User Groups"
path: "/docs/program-operations/platform-configuration/authentication/sso-via-saml"
---

You can have customized groups with different access rights on your program. HackerOne program administrators can set these access rights for groups on your team. All security teams start with Admin and Standard default groups with set permissions that you can't edit, but you can still add or remove users to these groups. 

![user group](https://github.com/Hacker0x01/docs.hackerone.com/blob/master/docs/program-operations/platform-configuration/images/user-group.png?raw=true)

To add a new group and set access rights:
1. Go to your program's **Settings > General > Group Management**. 
2. Click **Add Group**.
3. Write the name of the group in the **Name** field. 
4. Select the permissions you want to enable for the group. You can select from these options:

Option | Details
------ | ------
Report | Users in the group can: <ul><li>Post comments</li><li>Change report states</li><li>Edit report titles and vulnerability types</li><li>Suggest bounties</li><li>Add/Remove external participants from reports</li><li>Edit common responses</li><li>Edit triggers</li><li>Request public disclosure</li><li>Agree to public disclosure request</li>
Program | Users in the group can: 
Reward | Users in the group can: <ul><li>Grant rewards</li><li>Post comments</li><li>Suggest bounties</li>
Admin | Users in the group can: <ul><li>Add/Remove users</li><li>Edit user permissions</li>

*Note: All groups have the ability to view reports and post internal comments by default.* 

5. Click **Create**. 

To edit your group name and permissions, click **Edit**.

To add or remove users to the group:
1. Click **Add/Remove users**.
2. Select the check box of the users you want to add to the group.
3. Deselect the check boxes of the users you want to remove from the group. 
3. Click **Update**.  