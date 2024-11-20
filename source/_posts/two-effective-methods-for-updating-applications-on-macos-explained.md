---
title: Two Effective Methods for Updating Applications on macOS Explained
date: 2024-11-17T23:51:07.803Z
updated: 2024-11-19T19:10:36.790Z
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
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036501/19272" target="_top" id="2036501">
  <img src="//a.impactradius-go.com/display-ad/19272-2036501" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036501/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105873/7443" target="_top" id="2105873">
  <img src="//a.impactradius-go.com/display-ad/7443-2105873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137210/26400" target="_top" id="2137210">
  <img src="//a.impactradius-go.com/display-ad/26400-2137210" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137210/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-2-ways-to-increase-your-youtube-audience-fast/"><u>[New] 2024 Approved 2 Ways to Increase Your YouTube Audience Fast</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/asy-paths-to-profitable-youtube-business-channels-top-10-list-in-2024/"><u>[New] Easy Paths to Profitable YouTube Business Channels, Top 10 List, In 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-game-changing-streaming-apps-for-gamers-for-2024/"><u>[New] Game-Changing Streaming Apps for Gamers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-much-can-you-earn-on-youtube-via-ad-revenue-for-2024/"><u>[New] How Much Can You Earn on YouTube via Ad Revenue for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-use-google-trends-to-come-up-with-video-ideas-easy-guide-for-2024/"><u>[New] How to Use Google Trends to Come up with Video Ideas [Easy Guide] for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-device-capture-to-viral-content-youtubes-upload-guide/"><u>[Updated] 2024 Approved From Device Capture to Viral Content YouTube's Upload Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1717717687675-updated-2024-approved-how-to-make-collab-videos-and-grow-your-channel/"><u>[Updated] 2024 Approved How to Make Collab Videos And Grow Your Channel?</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-channel-success-metrics-subscriber-and-play-buttons/"><u>[Updated] Channel Success Metrics Subscriber & Play Buttons</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-flaunt-your-brand-with-ease-the-top-10-youtube-theme-designers-for-2024/"><u>[Updated] Flaunt Your Brand with Ease - The Top 10 YouTube Theme Designers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-add-timestamps-on-youtube-video-link-in-2024/"><u>[Updated] How to Add Timestamps on YouTube Video Link, In 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-captivate-audience-attention-with-your-yt-shorts-for-2024/"><u>[Updated] How to Captivate Audience Attention with Your YT Shorts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-launch-your-first-sporty-video-channel-on-apple-systems-for-2024/"><u>[Updated] How to Launch Your First Sporty Video Channel on Apple Systems for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-reasons-for-unexpected-cut-off-in-imovie/"><u>[Updated] In 2024, Reasons for Unexpected Cut-Off in iMovie</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-fostering-relationships-not-just-viewers-a-guide-to-subscriptions/"><u>2024 Approved Fostering Relationships, Not Just Viewers A Guide to Subscriptions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-streamers-toolkit-beyond-streamlabs-obs/"><u>2024 Approved Streamer's Toolkit Beyond Streamlabs OBS</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-cast-nokia-c32-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>How to Cast Nokia C32 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/in-2024-identifying-the-perfect-hashtag-for-your-tiktok-profile/"><u>In 2024, Identifying the Perfect Hashtag for Your TikTok Profile</u></a></li>
<li><a href="https://technical-tips.techidaily.com/meta-unveils-pro-style-vr-gadget-incorporating-apples-infamous-capabilities-zdnet-insights/"><u>Meta Unveils Pro-Style VR Gadget, Incorporating Apple's Infamous Capabilities | ZDNet Insights</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-asus-rog-phone-8-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Asus ROG Phone 8 Users</u></a></li>
</ul></div>

