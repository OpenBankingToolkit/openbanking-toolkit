[<img src="https://raw.githubusercontent.com/ForgeRock/forgerock-logo-dev/master/Logo-fr-dev.png" align="right" width="220px"/>](https://developer.forgerock.com/)

# OpenBanking Tool Kit

Root repository of the OpenBanking toolkit, providing you links to all the different repositories

| Bundle| Maven version| Github repo | Description |
|---|---|---|---|
|ASPSP|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-aspsp.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-aspsp)| [openbanking-aspsp](https://github.com/OpenBankingToolkit/openbanking-aspsp/)|Protect your bank APIs using Open Banking. Provide FAPI conformance on top of an OIDC provider like ForgeRock AM| 
|Analytics|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-analytics.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-analytics)|[openbanking-analytics](https://github.com/OpenBankingToolkit/openbanking-analytics/)|Provide analytics data of your Open Banking eco-system, ready to share to with the authority like FCA| 
|JWKMS (crypto service)|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-jwkms.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-jwkms)|[openbanking-jwkms](https://github.com/OpenBankingToolkit/openbanking-jwkms/)|Crypto service for your applications. Help you sign/validate JWS and more| 
|Directory|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-directory.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-directory)|[openbanking-directory](https://github.com/OpenBankingToolkit/openbanking-directory/)|Central authority that issues certificates and SSA| 
|TPP|[![Bintray](https://img.shields.io/bintray/v/openbanking-toolkit/OpenBankingToolKit/openbanking-tpp.svg?maxAge=2592000)](https://bintray.com/openbanking-toolkit/OpenBankingToolKit/openbanking-tpp)|[openbanking-tpp](https://github.com/OpenBankingToolkit/openbanking-tpp/)|A sample TPP that implement OB UK 1.1| 
|License|![license](https://img.shields.io/github/license/ACRA/acra.svg)|||

# What is this tool kit?

Designed for banks that wishes to offer Open Banking APIs. 

This tool kit is providing assets for building up a full Open Banking eco-system. By this, we means that it not only provides
an ASPSP service, but also an Open Banking directory, a sample TPP, an analytics, etc.

The kit is composed of micro-services, that we group together as bundle.

An example is our core bundle ASPSP, which is offering you FAPI conformance for Open Banking UK and CDR. 
It's also enhancing the AS, like the dynamic registration,to be as Open Banking UK describes it (a signed JWT as a payload instead of a JSON).
Each bundle got a dedicated repo, which would provides documentation in the readme.

# Why a tool kit?

Composed as Spring boot micro-services, you can extend any of them or even replace one completely if you wish to. It offers you
a complete flexibility, without loosing the benefits of the maintenance of this repository.
An example of this flexibility is the ability to add new security feature on top of FAPI, and still get the fixes we do on the FAPI gateway.

# Awesome! But where should I start?

Have a look to our different repos, especially the readme. They are classic spring boot applications, a bit like spring cloud.

# Do I need to adopt all the bundles or can I cherry-pick what I need?

You can cherry-pick only what you are interested in. A common one is to only take our Open Banking directory, as you may already
got an ASPSP implementation.
Another one that is a good one to cherry-pick on its own, is the analytics. 

