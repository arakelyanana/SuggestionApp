
# Suggestion App

## Description 

The primary goal of this project was to use MongoDB and the Blazor Server for the first time with authorization from Azure Portal. The user has the opportunity to submit suggestions for brand-new video ideas on this website. Suggestions can be verified and their status can be changed by admin users.


## Acknowledgements

 - [Suggestion Site App Course by IAmTimCorey](https://www.youtube.com/playlist?list=PLLWMQd6PeGY0cZFMqx5ijmdaD87sJKCsU)


## Run the project

To run this project you will have to have the profile in Azure Portal and in MongoDB.

You will have to use your ConnectionStrings from MongoDB.

The rest information you will feel in AzureAdB2C, you will get from Azure Portal. If you want to know how to feel this information check the link (the 20th video) provided in Acknowledgements.

```bash

  "ConnectionStrings": {
    "MongoDB": "<Your ConnectionStrings>"
  }
   "AzureAdB2C": {
    "Instance": "https://<username>.b2clogin.com/",
    "ClientId": "<Your ClientId>",
    "CallbackPath": "/signin-oidc",
    "Domain": "<username>.onmicrosoft.com",
    "SignUpSignInPolicyId": "B2C_1_susi",
    "ResetPasswordPolicyId": "B2C_1_reset",
    "EditProfilePolicyId": "B2C_1_edit"
  }
```
    
