---
description: Learn about the end-of-life plans for the Device Co-op.
title: Device Co-op end-of-life FAQ
---
# Device Co-op end-of-life FAQ

This document provides answers to frequently asked questions about the end of life process for Adobe Experience Cloud Device Co-op. When this plan goes into effect, Adobe will give you advanced notice in [Experience Cloud Release Notes](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html) and the [Priority Product Update](https://www.adobe.com/subscription/priority-product-update.html).

## FAQ

The following is a list of answers to frequently asked questions about the [!DNL Device Co-op] end of life process.

## Why are you deprecating [!DNL Device Co-op]?

The upcoming changes in the AdTech environment are expected to result in [!DNL Device Co-op] becoming an obsolete solution in the coming years. [!DNL Device Co-op] is comprised mostly of third-party cookies and Google's announcement that they will be blocking third-party cookies on Google Chrome by 2022 will diminish the effectiveness of [!DNL Device Co-op]. Google Chrome has ~65% of the browser market share and other major browsers have already implemented blocking of third-party cookies. Once Google Chrome blocks third-party cookies, the majority of third-party cookies will be blocked and [!DNL Device Co-op] will be rendered obsolete.

## Why is Adobe ending [!DNL Device Co-op] sign-ups now?

Sign-ups are ending to prevent risks of not meeting customer expectations due to the upcoming industry changes around third-party cookies. [!DNL Device Co-op] takes a few months to be prepared and another few months to extract value from the service, and any further sign-ups at this point could result in brands not experiencing the full value of [!DNL Device Co-op].

## Can new customers sign up?

Starting June 11, 2021, Adobe will no longer accept new sign-ups to [!DNL Device Co-op].

## Are you renewing existing contracts?

Starting June 11, 2021, Adobe will no longer renew [!DNL Device Co-op] contracts. If you wish to continue using [!DNL Device Co-op] services, you may continue to do so under the current license terms until the program ends.

## What is the exact end date of the [!DNL Device Co-op] program?

The [!DNL Device Co-op] program will end in 2022. The specific timing and date depends on when Google starts to block third-party cookies.

## Are these dates subject to change?

An announcement will be made in June 2021 regarding the impending deprecation of [!DNL Device Co-op] in 2022. These dates are subject to change.

## Which applications will be affected by the Device Co-op end of life?

The following applications will be affected by the [!DNL Device Co-op] end of life procedures: Adobe Analytics, Adobe Audience Manager, Adobe Advertising Cloud, and Adobe Target.

## What are the alternative options to Device Co-op?

### Adobe Analytics

- Identity Service Private Graph
- Field Based Stitching

### Adobe Audience Manager

- Adobe Audience Manager maintains integrations with third-party device graph partners including [!DNL LiveRamp] and [!DNL Tapad].
  - Customers must establish commercial relationships with graph partners directly in order to leverage in Audience Manager.

### Real-time CDP

- Adobe has no plans to modify the current Audience Manager DMP offering. However, the deprecation of third-party cookies will likely create scale challenges for most DMP users, and we’re helping our customers evolve their data management practices reducing their dependencies on identifiers that face restrictions in the coming year. Marketing teams must build first-party data strategies focused on durable identifiers that include PII, which can be solved for with a Customer Data Platform (CDP).
- Adobe’s Real-time CDP reduces dependencies on third-party cookies and device IDs by expanding the set of identifiers available for audience creation to include PII (personally identifiable information). Foundational to Real-time CDP is the Real-time Customer Profile, which brings together person attribute data with behavioral data in real-time and allows marketers to create rich audience segments with patented data governance controls. Like Audience Manager, Real-time CDP powers insights and personalization use cases, but also generates more granular person-level insights and can activate audiences to a broader range of destinations spanning AdTech and martech, including paid media, social media, email, customer systems, and more.
- Real-time CDP will include access to Segment Match, which allows brands to expand their own first-party data sets through partnerships and achieve improved insights and personalization.

### Adobe Target

- There are currently no alternatives available for Adobe Target because [!DNL Target] provides a deterministic cross-device identity stitching capability known as `mbox3rdPartyId`, which functions similarly to Adobe's Customer ID. This capability allows [!DNL Target] customers to merge profiles and activity participation across [!DNL Target] tests and personalization being done in inbound channels.

### Adobe Advertising Cloud

- Adobe Advertising Cloud customers will no longer be able to use [!DNL Device Co-op] for cross-device audience targeting and measurement. [!DNL Advertising Cloud] customers will be able to leverage Adobe's [!DNL Device Graph] partnership with [!DNL LiveRamp] to continue to perform these functions to the extent of [!DNL LiveRamp’s] ability and scale.
- Customers need to let their campaigns that are using [!DNL Device Co-op] end, and then either switch to the LiveRamp device graph provider in the platform, or no longer leverage people-based targeting.

## What existing capabilities and implementations can help my preparation for a cookie-less future?

Your existing Visitor ID Service implementation powers Cross-Device Analytics, a feature of Adobe Analytics. If your existing declared ID is a hashed email, this can be used to power the following capabilities:

- People-Based Destinations, a feature in Real-Time CDP and Adobe Audience Manager.
- Segment Match (Beta), a feature in Real-Time CDP and Adobe Experience Platform Activation.

## Will I get to keep my data from [!DNL Device Co-op]?

For Audience Manager and Ad Cloud users, the data from Co-op will not be available to transfer to third party graphs.Co-op data will only be migrated for Analytics Ultimate users using Cross-Device Analytics with Co-op switching to Field-Based Stitching. All other solutions will not have their data migrated.

## Is it mandatory to adopt other features?

While adoption of other Adobe features is not mandatory, we strongly recommend that you start the implementation of other features as soon as possible to allow time and appropriate coordination in advance of Co-op deprecation.

## By when do I have to adopt alternative solutions if I choose to?

Adoption of other features is not mandatory. It is only recommended should customers wish to continue addressing use-cases that were addressed by Co-op.

If customers choose to adopt other features, they should do so by 2022 (exact timing to be announced) before the Co-op program ends.

## How long will the adoption take? 

This will depend on the feature. For example, if an Analytics Ultimate customer using Cross-Device Analytics with Co-op needs to migrate to Real-time Private Device Graph or Field-Based Stitching, adoption will take some time.