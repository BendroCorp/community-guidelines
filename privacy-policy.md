# BendroCorp Privacy Policy
This Privacy Policy applies to all BendroCorp services and integrations.

## Overview
This privacy policy has been compiled to better serve those who are concerned with how their 'Personally Identifiable Information' (PII) is being used online. PII, as described in US privacy law and information security standards, is information that can be used on its own or with other information to identify, contact, or locate a single person, or to identify an individual in context. Please read our privacy policy carefully to get a clear understanding of how we collect, use, protect or otherwise handle your Personally Identifiable Information in accordance with our website.

## Information Ownership
You retain full ownership over any PII you submit. By submitting content (ie. Text, Videos, Screenshots, Stories, Roleplay, etc) which is not PII you hereby grant BendroCorp a perpetual, unlimited, non-revokable license to store, retain and use any such content in any way for as long as BendroCorp sees fit. For data integrity reasons most content “deletions” are actually “archivals” and made non-visible do the content is no longer displayed. If you choose to fully terminate your account, via written notice, all content added by your account tied to your account will be anonymized within our service within seven (7) working days.

## What personal information do we collect from the people that use this application?
Currently when connecting to our application stack we may collect the following personal information at various times:
- Email
- Address Information: Street Address, City, State, Zip Code, Country
- Credit Card Information
- IP Address
- Geolocation
- Device identifiers
- Any other personal information you submit to us not otherwise directly collected for operating the service through voluntary submission (ie chats, messages, etc) 

## When do we collect information?
We collect information from you when you register on our site, fill out forms or generally enter information on our site. We also gather geolocation data based on your IP address from third party sources.

## How do we use your information?
We use the information you provide from direction collection of the above data for the following purpose:
- Email
   - Email data is gathered to aid in facilicating the authentication of your identity and as an avenue for communicating with you.
- Address Information
   - We only collect address information for the purpose os shipping physical items to you from the BendroCorp swag store and exchange.
   - In the case of the BendroCorp exchange, by entering in an a sale agreement with an item seller you authorize us to release your information to the selling member.
- Credit Card Information
  - We temporarily gather credit card information from you solely for the purpose of facilitating payments. We do not store credit information at all within the BendroCorp service. Any payment card information is passed to our payment processor. Please see the section for **Stripe** in our **Third-party disclosures**.
- IP Address
  - We gather your IP address information for information security purposes. Your IP addresses allows to determine where a request originated from which allows us to prevent bad actors from accessing your data and our data.
- Geolocation
  - We collect geolocation data based on IP address for the afformentioned purpose.
- Device Identifiers
  - We gather device identiers to both track the number of installations and when combined with push notifications we use that information to ensure that are not sending duplicate device notifications.

At no time do we use any of your information for advertising purposes or any other purpose not directly involved in facilitating the operation of the service.

## How do we protect your information?
We encrypt your personal data wherever possible.

We only allow third parties who you affirmatively consent to have access to your data except where those 3rd parties are required to operate the service.

We conduct frequent vulnerability assessments and security reviews.

Your personal information is contained behind secured networks and is only accessible by a limited number of persons who have special access rights to such systems, and are required to keep the information confidential. In addition, all sensitive/credit information you supply is encrypted via Transport Layer Security (TLS) technology.

We implement a variety of security measures when a user enters, submits, or accesses their information to maintain the safety of your personal information.

All transactions are processed through our payment provider Stripe. We do not store your credit card or financial information on our servers but we do maintain a list of billing transactions including billing amount and billing date.

## Do we use 'cookies'?
Yes.

Cookies are small files that a site or its service provider transfers to your computer's hard drive through your Web browser (if you allow) that enables the site's or service provider's systems to recognize your browser and capture and remember certain information. For instance, we use cookies to help us remember and process the items in your shopping cart. They are also used to help us understand your preferences based on previous or current site activity, which enables us to provide you with improved services. We also use cookies to help us compile aggregate data about site traffic and site interaction so that we can offer better site experiences and tools in the future.

We use cookies to:
To allow for you to remain logged in be safely storing a refresh token.

You can choose to have your computer warn you each time a cookie is being sent, or you can choose to turn off all cookies. You do this through your browser settings. Since browser is a little different, look at your browser's Help Menu to learn the correct way to modify your cookies.

## Other Persistence Caches
The primary way we maintain your session within a browser environment is via "local storage". Local storage is a newer technology within browsers which allow websites to store more sophisticated strings of data.

If users disable cookies in their browser:
If you turn cookies off, Some of the features that make your site experience more efficient may not function properly.

## Third-party disclosures
**We do not sell, trade, or otherwise transfer your personally identifiable information to outside parties for profit or advertising. _Ever_.**

This does not include application stack hosting partners and other parties who assist us in operating our service and serving our users, so long as those parties agree to keep this information confidential and are shown to operate the services consistent with the principle that privacy is a human right. As a result, we are extremely selective about the services we choose to integrate with.

We may also release information when it's release is appropriate to comply with the law or court order, enforce our service policies, or protect ours or others' civil and/or legal rights, property or safety.

We currently work with the following 3rd party services to provide this service:

