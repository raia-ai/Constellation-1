---
title: Getting Started | Constellation1 Customer Hub
---

# Getting Started | Constellation1 Customer Hub

Before you begin with your integration, you’ll need to obtain the proper credentials from an eSign representative. Your eSign representative will create an administrative account to associate with the API integration. An API key will be generated and linked to your integration administrative account and provided to you for use in authenticating through the eSign web service.

### **API Selection**

**SOAP**

### Requirements

The following is required of your web service client:

*   SOAP 1.1 specification support
*   Ability to connect using HTTPS

### Connecting

The eSign web service is available in two environments: stage and production. The following tables specify how to obtain the WSDL for the SOAP endpoints in each environment:

### Overview

Typical eSign integrations follow the same general workflow: authentication, user management, and session creation.  Once a session is created through the API, the user is redirected to the eSign web application for session customization. After a signer has completed signing, eSign will post updates to a client’s endpoint acting as a listener service, notifying the client when documents are available for collection in addition to pushing documents once they are signed. This is simply a high level description and below is a flow chart of the general workflow.[![overview](https://docs.constellation1.com/wp-content/uploads/2015/02/overview.png)](https://docs.constellation1.com/wp-content/uploads/2015/02/overview.png)

### **RESTFUL**

### Requirements

The following is required of your web service client:

*   Ability to connect using HTTPS

### Connecting

The eSign web service is available in two environments: stage and production.

### Overview

Typical eSign integrations follow the same general workflow: authentication, user management, and session creation.  Once a session is created through the API, the user is redirected to the Constellation1 eSign web application for session customization. After a signer has completed signing, Constellation1 eSign will post updates to a client’s endpoint acting as a listener service, notifying the client when documents are available for collection in addition to pushing documents once they are signed. This is simply a high-level description and below is a flow chart of the general workflow.[![overview](https://docs.constellation1.com/wp-content/uploads/2015/02/overview.png)](https://docs.constellation1.com/wp-content/uploads/2015/02/overview.png)

Was this article helpful to you?

Was this article helpful to you?