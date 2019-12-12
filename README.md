[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

# OpenBanking Tool Kit

This is the root repository of the ForgeRock OpenBanking toolkit, providing an overview of the toolkit, what it offers and a jumping off point to all the other repositories. This is your 'home page'.

| Bundle| Maven version| Github repo | Description |
|---|---|---|---|
|ASPSP|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-aspsp.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-aspsp)| [openbanking-aspsp](https://github.com/OpenBankingToolkit/openbanking-aspsp/)|Protect your bank APIs using Open Banking. Provide FAPI conformance on top of an OIDC provider like ForgeRock AM|
|Analytics|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-analytics.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-analytics)|[openbanking-analytics](https://github.com/OpenBankingToolkit/openbanking-analytics/)|Provide analytics data of your Open Banking eco-system, ready to share to with the authority like FCA|
|JWKMS (crypto service)|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-jwkms.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-jwkms)|[openbanking-jwkms](https://github.com/OpenBankingToolkit/openbanking-jwkms/)|Crypto service for your applications. Help you sign/validate JWS and more|
|Directory|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-directory.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-directory)|[openbanking-directory](https://github.com/OpenBankingToolkit/openbanking-directory/)|Central authority that issues certificates and SSA|
|TPP|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-tpp.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-tpp)|[openbanking-tpp](https://github.com/OpenBankingToolkit/openbanking-tpp/)|A sample TPP that implement OB UK 1.1|
|License|![license](https://img.shields.io/github/license/ACRA/acra.svg)|||

# What is this tool kit?

This toolkit has been designed to help financial organisations build secure reliable Open Banking APIs. It enables financial organisations to allow their customers to securely provide access to their data and accounts to other financial service providers such as account aggregator apps, or easy payment apps.

It provides assets that allow the creation of a full Open Banking ecosystem. Not only does it provide the full Open Banking API implementation complete with a proven conformant security profile, but also an Open Banking directory, a sample third party application, an analytics and reporting application, sample Third Party Provider code that uses the Open Banking APIs and a service that provide complex security functions to make your life easier. 

The kit is composed of micro-services that can be orchestrated to provide certain Open Banking functionality. For example, the [openbanking-aspsp](https://github.com/OpenBankingToolkit/openbanking-aspsp/) repository contains code that builds a number of micro-services that provide;

- A Resource Server (RS) that provides Account and Transaction APIs, Payment Initiation APIs, Conformation of Funds APIs and Event Notification APIs.

- An Authorisation server - provides authentication and authorisation to securely protect access to the Resource Server resources
- A Manual Onboarding application that can be used by ASPSPs to let TPPs sign up to use their APIs manually
- A number of services that provide a bank simulation capable of servicing requests made to the Resource Server Open Banking APIs. This can be used to provide an Open Banking Sandbox which allows developers, both within the organisation providing the APIs and those developing applications against those APIs, to develop and test code in a safe environment without needing to have accounts with the API provider and with no danger of handling real data or making real payments.

# Why a tool kit?

The Java micro-services that make up the toolkit are implemented using [spring boot](<https://spring.io/projects/spring-boot>). UIs are coded using node and Angular. You can extend or replace services as needed to build an ecosystem specific to you. It offers you complete flexibility without loosing the benefits of the maintenance of this repository. An example of this flexibility is the ability to add new security feature on top of FAPI, and still get the fixes we do on the FAPI gateway.

# Awesome! But where should I start?

Have a look to our different repositories and learn from the READMEs provided for each. 

# Do I need to adopt all the bundles or can I cherry-pick what I need?

You can cherry-pick only what you are interested in. A common one is to only take our Open Banking directory, as you may already have an ASPSP implementation.

Another one that is a good one to cherry-pick on its own, is the analytics. 