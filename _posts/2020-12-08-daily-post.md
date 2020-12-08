---
layout: single
published: true
title: Daily Post - 08/12/2020
tags:
  - Microsoft
  - Office 365
  - Daily Post
categories:
  - Microsoft
---
## Email Pains

Today has been a painful day trying to resolve an issue with Mail rules in Exchange Online. Yesterday I switched on a Malware Policy to block certain files types after reading [this article.](https://regarding365.com/a-little-bit-more-security-fb6825ef8435?source=rss----604cd9a532f6---4) All seemed fine but then first thing this morning I received a number of calls from users unable to email Helpdesk calls to our Helpdesk system ([Freshdesk](https://www.freshdesk.com)). It seems as though the change I made yesterday had triggered a mail rule setup to block users autoforwarding emails externally into action that must not have been working before.

Unfortunately trying to fix mail rules in Exchange is made more difficult due to the very long time it takes for changes made to become operational. According to [Lance Cal in this Microsoft Community thread](https://answers.microsoft.com/en-us/msoffice/forum/msoffice_o365admin-mso_exchon-mso_o365b/dlp-and-mail-transport-rules-in-eac/75486160-ee0e-4cc2-a9cb-a9311630cf83) changes can take up to 12 hours to become active. Thats a whole working day before I can see if the change I made to fix our issue works and during which time our IT Helpdesk that relies on email autoforward rules to operate remains unusable.

