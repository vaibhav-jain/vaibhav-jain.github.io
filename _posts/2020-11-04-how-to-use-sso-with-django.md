---
layout: post
comments: true
author: Vaibhav Jain
tag: ["SSO", "Django", "Python", "SAML"]
image: "/../assets/img/What-Happened-While-Your-Resume-Was-Sleeping.png"
description: "Have you ever wondered what happened to your resume?"
title: "How to use SSO/SAML with Django?"
---

![resume](/../assets/img/saml_flow.png)

• **What is SSO/SAML?**

• **Have you ever wondered how to setup your own SP using Django?**

• **How and where to store your user data?**

• **How to authenticate users and give access to your services/apps?**

---------------
# Let's start with basics of SSO & SAML

* **SSO - Single Sign-On**. Allows Users to sign on in one website or system and automatically be signed on in another website or system.
    See [http://en.wikipedia.org](http://en.wikipedia.org/wiki/Single_sign-on) for a detailed description of Single Sign-On.
* **SAML - Security Assertion Markup Language** is an open standard for exchanging authentication and authorization data between parties,
    in particular, between an identity provider and a service provider.
* **SAML Metadata**
    * The metadata used to make SAML work. 
* **Asserting party (AP) or Identity Provider (IDP)**
    * IDP is a service /website that provide user identity information like (username, security token and email address etc…) through Saml-2 Request/Response using HTTP-POST
    * Send assertions to relying party
* **Relaying party (RP) or Service Provider (SP)**
    * This is the actual website/client consumes the Identity information shared by the IDP through Saml 2
    * Request/Response using HTTP-POST
    * Consume the assertions from AP/IDP
* **Assertions**
    * Data exchanged from AP to RP (XML Data)
    * Can include user identity, authentication data, or any other attributes
* **User/Actor/Browser**
    * Request protected resource from service provider.
    * Act as bridge between SP and IDP for SAML communication. 

Learn more at:
* [https://labs.tadigital.com](https://labs.tadigital.com/index.php/2018/11/05/single-sign-on-with-saml-standards/)
* [http://help.learn.com/](http://help.learn.com/Content/Products/Integrations/Learn%20SSO/Learn%20SSO%20Terminology.htm#:~:text=SSO%20%2D%20Single%20Sign%2DOn.,in%20to%20LearnCenter%20as%20well.)

# How to Setup Idp?
Coming soon
