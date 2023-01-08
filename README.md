A Google OAuth example, without Passport.

Create from the inspiration from the following resources

The UI app with react is not needed in this case.

Medium: https://tomanagle.medium.com/google-oauth-with-node-js-4bff90180fe6

YouTube: https://www.youtube.com/watch?v=idqhYcXxbPs

### 0. Modify config.ts with your environment
### GCP Console->APIs&Services->Crentials Add Web App
### auto javascript http://localhost:4000
### redirect URL http://localhost:4000/auth/google
### get Client ID and Client Secret
### 1. Click on "1" to see whether it is producing the right URL
 http://localhost:4000/auth/google/url
### 2. Click on the auth URL to get authenticated in GCP IAM
### 3. Get authenticated and the control redirected to http://### localhost:4000/logged
### 4. Click on the link to see the user information from  http://localhost:4000/auth/me