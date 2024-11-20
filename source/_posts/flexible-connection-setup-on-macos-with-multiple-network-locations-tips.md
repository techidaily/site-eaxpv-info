---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2024-11-15T23:06:17.893Z
updated: 2024-11-20T00:45:47.613Z
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
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135356/19272" target="_top" id="2135356">
  <img src="//a.impactradius-go.com/display-ad/19272-2135356" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135356/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-entering-the-fullscreen-realm-choosing-a-cms/"><u>[New] 2024 Approved Entering the Fullscreen Realm Choosing a CMS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-elevate-your-presence-the-best-5-practices-for-max-viewers/"><u>[New] In 2024, Elevate Your Presence The Best 5 Practices for Max Viewers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-ideation-to-implementation-a-comprehensive-approach-for-quality-edu-videos/"><u>[New] In 2024, From Ideation to Implementation A Comprehensive Approach for Quality Edu-Videos</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-ideal-mac-screenshot-guide-5-streamlined-and-effective-methods/"><u>[New] In 2024, Ideal Mac Screenshot Guide 5 Streamlined and Effective Methods</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-step-by-step-guide-on-using-gaming-youtube-banner-templates/"><u>[New] In 2024, Step-By-Step Guide on Using Gaming YouTube Banner Templates</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-prime-mobile-hd-video-playback-androids-top-picks/"><u>[New] Prime Mobile HD Video Playback Android's Top Picks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-essential-knowledge-for-youtube-short-creators/"><u>[Updated] 2024 Approved Essential Knowledge for YouTube Short Creators</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-podcasts-vs-youtube-making-an-informed-media-decision/"><u>[Updated] 2024 Approved Podcasts Vs. YouTube Making an Informed Media Decision</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-6-completely-different-places-to-get-youtube-icons-and-logos/"><u>[Updated] 6 Completely Different Places to Get YouTube Icons and Logos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-igniting-success-the-youtubers-playbook/"><u>[Updated] Igniting Success The YouTuber's Playbook</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-lenssplit-viewer-insight-for-2024/"><u>[Updated] LensSplit Viewer Insight for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-the-eraser-guru-expert-tips-for-psx-users/"><u>[Updated] The Eraser Guru Expert Tips for PSX Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chrome-upgrade-for-easy-chatgpt-command-input-boost-productivity-now/"><u>Chrome Upgrade for Easy ChatGPT Command Input – Boost Productivity Now</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/crafting-engaging-video-teasers-for-youtube-success-for-2024/"><u>Crafting Engaging Video Teasers for YouTube Success for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/in-2024-find-rich-ambiance-for-video-content/"><u>In 2024, Find Rich Ambiance for Video Content!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/in-2024-youtubes-most-followed-fashionistas-and-cosmetic-experts/"><u>In 2024, YouTube's Most-Followed Fashionistas & Cosmetic Experts</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/pokemon-go-cooldown-chart-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>Pokémon Go Cooldown Chart On Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/reel-riches-understanding-metas-monetary-mechanisms-for-artists/"><u>Reel Riches: Understanding Meta’s Monetary Mechanisms for Artists</u></a></li>
<li><a href="https://techidaily.com/the-easiest-methods-to-hard-reset-samsung-galaxy-a14-5g-drfone-by-drfone-reset-android-reset-android/"><u>The Easiest Methods to Hard Reset Samsung Galaxy A14 5G | Dr.fone</u></a></li>
</ul></div>

