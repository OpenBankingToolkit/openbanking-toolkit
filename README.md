[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

# OpenBanking Tool Kit

This is the root repository of the ForgeRock OpenBanking toolkit, providing an overview of the toolkit, what it offers and a jumping off point to all the other repositories. This is your 'home page'.

![license](https://img.shields.io/github/license/ACRA/acra.svg)

### Open Banking Reference Implementation - Backend 

| Backend |Release version| Github repo | Description | 
|---|---| --- | --- | 
|Services|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-reference-implementation.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-reference-implementation)|[reference-impl](https://github.com/OpenBankingToolkit/openbanking-reference-implementation)| Example of how you can bundle all the micro-services together |

### Artifacts and libraries
| Artifact | Release version | Github repo | Description |
| --- | --- | --- | --- |
| eidas |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/eidas-psd2-sdk.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/eidas-psd2-sdk)| [eidas-psd2-sdk](https://github.com/OpenBankingToolkit/eidas-psd2-sdk) | A Java SDK to help you manipulate EIDAS - PSD2 certificates |
| uk-datamodel |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-datamodel.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-datamodel) | [uk-datamodel](https://github.com/OpenBankingToolkit/openbanking-uk-datamodel)| A Java data model library (Generated classes from OB Swagger documentation) for Open Banking uk: [read-write-apis](https://www.openbanking.org.uk/read-write-apis/)|
| maven parent | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-parent.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-parent)| [starter parent](https://github.com/OpenBankingToolkit/openbanking-parent) | Maven parent used by the ForgeRock OpenBanking maven project|
| common | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-common.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-common)|[common](https://github.com/OpenBankingToolkit/openbanking-common) | ForgeRock OpenBanking Commons is a set of abstractions and common classes used in different ForgeRock OpenBanking projects|
| clients | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-clients.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-clients)|[clients](https://github.com/OpenBankingToolkit/openbanking-clients) | ForgeRock OpenBanking clients used in different ForgeRock OpenBanking projects|
| jwkms | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-jwkms.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-jwkms)|[jwkms](https://github.com/OpenBankingToolkit/openbanking-jwkms) | The JWKMS provides essential key management functionality|
| auth | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-auth.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-auth)|[auth](https://github.com/OpenBankingToolkit/openbanking-auth) | ForgeRock OpenBanking Auth is a library that can incorporated into a project to enable login using Authorisation Code Flow|
| uk-extensions | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-extensions.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-extensions)|[uk-extensions](https://github.com/OpenBankingToolkit/openbanking-uk-extensions) | This library extensions has been designed to write the ad-hoc functions and operations to extend the existing ones|

### Bundles

| Bundle| Release version| Github repo | Description |
|---|---|---|---|
|ASPSP|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-aspsp.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-aspsp)| [openbanking-aspsp](https://github.com/OpenBankingToolkit/openbanking-aspsp/)|Protect your bank APIs using Open Banking. Provide FAPI conformance on top of an OIDC provider like ForgeRock AM|
|Analytics|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-analytics.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-analytics)|[openbanking-analytics](https://github.com/OpenBankingToolkit/openbanking-analytics/)|Provide analytics data of your Open Banking eco-system, ready to share to with the authority like FCA|
|Directory|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-directory.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-directory)|[openbanking-directory](https://github.com/OpenBankingToolkit/openbanking-directory/)|Central authority that issues certificates and SSA|
|TPP|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-tpp.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-tpp)|[openbanking-tpp](https://github.com/OpenBankingToolkit/openbanking-tpp/)|A sample TPP that implement OB UK 1.1|

### Release order
| Priority | type | latest version | project |
| --- | --- | --- | --- |
| 1 | artifact | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/eidas-psd2-sdk.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/eidas-psd2-sdk)| [eidas-psd2-sdk](https://github.com/OpenBankingToolkit/eidas-psd2-sdk) |
| 1 | artifact |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-datamodel.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-datamodel) | [uk-datamodel](https://github.com/OpenBankingToolkit/openbanking-uk-datamodel)|
| 2 |  artifact |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-parent.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-parent)| [starter parent](https://github.com/OpenBankingToolkit/openbanking-parent) |
| 3 | artifact | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-common.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-common)|[common](https://github.com/OpenBankingToolkit/openbanking-common) |
| 4 |  artifact |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-clients.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-clients)|[clients](https://github.com/OpenBankingToolkit/openbanking-clients) |
| 5 | artifact | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-jwkms.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-jwkms)|[jwkms](https://github.com/OpenBankingToolkit/openbanking-jwkms) |
| 5 | artifact | [![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-auth.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-auth)|[auth](https://github.com/OpenBankingToolkit/openbanking-auth) |
|6| bundle |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-aspsp.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-aspsp)| [openbanking-aspsp](https://github.com/OpenBankingToolkit/openbanking-aspsp/)|
|6|bundle |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-analytics.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-analytics)|[openbanking-analytics](https://github.com/OpenBankingToolkit/openbanking-analytics/)|
|6|bundle |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-directory.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-directory)|[openbanking-directory](https://github.com/OpenBankingToolkit/openbanking-directory/)|
|6|bundle |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-tpp.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-tpp)|[openbanking-tpp](https://github.com/OpenBankingToolkit/openbanking-tpp/)|
| 7| artifact |[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-extensions.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-uk-extensions)|[uk-extensions](https://github.com/OpenBankingToolkit/openbanking-uk-extensions) |
|8| services backend|[![GitHub release (latest by date)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-reference-implementation.svg)](https://img.shields.io/github/v/release/OpenBankingToolkit/openbanking-reference-implementation)|[reference-impl](https://github.com/OpenBankingToolkit/openbanking-reference-implementation)
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
