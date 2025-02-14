# GTM-Tag-counter Script
Each html page has a script with the capability of automating the listing of all GTM containers, workspaces and tags of an GTM account.
# Functionalities
- Lists all Containers that belongs to a GTM Account. 
- Lists all Workspaces that belong to a GTM Container. (You can also adapt the code to filter it, so it can list based on properties like, accountId, containerId, workspaceId, name)
- Lists all GTM Tags of a Container.  (You can also adapt the code to filter it, so it can list based on properties like, accountId, containerId, workspaceId, tagId, name, type)

For more information: https://developers.google.com/tag-platform/tag-manager/api/v2

# Requirements and how to use it

- You need: GTM account id (), Google API Credentials, Client ID OAuth 2.0
- Create Client ID OAuth 2.0 here: https://console.cloud.google.com/apis/credentials
- Warning! Every time you use it, you have to update the code with your own key credentials 

All the requests requires authorization with at least one of the following scopes, authorized in this link: https://developers.google.com/oauthplayground/ 

* 1- Access https://developers.google.com/oauthplayground/ and authorize one of the scopes https://www.googleapis.com/auth/tagmanager.edit.containers | https://www.googleapis.com/auth/tagmanager.readonly
* 2- On cofiguration check the "Use your own OAuth credentials" box, and paste the Client Id and the Secret Key
* 3- Exchange your authorizaton code for token
* 4- Copy the bearer prefix and paste on the html code
* 5- Open the html on the navigator and run it

There also are instructions on the code

Please Contact me if any difficults

api overrall.html (lists all container, all workspaces, all tags)
api tags de midia.hmtl (list just tags named with Social Media names, like facebook, pintereste, etc)
api tags.html (list filtered tags, just change the words on 'const filtro=[]')
