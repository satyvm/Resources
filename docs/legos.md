---
title : "Legos"
description: "A Curated list of Legos"
lead: ""
date: 2023-01-30T22:02:49+05:30
lastmod: 2023-01-30T22:02:49+05:30
draft: true
images: []
---

### Project Categories

The categories below are simplistic and imperfect and will improve with input.  Please make suggestions.  
You can read more about how to suggest & make changes in our **[wiki.](https://github.com/OpenDataforWeb3/Resources/wiki)**

**We peridocially run bounties & hackathons that reward issues & pull requests; so your improvements may resulted in a reward!**

## List of Legos

### Gitcoin Passport
- [Website](https://go.gitcoin.co/passport)
- [Github](https://github.com/gitcoinco/passport)
- Summary: *When a user connects a passport, a trust score can be calculated for them which is used as evidence of personhood - the greater the score the more likely they are to be a genuine user.*


**Shared IP:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_visitsIP.R)
- Summary: *User IP addresses can also be checked to see if they are shared with many other users. Lots of addresses originating from the same IP could be a marker for Sybil attackers.*

**SAD Model:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_SAD.R)
- Summary: *The user also has a Gitcoin account whose history can be analyzed using the SAD model to give another Sybil-likelihood score.*

**DonorDNA:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_DNA.R)
- Summary: *When a donor connects their wallet their profile of past donations can be analyzed to see whether it is similar to groups of other users, which may be indicatative of Sybil rings.*

**GrantDNA:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_DNA.R)
- Summary: *Each grant has a set of donors that can be represented as a set of binary data. This can be used to compare grants against flagged grants to see if they have similar donor profiles.*

**Onchain Intersectionality:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_intersectionality.R)
- Summary: *It checks "How many out of a set of on-chain credentials does a user have?"*

**Levenstein distance:**
- [Github](https://github.com/Fraud-Detection-and-Defense/Gitcoin-Sybil-LEGOs/blob/main/scripts_process/process_levenshtein.R)
- Summary: *Every user has a username - when they sign up to Gitcoin grants the similarity of their name can be compared against all other usernames to generate a likelihood of the username being auto-generated - evidence of a Sybil account. This Lego will be deprecated in the grants protocol because usernames will no longer be available - only Ethereum addresses, wallet IDs and grant/round nonce.*
