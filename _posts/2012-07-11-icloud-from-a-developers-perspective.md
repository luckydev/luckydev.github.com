---
layout: post
title: iCloud, from a Developer's perspective
date: '2012-07-11T00:30:00+05:30'
tags: []
comments: true
---
From SJ keynotes, people think that iCloud is just a sync service for their contacts/music/pictures/videos. But It doesn’t stop there. Many don’t know that it is also available for third party developers.

So any app on iOS can utilize iCloud API and sync its data across all devices (iPod, iPhone, iPad and Mac). And users can access the same data on all their devices. Mountain Lion is coming this month and it takes iCloud integration much more seriously. 

iCloud is a win-win for both consumers and developers. Consumers get such a rich deeply integrated sync and backup solution without much trouble. And Developers get a rich synchronization backend for free! 

Many super smart developers would think that they can develop their own synchronization backend and use it in all their apps. Well, not of all us have that much time/money to do it. If I can use iCloud, develop the app and start to see sales in 60 days from now, why would I ever choose to build my own synchronization platform? And If I create my own synchronization platform, I need to maintain the servers and their uptime. But Apple takes care of all of them for me in iCloud. 

When I develop an app, I know for sure that iOS users would have configured their iCloud account during the device setup and I can just blindly use the API to sync my app’s data with it. If they turn Off iCloud sync by any chance or if they have not configured the account at all, the API just takes care of it all. I, as a developer don’t need to handle all of this configuration and edge cases headache. This goes the same for both Twitter and Facebook integration in recent iOS versions.

Well, some might argue that they could use Dropbox API and do the same. I then need to take care of configuration details of the service etc., inside my app which is not easy at all. Also when a person buys a new iOS device and during the setup if he brings down all of his iCloud backup to the device, I know for sure that my app’s data will also come in. I can’t get this in any other third party sync platform. And to use my app, I need to put explicitly a dependency for the user to be on Dropbox. 

Google Drive seems to look like one more alternative. But I have to test it before I can write more comments on it. 
