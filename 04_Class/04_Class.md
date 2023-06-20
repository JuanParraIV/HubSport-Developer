[🔙 << Class 3](../03_Class/03_Class.md) | [Class 5 >>](../05_Class/05_Class.md)

[🔙 Back](../README.md)


# How will you connect your App to HubSpot
## What's the best way for users to access your app?
<img src="../assets/HubSpot.png" alt="Difference" width="800" height="">

## HubSpot:
- **API Key:**
  ### What permissions this grants:
  - Gives the user GOD mode to the entire Hubspot instance. its usage is not preferred and will be depreciated in the future.
  ### This is a good fit when: 
    - When first staring development and you want to quickly start working with the HubSpot API's and you haven't quite figured out what permissions you'll need just yet
    - At 
  - An API key is a simple and straightforward way to authenticate and access the HubSpot APIs.
  - You can generate an API key in your HubSpot account by going to Settings -> Integrations -> API key.
  - API keys are typically used for server-to-server integrations or when accessing the APIs from scripts or command-line tools.
  - Keep in mind that API keys have broad access permissions, so it's important to handle them securely.

- **OAuth:**
  - OAuth is a more secure and recommended authentication method for third-party integrations with HubSpot.
  - With OAuth, you can request authorization from a HubSpot user to access their account data.
  - To use OAuth, you need to create an app in the HubSpot Developer Dashboard and configure the necessary OAuth scopes and redirect URLs.
  - When a user authorizes your app, you receive an access token, which you can use to make API requests on their behalf.
  - OAuth is commonly used for applications that require access to specific user data and need to authenticate as individual users.

- **Private Application:**
  - Private applications are a type of OAuth application that allows you to authenticate and access your own HubSpot account data.
  - You can create a private application in the HubSpot Developer Dashboard.
  - Private applications use OAuth 2.0 for authentication, similar to other OAuth integrations.
  - Private applications are useful when you want to automate tasks or build custom functionality within your own HubSpot account.

- **Developer API Key:**
  - Developer API keys are used specifically for accessing certain HubSpot APIs that require additional permissions.
  - These keys are generated in the HubSpot Developer Dashboard and provide access to APIs like the CMS API or Ecommerce Bridge API.
  - Developer API keys are separate from the regular API keys and provide more granular control over access to specific APIs.




[🔙 << Class 3](../03_Class/03_Class.md) | [Class 5 >>](../05_Class/05_Class.md)
