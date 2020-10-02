# Google OAuth2 Authentication in NodeJS

Implementing authentication via Google in a Node.js web application. For this, we’ll be using Passport.js, an authentication package for Node.js.

## Step 1: Create a Google client ID and client secret

We can create a client ID and client secret using its Google API Console. You need to follow below steps once you open Google API Console

* From the project drop-down, select an existing project, or create a new one by selecting Create a new project

* In the sidebar under "APIs & Services", select Credentials
* In the Credentials tab, select the Create credentials drop-down list, and choose OAuth client ID.
* Under Application type, select Web application.
* In Authorized redirect URI use http://localhost:3000/auth/google/callback
Press the Create button and copy the generated client ID and client secretInstallation

**Note**: If Google doesn't support [http://localhost:3000](http://localhost:3000), then use [http://127.0.0.1:3000](http://127.0.0.1:3000)


## Setup and run
to setup this project, run the following commands on your terminal
```bash
1. to clone the project `git clone https://github.com/giftmbanda/GoogleOAuth2Node`
2. navigate to the project directory `cd GoogleOAuth2Node`
3. install neccesary packages, modules `npm install`
4. in the index.js file, use your clientID and clientSecret instead with yours.
5. to run the project `npm start`
6. using POSTMAN you can use this default url of `http://localhost:3000`
```
## Author
[Gift Banda](https://giftmbanda.com)