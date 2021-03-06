## Prerequisites

To configure Azure AD integration with ICIMS, you need the following items:

- An Azure AD subscription
- A ICIMS single sign-on enabled subscription

> **Note:**
> To test the steps in this tutorial, we do not recommend using a production environment.

To test the steps in this tutorial, you should follow these recommendations:

- Do not use your production environment, unless it is necessary.
- If you don't have an Azure AD trial environment, you can get a one-month trial [here](https://azure.microsoft.com/pricing/free-trial/).

### Configuring ICIMS for single sign-on

To configure single sign-on on **ICIMS** side, you need to send the **[Downloaded SAML Metadata file](%metadata:metadataDownloadUrl%)**, **Azure AD Sign Out URL** : %metadata:singleSignOutServiceUrl%, **Azure AD SAML Entity ID** : %metadata:IssuerUri%, and **Azure AD Single Sign-On Service URL** : %metadata:singleSignOnServiceUrl%
 to [ICIMS support team](https://www.icims.com/contact-us). They set this setting to have the SAML SSO connection set properly on both sides.

## Quick Reference

* **Azure AD Single Sign-On Service URL** : %metadata:singleSignOnServiceUrl%

* **Azure AD Sign Out URL** : %metadata:singleSignOutServiceUrl%

* **Azure AD SAML Entity ID** : %metadata:IssuerUri%

* **[Download SAML Metadata file](%metadata:metadataDownloadUrl%)**

## Additional Resources

* [How to integrate ICIMS with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/active-directory-saas-icims-tutorial)
