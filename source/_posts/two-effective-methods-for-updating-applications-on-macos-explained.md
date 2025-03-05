---
title: Two Effective Methods for Updating Applications on macOS Explained
date: 2025-02-27T23:05:47.201Z
updated: 2025-03-05T16:53:34.654Z
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

## How to update MacOS apps from the command line

This is a bit more complicated, for two reasons: first, you have to find out what apps are available for updating, and, second -- as with Linux -- the app names are case-sensitive.

## 1\. Open the Terminal app

To run commands, you must first open the terminal app, which can be done from the Launchpad. Click the Launchpad icon in your Dock and then type _terminal_. Click the launcher to open the Terminal app.

## 2\. Check for available updates

Next, you need to run the command to check for updates. The command in question is _softwareupdate_ and is used for both checking and running the updates. To check for available updates, issue the command:

sudo softwareupdate -l

You will be prompted for your sudo password (which is your MacOS user password). 

**Also: [How to update every Apple device (iPhone, iPad, Apple Watch, Mac, more)](https://www.zdnet.com/article/how-to-update-every-apple-device/)**

The -l option stands for _list_. This will print out any available app updates and, if required, it will inform you if a restart is needed to complete any recent OS updates. If you see such a warning, make sure to do the reboot to complete the process.

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
<li><a href="https://article-tips.techidaily.com/new-explore-sj7s-high-definition-action-footage-in-new-review/"><u>[New] Explore SJ7's High-Definition Action Footage in New Review</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-mobile-mastery-an-exhaustive-look-at-androids-lightroom-for-2024/"><u>[New] Mobile Mastery An Exhaustive Look at Android’s Lightroom for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-dslrs-rivalry-with-mirrorless-for-video-artistry-for-2024/"><u>[Updated] DSLR's Rivalry with Mirrorless for Video Artistry for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-laughmaker-quick-meme-and-image-crafter/"><u>[Updated] LaughMaker Quick Meme & Image Crafter</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ai-revolutionized-communication-how-siri-is-now-apples-primary-search-engine-inspired-by-bing-insights-for-tomorrow/"><u>AI Revolutionized Communication: How Siri Is Now Apple's Primary Search Engine, Inspired by Bing | Insights for Tomorrow</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/apple-discontinues-new-ios-beta-following-iphone-malfunction-incidents-insights-from-zdnet/"><u>Apple Discontinues New iOS Beta Following iPhone Malfunction Incidents – Insights From ZDNet</u></a></li>
<li><a href="https://win11.techidaily.com/avoiding-failure-starting-services-on-windows-efficiently/"><u>Avoiding Failure: Starting Services on Windows Efficiently</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/comprehensive-guide-to-leading-compact-tablets-of-2nplusd-endorsed-by-industry-experts-zdnet/"><u>Comprehensive Guide to Leading Compact Tablets of 2N+d, Endorsed by Industry Experts | ZDNET</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/disabled-iphone-13-pro-max-how-to-unlock-a-disabled-iphone-13-pro-max-drfone-by-drfone-ios/"><u>Disabled iPhone 13 Pro Max How to Unlock a Disabled iPhone 13 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-realme-11x-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Realme 11X 5G | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/latest-and-greatest-mp3-audio-gadgets-featured/"><u>Latest and Greatest MP3 Audio Gadgets - Featured</u></a></li>
<li><a href="https://extra-information.techidaily.com/strategic-approaches-to-metaverse-promotion/"><u>Strategic Approaches to Metaverse Promotion</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-rated-iphone-16-and-16-pro-protectors-thoroughly-reviewed-by-tech-gurus/"><u>Top-Rated iPhone 16 & 16 Pro Protectors - Thoroughly Reviewed by Tech Gurus</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1727792522252-top-rated-smartwatches-comprehensive-analysis-by-tech-experts-zdnet/"><u>Top-Rated Smartwatches : Comprehensive Analysis by Tech Experts | ZDNet</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-guide-to-the-finest-airtag-wallets-of-2024-expert-opinions/"><u>Ultimate Guide to the Finest AirTag Wallets of 2024: Expert Opinions</u></a></li>
</ul></div>

