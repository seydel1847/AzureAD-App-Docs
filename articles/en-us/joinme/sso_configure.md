## Prerequisites

To configure Azure AD integration with join.me, you need the following items:

- An Azure AD subscription
- A join.me single sign-on enabled subscription

> **Note:**
> To test the steps in this tutorial, we do not recommend using a production environment.

To test the steps in this tutorial, you should follow these recommendations:

- Do not use your production environment, unless it is necessary.
- If you don't have an Azure AD trial environment, you can [get a one-month trial](https://azure.microsoft.com/pricing/free-trial/).

### Configuring join.me for single sign-on

To configure single sign-on on **join.me** side, you need to send the **App Federation Metadata Url** which you have copied from Azure portal to [join.me support team](https://help.join.me/s/?language). They set this setting to have the SAML SSO connection set properly on both sides.

## Quick Reference

* **Azure AD Single Sign-On Service URL** : %metadata:singleSignOnServiceUrl%

* **[Download Azure AD Signing Certifcate](%metadata:CertificateDownloadRawUrl%)**

* **[Download SAML Metadata file](%metadata:metadataDownloadUrl%)**

## Additional Resources

* [How to integrate join.me with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/saas-apps/joinme-tutorial)