- Amazon - for file storage via Amazon S3. Any files you upload to our service are stored here and are identified by an identifier unique to the file (not your account) within the S3 service.
- Stripe - for payment processing. The email account used to originally sign up for our service is disclosed along with any payment card information required to legally process payments. We do not store credit card information within the BendroCorp service. For one time donations Stripe stores your information long enough to effectuate the transaction. In the case of Supporter Program subscriptions, Stripe will maintain your personal and credit card information as long as the subscription is active.
- Digital Ocean - our primary cloud hosting provider where our data resides. While we don't technically share your data with them this is where it lives.
- Discord - we use Discord as our primary communications platform. You have to have a seperate account for Discord. We do share some information back and forth between the Discord platform and BendroCorp like email addresses, guild message contents and other contents from the BendroCorp API.

Non-personally identifiable visitor information may be provided to other parties for marketing, advertising, or other uses.

## Discord Integration
As outlined above, BendroCorp integrates with Discord as our primary communications platform. As a result, members must integrate their Discord account with the BendroCorp application stack with limited a limited set of permissions/scopes. The below scopes represent the totality of access that BendroCorp has to a user's Discord account. Below is the explanation of how each of those scopes/permissions are used and their limitations:

- Email - "Access your email address" - the second most essential piece. This provides the literal email string that is associated with your Discord account (ie. john.doe@gmail.com). This does **not** provide access to your *actual* email messages (Discord can't access that either). We use this information from Discord for a one time lookup in our database to locate your user account. To link your account to BendroCorp the email provided by Discord must match the email address on your account.
- Identity - "Access your username and avatar". The most essential piece of information. Provides access to essential user information including Discord ID, username and avatar. This does **not** provide access to any private/direct messages or any other personal data.

Futhermore the "bot" visible in Discord as "Kaden" and referred to furthermore as "Kaden" has access to any and all data visible within any part of the Discord BendroCorp server/guild instance which includes but is not limited to:

- All chat messages
- Voice presence
- Security Groups
- User data

## Third-party links
Occasionally, at our discretion, we may include or offer third-party products or services on our website. These third-party sites have separate and independent privacy policies. We therefore have no responsibility or liability for the content and activities of these linked sites. Nonetheless, we seek to protect the integrity of our site and welcome any feedback about these sites.

CalOPPA is the first state law in the nation to require commercial websites and online services to post a privacy policy. The law's reach stretches well beyond California to require any person or company in the United States (and conceivably the world) that operates websites collecting Personally Identifiable Information from California consumers to post a conspicuous privacy policy on its website stating exactly the information being collected and those individuals or companies with whom it is being shared. - See more at: http://consumercal.org/california-online-privacy-protection-act-caloppa/#sthash.0FdRbT51.dpuf

## California Online Privacy Protection Act
According to CalOPPA, we agree to the following:

- Users can visit our site anonymously.
- Once this privacy policy is created, we will add a link to it on our home page or as a minimum, on the first significant page after entering our website.
- Our Privacy Policy link includes the word 'Privacy' and can easily be found on the page specified above.

You will be notified of any Privacy Policy changes:
- On our Privacy Policy Page

Can change your personal information:
- By logging in to your account

## Do Not Track
We honor Do Not Track signals and Do Not Track, plant cookies, or use advertising when a Do Not Track (DNT) browser mechanism is in place. Using such mechanisms may, however, strongly impede your ability to use our service.

## Does our site allow third-party behavioral tracking?
We do not use or allow third-party behavioral tracking.

## COPPA (Children Online Privacy Protection Act)
When it comes to the collection of personal information from children under the age of 13 years old, the Children's Online Privacy Protection Act (COPPA) puts parents in control. The Federal Trade Commission, United States' consumer protection agency, enforces the COPPA Rule, which spells out what operators of websites and online services must do to protect children's privacy and safety online.

### COPPA Disclosures
We do not specifically market to children under the age of 13 years old. We do not allow those under the age of 16 years of age to create accounts within our service.
Fair Information Practices
The Fair Information Practices Principles form the backbone of privacy law in the United States and the concepts they include have played a significant role in the development of data protection laws around the globe. Understanding the Fair Information Practice Principles and how they should be implemented is critical to comply with the various privacy laws that protect personal information.

In order to be in line with Fair Information Practices we will take the following responsive action, should a data breach occur:

- We will notify you via email within 7 business days of when we become aware of a data breach and are able to identify affected users.
- We also agree to the Individual Redress Principle which requires that individuals have the right to legally pursue enforceable rights against data collectors and processors who fail to adhere to the law. This principle requires not only that individuals have enforceable rights against data users, but also that individuals have recourse to courts or government agencies to investigate and/or prosecute non-compliance by data processors.

## CAN-SPAM Act
The CAN-SPAM Act is a law that sets the rules for commercial email, establishes requirements for commercial messages, gives recipients the right to have emails stopped from being sent to them, and spells out tough penalties for violations.

To be in accordance with CANSPAM, we agree to the following:

- Not use false or misleading subjects or email addresses.
- Identify the message as an advertisement in some reasonable way.
- Include the physical address of our business or site headquarters.
- Monitor third-party email marketing services for compliance, if one is used.
- Honor opt-out/unsubscribe requests quickly.
- Allow users to unsubscribe by using the link at the bottom of each email.

## Contacting Us
If there are any questions regarding this privacy policy, you may contact us via support (at) bendrocorp.com
