# React-Native-Firebase-deployment

CI/CD pipeline to automate the deployment of a react native app to firebase app distribution 

## Requisites

### `Firebase tokens`
> `${{secrets.FIREBASE_APP_ID_ANDROID}}` : This is the app ID which you can find from the firebase console under **project settings**

> `${{secrets.FIREBASE_TOKEN}}` : This is a token which you can get after configuring firebase on your local machine and then running 
> ***firebase login:ci*** to generate the token.

## Store these two tokens seperately under your
### Repository> Settings> Secrets> Actions> New Repository Key
