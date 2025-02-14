# GTM-Tag-counter Script
Each html page has a script with the capability of automating the listing of all GTM containers, workspaces and tags of an GTM account.
# Functionalities
- Lists all Containers that belongs to a GTM Account. 
- Lists all Workspaces that belong to a GTM Container. (You can also adapt the code to filter it, so it can list based on properties like, accountId, containerId, workspaceId, name)
- Lists all GTM Tags of a Container.  (You can also adapt the code to filter it, so it can list based on properties like, accountId, containerId, workspaceId, tagId, name, type)

For more information: https://developers.google.com/tag-platform/tag-manager/api/v2

# Requirements and how to use it

All the requests requires authorization with at least one of the following scopes:
Scope
* https://www.googleapis.com/auth/tagmanager.edit.containers
* https://www.googleapis.com/auth/tagmanager.readonly
