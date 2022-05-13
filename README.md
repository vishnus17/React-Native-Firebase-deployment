# React-Native-Firebase-deployment

CI/CD pipeline to automate the deployment of a react native app to firebase app distribution 


### `Firebase tokens`
> The app ID is the `${{secrets.FIREBASE_APP_ID_ANDROID}}` token which you can find from the firebase console under **project settings**

> Configure firebase on your local machine and run **firebase login:ci** to generate the `${{secrets.FIREBASE_TOKEN}}` token.

Store these two tokens seperately under your
## Repository> Settings> Secrets> Actions> New Repository Key
