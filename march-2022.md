## Enhancements

### Invite users without a Percona account to join your organization
As a member of an organization, you can invite other users to join your team even if their email address is not linked to a Percona account yet. 

Previously, only users with a Percona account could join Portal Platform organizations. 
The new users receive an email notifying them of the invite, and another one to activate their Percona account. 

As soon as their accounts are active, the new members can log in to Percona Platform and check the details of the organization.

### PMM Server addresses validated before connecting to Percona Platform  

To ensure that Percona Platform can reach the PMM instances connected to an organization, additional validation has been added to the **Connect PMM to Percona Platform** option in PMM. 

This means that Percona Platform now only stores and has access to correct PMM Server URLs.

### Synchronized Platform and PMM roles
After connecting a PMM server to Percona Platform, all members of the Platform organization were granted access to PMM as **Viewer** users.

We have now updated these permissions to ensure that Administrators of Portal organizations are also granted **Admin** role in PMM. 
Technical users in Platform continue to have **Viewer** role in PMM.



## Possibility to edit the organization name

You can now edit the name of your Percona Platform organization after creating it. 

This action is not available for organizations linked to Percona Customer Portal. If you are a Percona customer with a Percona Customer Portal account, the name of your organization is always retrieved from your Customer Portal account and cannot be changed from Percona Platform.

