---
layout: default
title: Relying Party
page: idp
---
### Relying Party

The Testpoint IDP is a standards compliant OICD Identity Provider. In adition to using it to authenticate and authorise synthetic ABN users against Testpoint services, you can also register your own services (OIDC Relying Parties). This way, it can be used to support development of arbitrary services requiring consent-based access to ABN identities.

Instructions:

*   Login to the IDP client with GitHub
*   Create your RP client using the web interface
*   Record the client id and client secret issued by the IDP
*   Configure your service (OIDC client) to use the credentials provided