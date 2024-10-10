---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2024-10-09T02:45:09.517Z
updated: 2024-10-10T00:41:55.660Z
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
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037474/7443" target="_top" id="2037474">
  <img src="//a.impactradius-go.com/display-ad/7443-2037474" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037474/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-the-quintessential-selection-5-must-have-mac-snipers-for-2024/"><u>[New] The Quintessential Selection 5 Must-Have Mac Snipers for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-unearthing-the-potential-in-magixs-image-sorter/"><u>[Updated] Unearthing the Potential in MAGIX's Image Sorter</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-realme-gt-5-pro-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Realme GT 5 Pro | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/dvd-mp4-h264hevc-dvd/"><u>迅速直截了當的 Dvd 转换为 MP4 H.264/HEVC - 解決 DVD 重復和改正</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1725290622635-aiai/"><u>AIを活用したブラックアンドホワイト映像の高度な色彩変換手法：プロフェッショナルにカラー化できる最新AIツールリスト</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/best-alternatives-to-kickasstorrents-top-5-sites-for-legal-movie-and-game-downloads/"><u>Best Alternatives To KickassTorrents: Top 5 Sites For Legal Movie & Game Downloads</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/bypassing-the-dvd-shrink-not-working-hurdle-for-windows-10-users-effective-solutions-and-tips/"><u>Bypassing the 'DVD Shrink Not Working' Hurdle for Windows 10 Users: Effective Solutions and Tips</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/comprehensive-analysis-protecting-your-macbook-pro-13-with-a-high-quality-fintie-case/"><u>Comprehensive Analysis: Protecting Your MacBook Pro 13 with a High-Quality Fintie Case</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/discover-the-ultimate-freebies-choose-any-of-these-top-3-free-tools-to-craft-stunning-4k-slideshows/"><u>Discover the Ultimate Freebies: Choose Any of These Top 3 Free Tools to Craft Stunning 4K Slideshows!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/h264/"><u>H.264 ビデオコーデックの詳細なセットアップガイドと推奨包を無料でダウンロード</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-realme-c53-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Realme C53 Phone that is Locked?</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-honor-magic-5-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Honor Magic 5 to PC? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-premier-tech-list-top-17-software-for-photo-background-eradication/"><u>In 2024, Premier Tech List Top 17 Software for Photo Background Eradication</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-10-password-cracking-tools-for-oppo-k11-5g-by-drfone-android/"><u>In 2024, Top 10 Password Cracking Tools For Oppo K11 5G</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/mp4-versus-avi-in-depth-analysis-of-two-leading-video-formats-for-optimal-streaming-quality/"><u>MP4 Versus AVI: In-Depth Analysis of Two Leading Video Formats for Optimal Streaming Quality</u></a></li>
<li><a href="https://techidaily.com/reset-pattern-lock-tutorial-for-m6-pro-4g-by-drfone-android-unlock-android-unlock/"><u>Reset pattern lock Tutorial for M6 Pro 4G</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/spielt-die-xbox-one-auch-dvd-filme-ab-eine-umfassende-anleitung-zur-instandsetzung-und-fehlerbehebung/"><u>Spielt Die Xbox One Auch DVD-Filme Ab? - Eine Umfassende Anleitung Zur Instandsetzung Und Fehlerbehebung</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unveiling-edit-capabilities-in-dall-e-3-progress-and-potential-improvements-needed/"><u>Unveiling Edit Capabilities in DALL-E 3: Progress and Potential Improvements Needed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/1725286040234-digiarty-winx-dvd/"><u>オンラインショップ用ガイド：Digiarty WinX DVD製品情報と選び方</u></a></li>
</ul></div>

