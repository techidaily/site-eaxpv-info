---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2024-10-22T20:55:24.134Z
updated: 2024-10-27T17:57:04.717Z
tags:
  - apple
categories:
  - tech
thumbnail: https://thmb.techidaily.com/830a114fa27984f8d212144f3dee11f785f5b8b667c623d0ec997b65a2b06877.jpg
---

## Flexible Connection Setup on macOS with Multiple Network Locations - Tips

![MacOS Ventura](https://www.zdnet.com/a/img/resize/f9b803b11abf24ef89a80e3eab2b456c1d35293a/2022/07/11/47775a46-83d9-4a0e-a1e0-bac36bb3c798/macos-ventura-apple-hero.jpg?auto=webp&width=1280)

Apple

I connect to a lot of different networks. At home, I have three different LANs to choose from, which I use depending on my needs. For example, I have a general-purpose network and one that I use for the deployment of containers and the like. 

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037350/7443" target="_top" id="2037350">
  <img src="//a.impactradius-go.com/display-ad/7443-2037350" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037350/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137380/7443" target="_top" id="2137380">
  <img src="//a.impactradius-go.com/display-ad/7443-2137380" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137380/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111995/7443" target="_top" id="2111995">
  <img src="//a.impactradius-go.com/display-ad/7443-2111995" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111995/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528688/16446" target="_top" id="1528688">
  <img src="//a.impactradius-go.com/display-ad/16446-1528688" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528688/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

## Switching to a different Network Location

After you've created all of the network locations you need, MacOS makes it very easy to switch between them. All you have to do is click the Apple menu > Location > \[Location name\] (select the name of the location you want to use).

Switching between network locations is a few mouse clicks away.

Image: Jack Wallen

And that's all there is to creating and using network locations in MacOS. If you need to get specific with how your MacOS device interacts with a network, this is a great way to go. Just remember, however, if you move from the current location, you'll want to select another. For example, if you have [one location for home and one for work](https://www.zdnet.com/article/hybrid-workers-dont-want-to-return-to-the-office-but-soon-they-might-have-to/), your machine might have trouble connecting to that work LAN with the home settings.

  
Fortunately, you are now empowered to more easily make that switch.

#### Jack Wallen: Here's how to...

[How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")

[The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")

[Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")

[Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

* [How to get true window snapping in MacOS](https://www.zdnet.com/article/how-to-get-true-window-snapping-in-macos/ "How to get true window snapping in MacOS")
* [The AGM 5 Pro might be the loudest Android phone ever](https://www.zdnet.com/article/the-agm-5-pro-might-be-the-loudest-android-phone-ever/ "The AGM 5 Pro might be the loudest Android phone ever")
* [Nitrux 2.4 Linux distro shows promise](https://www.zdnet.com/article/nitrux-2-4-linux-distribution-shows-promise-but-seems-rough-around-the-edges/ "Nitrux 2.4 Linux distro shows promise")
* [Tired of being tracked online? DuckDuckGo's Email Protection can help](https://www.zdnet.com/article/tired-of-being-tracked-online-duckduckgos-email-protection-can-help/ "Tired of being tracked online? DuckDuckGo's Email Protection can help")

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-unveiling-the-secrets-to-slow-motion-screenshots-in-snapchat/"><u>[New] 2024 Approved Unveiling the Secrets to Slow-Motion Screenshots in Snapchat</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-get-started-signing-up-for-a-youtube-channel/"><u>[Updated] How to Get Started Signing Up for a YouTube Channel</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-surging-channel-growth-with-optimal-video-hashes/"><u>[Updated] In 2024, Surging Channel Growth with Optimal Video Hashes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-convert-any-instagram-video-in-minutes-best-free-tools-windowsmac/"><u>2024 Approved Convert Any Instagram Video in Minutes Best Free Tools (Windows/Mac)</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-huawei-nova-y91-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Huawei Nova Y91 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/create-a-reliable-dvd-backup-transferring-to-iso-format-using-winx-dvd-copy/"><u>Create a Reliable DVD Backup: Transferring to ISO Format Using WinX DVD Copy</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/decoupeuses-mkv-de-haut-niveau-trier-les-fichiers-mkv-sans-recode/"><u>Découpeuses MKV De Haut Niveau : Trier Les Fichiers MKV Sans Recode</u></a></li>
<li><a href="https://win-able.techidaily.com/defeating-launch-hurdles-in-lost-ark-expert-advice-for-gamers/"><u>Defeating Launch Hurdles in Lost Ark: Expert Advice for Gamers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/dvd-memory/"><u>DVD Memory レビューとユーザーフィードバック：全面的なインサイト、利点、欠点および使用法</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ipaddvd3/"><u>IPad上のDVD再生のコツ：使いやすいテクニック3つをご紹介</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/la-meilleure-application-de-capture-decran-pour-les-utilisateurs-de-windows-prise-en-charge-des-versions-10-8-et-7/"><u>La Meilleure Application De Capture D'écran Pour Les Utilisateurs De Windows : Prise en Charge Des Versions 10, 8 Et 7.</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/professional-videographers-guide-to-efficient-color-keying-for-2024/"><u>Professional Videographer's Guide to Efficient Color-Keying for 2024</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/quick-and-simple-methods-for-reducing-video-size-on-twitter-pc-online-tools-or-applications/"><u>Quick & Simple Methods for Reducing Video Size on Twitter: PC, Online Tools or Applications</u></a></li>
<li><a href="https://win-howtos.techidaily.com/spacebar-key-stuck-or-unresponsive-in-windows-11-heres-what-to-do/"><u>Spacebar Key Stuck or Unresponsive in Windows 11? Here's What to Do!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ultimate-guide-to-winx-mediatrans-pro-top-app-for-seamless-iphone-and-ipad-data-syncing-with-computer/"><u>Ultimate Guide to WinX MediaTrans Pro: Top App for Seamless iPhone & iPad Data Syncing with Computer</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/vergleich-von-aac-und-mp3-welche-audioqualitat-uberzeugt-mehr/"><u>Vergleich Von AAC Und MP3: Welche Audioqualität Überzeugt Mehr?</u></a></li>
</ul></div>

