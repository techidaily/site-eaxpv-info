---
title: Two Effective Methods for Updating Applications on macOS Explained
date: 2024-10-09T00:28:30.414Z
updated: 2024-10-09T23:23:45.154Z
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
<a href="https://appsumo.8odi.net/c/5597632/2151882/7443" target="_top" id="2151882">
  <img src="//a.impactradius-go.com/display-ad/7443-2151882" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151882/7443" style="position:absolute;visibility:hidden;" border="0" />
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

## 2\. Update your apps

When the App Store opens, you can either update the apps individually (by clicking the Update button associated with the app in question) or update them all at once (by clicking Update All). During the update process, you might be prompted to close an app (or even a related app) if it's blocking the update from continuing. Should that be the case, close the app in question, return to the App Store, and click Continue from the pop-up warning.

These two apps on my MacBook Pro have pending updates.

Screenshot by Jack Wallen/ZDNET

Once the update is completed, close the App Store and you're done.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-3-steps-for-perfect-instagram-video-margins/"><u>[New] 2024 Approved 3 Steps for Perfect Instagram Video Margins</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-dodge-fb-disconnection-10-hidden-gems-to-keep-you-safe-for-2024/"><u>[New] Dodge Fb Disconnection 10 Hidden Gems to Keep You Safe for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ecure-extraction-of-audio-from-youtube-at-zero-cost/"><u>[New] Secure Extraction of Audio From YouTube at Zero Cost</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-honorable-warriors-reimagined-best-matching-gaming-titles-for-2024/"><u>[Updated] Honorable Warriors, Reimagined Best Matching Gaming Titles for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1-unlocking-the-secrets-todays-new-york-times-insights-and-answers-may-23rd-edition-nytimes-347/"><u>1. Unlocking the Secrets: Today's New York Times Insights & Answers, May 23Rd Edition (NYTimes #347)</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/2-digital-renewal-alert-5-critical-cues-you-need-a-new-email-address-now/"><u>2. Digital Renewal Alert: 5 Critical Cues You Need a New Email Address Now</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-rapid-fortnite-tile-making-hacks/"><u>2024 Approved Rapid Fortnite Tile-Making Hacks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/boost-your-facebook-usage-with-these-8-uncommon-yet-powerful-functions/"><u>Boost Your Facebook Usage with These 8 Uncommon Yet Powerful Functions!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/crack-the-puzzle-with-nyts-july-9th-connection-challenges-hint-session-394/"><u>Crack the Puzzle with NYT's July 9Th Connection Challenges (Hint Session #394)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/discovering-the-advantages-of-multi-angle-recording-for-2024/"><u>Discovering the Advantages of Multi-Angle Recording for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/secret-sound-scribes-hidden-audio-logging-for-mobile-devices/"><u>Secret Sound Scribes Hidden Audio Logging for Mobile Devices</u></a></li>
<li><a href="https://fox-links.techidaily.com/the-solitary-path-to-podcast-popularity/"><u>The Solitary Path to Podcast Popularity</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/value-for-money-an-in-depth-look-at-the-open-ear-wireless-earbuds-from-baseus-eli-sport-1-with-key-trade-offs-explored/"><u>Value for Money? An In-Depth Look at the Open-Ear Wireless Earbuds From Baseus Eli Sport 1 with Key Trade-Offs Explored</u></a></li>
</ul></div>

