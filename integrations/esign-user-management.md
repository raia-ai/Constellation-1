---
title: eSign - User Management | Constellation1 Customer Hub
---

# eSign - User Management | Constellation1 Customer Hub

### User Management

Typical integrations implement basic user management for access control and billing purposes. Basic user management involves maintaining references to user accounts in the eSign system through their respective unique identifier known as system user ID. This ID is obtained after creating a user through the API and makes it possible to push basic user information changes to the eSign system.  Storing this ID is crucial to ensuring a smooth user management experience.  User email accounts are required to be unique in the eSign system and can be activated and deactivated as a method of access control and for billing purposes.  For the best eSign experience the user’s time zone should be specified by the client in order to show meaningful data on documents and logs.

Before creating a new account it is a good idea to load a user object by the email address.  If a user has no account in the eSign system, a new account should be created and the returned ID should be stored.  If a user has an existing ID the next step would be ensuring that the user has an active status and synchronize any known changes to user information.

User properties supported by the API can be viewed in User Interface Classes in Appendix B. When requesting user information, the user object is returned in the UserResponse Interface Class and can be viewed in Appendix B. Refer User Management under the API Reference section for the supported user management APIs

[![quote](https://docs.constellation1.com/wp-content/uploads/2015/02/quote.png)](https://docs.constellation1.com/wp-content/uploads/2015/02/quote.png)

Was this article helpful to you?

Was this article helpful to you?