---
title: macOS Calendar sync annoyances
slug: 
description: 
date: "2024-05-23T00:00:00Z"
image: exchange.png
categories:
    - Daily Post
    - Apple
    - Microsoft
---
Came across this annoying bug with Calendar sync on macOS today. I use the excellent utility [Dato](https://apps.apple.com/gb/app/dato/id1470584107?mt=12) on my MacBook to ensure I don't miss any meetings, but this afternoon I noticed a meeting in my Outlook calendar that wasn't appearing in Dato.

At first I assumed this was a repeat of an occasional issue I have run into where my Exchange calendar just decides to stop syncing with my Calendar so I went through the normal "fix" of removing my Exchange account from Settings/Accounts and re-adding it. The trouble is this didn't fix the issue, the missing appointment was still missing.

The difference with this appointment though was that it was booked into my calendar using the Microsoft Bookings app. This it seems is the issue. After a bunch of digging I came across [this entry on Microsoft Feedback](https://feedbackportal.microsoft.com/feedback/idea/e085dfaf-d5f4-ed11-a81c-000d3a7a48db) which explains that the issue is with Bookings entries not syncing correct with EWS (Exchange Web Services) which is the older mechanism for calendar sync still used by macOS. Apparently this issue only affects macOS and not iOS (the missing entry appears correctly in the Calendar app on my iPhone)

I have added my vote on Microsoft Feedback for this to be resolved for what its worth, though I do wonder if the better solution would be for Apple to upgrade Calendar sync in macOS to use Exchange ActiveSync (EAS) which works correctly on iOS ?

## Daily Links

|Link|Description|
|--------|----|
|[Microsoft Feedback](https://feedbackportal.microsoft.com/feedback/idea/e085dfaf-d5f4-ed11-a81c-000d3a7a48db)|Events booked with Bookings need to show up in Calendar.app on macOS|
