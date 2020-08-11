---
title: Accessing staging
description: How to access the staging environment
published: true
date: 2020-08-11T01:38:44.324Z
tags: 
editor: undefined
---

# Accessing Staging
# Instructions for how to access VA.gov in Staging:

Go to https://staging.va.gov/. 

- From any page, in the top right corner click "Sign In".  
- Select ID.me to sign in, and enter the username and the password desired and click Sign in. The username will be of the format "vets.gov.user+XXX@gmail.com" (where XXX will change depending on the product) and the password will always be "Zm9ydHkgdHdv" in staging. 
- You will then be prompted to "enable 2FA". 
	- Click "Phone"
	- On the next screen you'll see a phone number, don't worry that you don't have access to that phone number, on staging, you don't actually have to enter this code. 
	- Click Continue
	- On the next screen you will see the code already entered. Click Continue again. 
- The popup should now close and you're logged in. 

A full list of staging test users is in [mvi-staging-users.csv](https://github.com/department-of-veterans-affairs/va.gov-team-sensitive/blob/master/Administrative/vagov-users/mvi-staging-users.csv), but not all test users exist in all VA backend test environments, so see below for which users to log in with for specific vets.gov features.

# Distribution

These credentials are considered "sensitive" but not "classified" by the team, and can be provided to small sets of trusted external users on a need to know basis. There is no guarantee of availability or accuracy. If significant load will be generated, or testing goes beyond confirming basic functionality, please reach out to the #vetsgov-engineers channel to work through options.

# Content
You do not need to log in to read any of our content besides what is specifically on the pages in the tools below.  Read away and especially check out the various ways to navigate the content!

# Forms
You do not _need_ to log in use most forms. But if you do, your progress will be saved along the way. Signing in will also prefill forms with data we can pull from the account profile. 526 (Disability Comp) **requires** sign-in because it needs to pull PII and PHI from VA sources to be successfully submitted. 

# Health Tools

To test Prescription Refills, Secure Messaging, and Blue Button, log in as user vets.gov.user+264@gmail.com. 

- Access Prescriptions at: https://staging.vets.gov/health-care/prescriptions (please don't actually click to confirm any refills, as we only have a limited number of those and have to request more from MHV every time we run out). 
- Access Secure Messaging at: https://staging.vets.gov/health-care/messaging
- Access Blue Button at: https://staging.vets.gov/health-care/health-records (Note, in staging because of the data setup we have, it will never automatically move off the "updating your records" page and you'll need to manually click "get an older version of your records" to get to the next page). 

# Claims and Appeals Status
Claims and appeals status are together in one product. To view this, log in as user vets.gov.user+226@gmail.com and visit https://staging.vets.gov/track-claims. 

Additionally, users 300 - 314 all have appeals in various statuses, so feel free to log in as any of those users to see what appeals in other statuses look like (but those users don't have any claims). (Update- as of 12/20/2019, none of these users have appeals either)

# Post 9/11 GI Bill Status and VA Letters
To view these two products, you can log in as user vets.gov.user+299@gmail.com. 

- Access Post 9/11 GI Bill Status: https://staging.vets.gov/education/gi-bill/post-9-11/ch-33-benefit
- Access VA Letters at: https://staging.vets.gov/letters

As more products are added, please add them here. 