---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2025-01-04T20:25:02.745Z
updated: 2025-01-06T19:48:36.005Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **ZDNET** Recommends

[The best Macs Apple's Mac lineup can be confusing as the company transitions from Intel processors to its own Apple Silicon processors. But we're here to help.  Read now](https://www.zdnet.com/article/best-mac/)

For the general-purpose network, I can just have MacOS accept an IP address from the DHCP server. However, for the container network, I prefer assigning a static IP address.

Is this possible?

It certainly is. With the help of MacOS Network Locations, you can assign specific configurations for specific networks (or locations) and even define a particular network you want to connect to within a location.

Let me show you how it works.

**Also:** [**How to manage SSH connections on MacOS with Termius**](https://www.zdnet.com/article/how-to-manage-ssh-connections-on-macos-with-termius/) 

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kZVDkvMZvP4?si=xAugrCf-Ud6EMMpm" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fvAC8jgs62o?si=xqEXZ7dpAXZ4sZ7A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-chat-room-to-screen-step-by-step-google-meet-youtube-streams/"><u>[New] In 2024, From Chat Room to Screen Step-by-Step Google Meet YouTube Streams</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-restrict-viewership-of-your-youtube-content/"><u>[Updated] 2024 Approved How to Restrict Viewership of Your YouTube Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlock-hdri-magic-compreranial-sdr-to-high-dynamic-range-upgrade/"><u>[Updated] 2024 Approved Unlock HDRI Magic Compreranial SDR to High Dynamic Range Upgrade</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-recover-hidden-shorts-thumbnails-in-videos-for-2024/"><u>[Updated] How to Recover Hidden Shorts' Thumbnails in Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-transform-brainstorms-into-youtube-channel-names-for-2024/"><u>[Updated] How To Transform Brainstorms Into YouTube Channel Names for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-follow-the-flow-of-forum-fancies/"><u>[Updated] In 2024, Follow the Flow of Forum Fancies</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-blur-background-of-your-youtube-video/"><u>[Updated] In 2024, How to Blur Background of Your YouTube Video</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-secrets-for-striking-fb-video-promos-for-2024/"><u>[Updated] Secrets for Striking FB Video Promos for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/audio-dilemma-resolved-reactivating-sound-on-windows-during-zoom-sessions/"><u>Audio Dilemma Resolved: Reactivating Sound on Windows During Zoom Sessions</u></a></li>
<li><a href="https://win11-tips.techidaily.com/breaking-the-mold-reinventing-yourself-with-a-new-username-in-windows-11/"><u>Breaking the Mold: Reinventing Yourself with a New UserName in Windows 11</u></a></li>
<li><a href="https://extra-hints.techidaily.com/how-to-fix-one-airpod-not-working/"><u>How to Fix One Airpod Not Working?</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-repair-a-non-functional-igfxem-chipset-issue-successfully/"><u>How To Repair A Non-Functional igfxEM Chipset Issue Successfully</u></a></li>
<li><a href="https://extra-tips.techidaily.com/synchronizing-airwaves-for-audience-gain/"><u>Synchronizing Airwaves for Audience Gain</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-new-possibilities-how-access-to-chatgpt-and-whisper-apis-transforms-the-business-landscape/"><u>Unlocking New Possibilities: How Access to ChatGPT & Whisper APIs Transforms the Business Landscape</u></a></li>
</ul></div>

