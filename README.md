## About

This is a mash up of app code from https://github.com/workos/node-example-applications. Its purpose is to combine both SAML SSO and Directory Sync functionality in one app using WorkOS and Okta.

## Getting started

To run this app locally you will need a WorkOS organization outfitted with both an SSO and Directory Sync connection. In its current form it will only fetch one directory.

### Steps:

1. Clone the repo using the HTTPS or SSH method

   HTTPS

   ```
   git clone https://github.com/LizBaker/WorkOS-example.git
   ```

   SSH

   ```
   git clone git@github.com:LizBaker/WorkOS-example.git
   ```

2. Make sure you're working with a version of node >= 10
3. Run `npm install`
4. Add a .env file to the root of the project with your WorkOS API key and client ID specified in the following format:

   ```
   WORKOS_API_KEY=sk_ABC123
   WORKOS_CLIENT_ID=client_ABC123
   ```

5. Run `npm start` and navigate to http://localhost:8000 in your browser

6. Click on the Enterprise SAML login option to start the flow

## Video walkthrough

https://github.com/user-attachments/assets/d729fc83-25e7-44fb-83ad-4d5dca45a6db


