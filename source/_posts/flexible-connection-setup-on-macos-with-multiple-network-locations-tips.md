---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2024-10-14T07:13:56.159Z
updated: 2024-10-16T08:41:47.474Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087409/7443" target="_top" id="2087409">
  <img src="//a.impactradius-go.com/display-ad/7443-2087409" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087409/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139120/17108" target="_top" id="2139120">
  <img src="//a.impactradius-go.com/display-ad/17108-2139120" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139120/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-gear-up-for-greatness-choosing-webcams-for-youtube-excellence/"><u>[New] 2024 Approved Gear Up for Greatness Choosing Webcams for YouTube Excellence</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-performance-gpu-picks-for-quality-video-streaming/"><u>[New] 2024 Approved High-Performance GPU Picks for Quality Video Streaming</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-make-profitable-youtube-ads-for-free-for-2024/"><u>[New] How To Make Profitable YouTube Ads for Free for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-go-viral-on-youtube-with-minimal-effort/"><u>[New] In 2024, How to Go Viral on YouTube with Minimal Effort</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-get-rid-of-youtube-ads-with-ease-on-chrome-firefox-ios-android/"><u>[Updated] 2024 Approved Get Rid of YouTube Ads with Ease on Chrome, Firefox, iOS, Android</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gain-an-edge-access-these-top-8-sites-for-free-eco-screen-backdrops-and-clips/"><u>[Updated] In 2024, Gain an Edge - Access These Top 8 Sites for FREE Eco-Screen Backdrops and Clips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gain-more-views-beginners-guide-to-youtube-seo/"><u>[Updated] In 2024, Gain More Views Beginner’s Guide to YouTube SEO</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-home-studio-heroics-your-path-to-effectful-artistry/"><u>[Updated] In 2024, Home Studio Heroics Your Path to Effectful Artistry</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-ideal-5-add-ons-to-enhance-sea-footage/"><u>[Updated] In 2024, Ideal 5 Add-Ons to Enhance Sea Footage</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-dji-fpv-revolution-a-review-of-eyewear-innovation/"><u>[Updated] The DJI FPV Revolution A Review of Eyewear Innovation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-turning-your-youtube-views-into-a-screen-capture-made-simple-and-free/"><u>[Updated] Turning Your YouTube Views Into a Screen Capture Made Simple and Free</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-tecno-spark-10-5g-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Tecno Spark 10 5G to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/high-quality-video-webcams-top-5-combos-with-sound-for-2024/"><u>High-Quality Video Webcams - Top 5 Combo's With Sound for 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-x100-pro-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo X100 Pro to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-is-geo-blocking-and-how-to-bypass-it-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, What is Geo-Blocking and How to Bypass it On Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://program-issues.techidaily.com/overcoming-subnautica-below-zero-crashes-a-comprehensive-guide-for-pc-gamers/"><u>Overcoming Subnautica (Below Zero) Crashes: A Comprehensive Guide for PC Gamers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/single-platform-focus-disabling-cross-play-for-personal-zen/"><u>Single-Platform Focus Disabling Cross-Play for Personal Zen</u></a></li>
</ul></div>

