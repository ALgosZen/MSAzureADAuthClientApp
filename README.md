How to add Microsoft authentication to web application - Node JS app

Setup azure account and go to active directory

https://docs.microsoft.com/en-us/azure/active-directory/develop/single-sign-on-saml-protocol

Register an application
Select 
Accounts in this organizational directory only (Default Directory only - Single tenant)

Make note of client id or application id .
Generate client credentials 
attach reply url


Goto quick start and pickup sample code of your choice. - python flask or nodeJS etc.,

Redirect URIs
http://localhost:3000/redirect

Download the code sample
Unzip and Open code folder in your favorite editor (VS Code here)
npm install
npm start



