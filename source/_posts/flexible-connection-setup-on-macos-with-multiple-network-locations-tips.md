---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2025-01-09T18:15:29.667Z
updated: 2025-01-13T17:51:54.065Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=3YDfzJAZMDp1gFRz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-clips.techidaily.com/new-break-even-on-youtube-monetizing-with-a-minimum-of-500-viewers/"><u>[New] Break Even on Youtube Monetizing with a Minimum of 500 Viewers</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-exploring-the-world-of-montage-image-magic/"><u>[New] Exploring the World of Montage Image Magic</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-hidden-pitfalls-investing-in-fraudulent-subscribers-for-2024/"><u>[New] Hidden Pitfalls Investing in Fraudulent Subscribers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-battle-royale-queens-top-10-female-youtubers/"><u>[Updated] 2024 Approved Battle Royale Queens Top 10 Female YouTubers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-editing-excellence-the-ultimate-guide-to-top-notebooks/"><u>[Updated] 2024 Approved Editing Excellence The Ultimate Guide to Top Notebooks</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-going-pro-with-gs-effects-exclusive-free-lessons-from-4-premier-video-channels/"><u>[Updated] 2024 Approved Going Pro with GS Effects Exclusive Free Lessons From 4 Premier Video Channels</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-expertly-selected-graphics-cards-for-peak-streaming-clarity/"><u>[Updated] Expertly Selected Graphics Cards for Peak Streaming Clarity</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-free-video-wizardry-top-8-editing-programs-for-youtube-enthusiasts-for-2024/"><u>[Updated] Free Video Wizardry Top 8 Editing Programs for YouTube Enthusiasts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-earning-potential-in-beauty-blogging/"><u>[Updated] In 2024, Earning Potential in Beauty Blogging</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-effortlessly-stream-mp3-to-youtube-with-3-key-steps/"><u>[Updated] In 2024, Effortlessly Stream MP3 to YouTube with 3 Key Steps</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-elite-collection-top-10-sites-for-professional-icons/"><u>[Updated] The Elite Collection Top 10 Sites for Professional Icons</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-maximize-view-count-best-yt-thumbnail-sizes/"><u>2024 Approved Maximize View Count Best YT Thumbnail Sizes</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/o-effortlessly-eradicate-unwanted-youtube-feedback/"><u>How to Effortlessly Eradicate Unwanted YouTube Feedback</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-open-your-apple-iphone-8-without-a-home-button-drfone-by-drfone-ios/"><u>How To Open Your Apple iPhone 8 Without a Home Button | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-rootjunky-apk-to-bypass-google-frp-lock-for-honor-magic-6-pro-by-drfone-android/"><u>In 2024, Rootjunky APK To Bypass Google FRP Lock For Honor Magic 6 Pro</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/simplicity-in-downloading-youtube-graphics-for-2024/"><u>Simplicity in Downloading YouTube Graphics for 2024</u></a></li>
<li><a href="https://win-luxury.techidaily.com/solucion-inmediata-para-el-error-de-carpeta-vacia-en-windows-11/"><u>Solución Inmediata Para El Error De 'Carpeta Vacía' En Windows 11</u></a></li>
</ul></div>

