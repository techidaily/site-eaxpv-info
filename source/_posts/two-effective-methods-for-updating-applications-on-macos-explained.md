---
title: Two Effective Methods for Updating Applications on macOS Explained
date: 2024-12-19T16:02:57.320Z
updated: 2024-12-22T18:35:09.324Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a68c5c5018f608284d7af133f2911830741f898253edd18111f294ce2b839027.jpg
---

## Two Effective Methods for Updating Applications on macOS Explained

![fullscreen-1-4-24-7-23pm](https://www.zdnet.com/a/img/resize/4d0754ca50eca284946b9049b2a02512354bb4c1/2024/01/05/f413ba01-74e1-4edb-8d1e-41b8aa539d45/fullscreen-1-4-24-7-23pm.jpg?auto=webp&width=1280)

Screen Sharing on MacOS Sonoma

Jason Perlow/ZDNET

Any time I see updates available for my MacOS machines, I immediately apply them. Why? Because those updates often contain security patches that keep my computers safe. Those updates might also contain new features for apps or performance and reliability improvements. Either way, I find these updates to be an essential part of [maintaining the security of my devices](https://www.zdnet.com/article/how-to-update-every-apple-device/) and keeping my mind at ease.

**Also: [How I purged over 175GB of files from my Mac in under a minute (and you can too)](https://www.zdnet.com/article/how-i-purged-over-175gb-of-files-from-my-mac-in-under-a-minute/)**

When I go to update a MacOS device, I know there's more than one way to approach the task -- from the App Store (via the MacOS GUI) or from the command line. Because I've spent decades [working with Linux](https://www.zdnet.com/article/thinking-about-switching-to-linux-things-you-need-to-know/), I'm 100% comfortable using the command line, so I will sometimes open the terminal app, check for upgrades, and then run them when they're available. Or, if I'm feeling a bit lazy, I'll just go the App Store route.

Let me show you both approaches.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## How to update MacOS apps from the App Store

**What you'll need:** The only things you'll need are an Apple device (a MacBook or iMac) and a valid user account on the machine. That's it. Let's get to the updates.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/C3cJe7Wgn6I?si=EckDFML-VJ_2sYz8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open the App Store

The fastest way to check and see if there are any updates available is by clicking the Apple button in the upper-left corner, where you might see something like _2 updates_ listed (indicating you have two apps that have updates available). Click that entry to open the App Store.

I have two available updates on my MacBook Pro.

Screenshot by Jack Wallen/ZDNET

#### Newsletters

ZDNET Tech Today

ZDNET's Tech Today newsletter is a daily briefing of the newest, most talked about stories, five days a week.

 Subscribe

[See all](https://www.zdnet.com/newsletters/)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3AGmFrtBLHw?si=VhvpUaXHPBHl6OT6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Update your apps

When the App Store opens, you can either update the apps individually (by clicking the Update button associated with the app in question) or update them all at once (by clicking Update All). During the update process, you might be prompted to close an app (or even a related app) if it's blocking the update from continuing. Should that be the case, close the app in question, return to the App Store, and click Continue from the pop-up warning.

These two apps on my MacBook Pro have pending updates.

Screenshot by Jack Wallen/ZDNET

Once the update is completed, close the App Store and you're done.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0pSRlspzW-A?si=A82G3Yxwj_31cKDq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Update the apps

Let's say the command lists that Apple Mail has an update available, which should be listed as _Mail_ (remember, case sensitivity). Before you update the app, make sure to close it first. Once closed, update the app with a command like this:

sudo softwareupdate -i Mail

After successfully typing your sudo password, the update will proceed. When the update completes, you may or may not have to restart the machine. (You will be informed if a reboot is necessary.) You can then re-open the app you just updated and enjoy whatever fresh features or security patches the update applied.

**Also: [The Apple products you shouldn't buy this month](https://www.zdnet.com/article/the-apple-products-you-shouldnt-buy-this-month/)** 

This is about as simple a method as you'll find to help keep your MacOS machines running smoothly and securely. Never leave an app update lingering because it often contains security patches, which are required for the health and well-being of your operating system.

#### Apple

[iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")

[My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")

[We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")

[6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

* [iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get](https://www.zdnet.com/article/iphone-16-pro-and-pro-max-hands-on/ "iPhone 16 Pro upgrade: If you have a 3 year-old iPhone, here are all the new features you'll get")
* [My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)](https://www.zdnet.com/article/my-biggest-regret-with-upgrading-my-iphone-to-ios-18-and-im-not-alone/ "My biggest regret with upgrading my iPhone to iOS 18 (and I'm not alone)")
* [We've used every iPhone 16 model and here's our best buying advice for 2024](https://www.zdnet.com/article/iphone-16-pro-max-buying-advice-2024/ "We've used every iPhone 16 model and here's our best buying advice for 2024")
* [6 iOS 18 settings I changed immediately - and why you should too](https://www.zdnet.com/article/6-ios-18-settings-i-changed-immediately-and-why-you-should-too/ "6 iOS 18 settings I changed immediately - and why you should too")

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://eaxpv-info.techidaily.com/new-building-your-asmr-empire-key-concepts-and-best-practices-for-2024/"><u>[New] Building Your ASMR Empire Key Concepts and Best Practices for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-dissecting-youtube-copyright-vs-creative-commons-ethos-for-2024/"><u>[New] Dissecting YouTube Copyright Vs. Creative Commons Ethos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-elevating-audience-excitement-with-top-ideas/"><u>[New] In 2024, Elevating Audience Excitement with Top Ideas</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-mastering-timeliness-using-current-events-to-your-advantage/"><u>[New] Mastering Timeliness Using Current Events to Your Advantage</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-maximize-engagement-the-ultimate-list-of-youtube-growth-tactics/"><u>[New] Maximize Engagement The Ultimate List of YouTube Growth Tactics</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-youtube-for-educators-maximizing-its-classroom-potential/"><u>[New] YouTube for Educators Maximizing Its Classroom Potential</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-boost-your-channel-game-essential-video-editing-advice/"><u>[Updated] 2024 Approved Boost Your Channel Game Essential Video Editing Advice</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-amplify-your-channel-effortless-tactics-for-more-views-for-2024/"><u>[Updated] Amplify Your Channel Effortless Tactics for More Views for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-beam-it-up-15-must-haves-for-your-youtube-live-stream-for-2024/"><u>[Updated] Beam It Up! 15 Must-Haves for Your YouTube Live Stream for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-expert-pick-mics-for-youtube-entrepreneurs-for-2024/"><u>[Updated] Expert Pick Mics for YouTube Entrepreneurs for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-in-2024-unveiling-the-top-rated-srt-translators-for-zero-cost/"><u>[Updated] In 2024, Unveiling the Top-Rated SRT Translators for Zero Cost</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-record-your-mac-in-hd-no-fee/"><u>[Updated] Record Your Mac in HD No Fee</u></a></li>
<li><a href="https://article-files.techidaily.com/exclusive-top-8-gear-in-the-vr-sphere/"><u>Exclusive Top 8 Gear in the VR Sphere</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-tecno-spark-10-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Tecno Spark 10 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-a-new-dimension-understanding-the-innovations-in-hp-envy-27-monitor/"><u>In 2024, A New Dimension Understanding the Innovations in HP Envy 27 Monitor</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-crafting-a-scintillating-trailer-tale/"><u>In 2024, Crafting A Scintillating Trailer Tale</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-top-picks-hd-cameras-under-100-for-extreme-sports/"><u>In 2024, Top Picks HD Cameras Under $100 for Extreme Sports</u></a></li>
<li><a href="https://win-forum.techidaily.com/the-ultimate-walkthrough-to-a-clean-windows-11-setup-beginner-friendly/"><u>The Ultimate Walkthrough to a Clean Windows 11 Setup - Beginner Friendly</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/top-80s-filters-and-effects-for-professional-videos/"><u>Top 80S Filters & Effects for Professional Videos</u></a></li>
</ul></div>

