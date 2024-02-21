# Grant the User to assume a Role in AWS Console

- Create a New User without policies attached to it

- Create a New Role > Custom Trust policy.  Copy the [role.json](./role.json) modify it according to you.
  
- Now Attach another Policy along with this policy (eg: Ec2_Full_Access) . This will allow the user to assume a role that can have full access to Attached Policy.

- Save this Policy and attch it to the New User

- Now go to the role and Copy the link and provide to the user.

- Now the User can assume the Role whenever he clicks the link and he can also switch between roles from his Top Right Menu.

