---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2024-11-27T19:04:09.844Z
updated: 2024-11-28T17:21:25.275Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/O7ChChlyX2o?si=7pMKdN1NZig1kYek&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How to create different network locations in MacOS

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Create a new network location

From the Location drop-down, select Edit Locations. In the resulting pop-up, click + (the plus sign). You will be prompted to name the location, so type a new name and hit Enter on your keyboard, and then click Done.

Creating a new Network Location in MacOS Monterey.

Image: Jack Wallen

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 4\. Configure the new location

Make sure to select the new location you created from the Location drop-down. Click Advanced to open the location configuration window, where you can configure the location to meet your specific needs. For example, you can select the network to be used and then configure that network for a static IP address using the Cloudflare DNS servers.

Configuring a network for the new location in MacOS.

Image: Jack Wallen

Once you've configured the location exactly how you need it, click Apply to save everything.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/024-approved-unleashing-creativity-secrets-of-unique-yt-short-content/"><u>[New] 2024 Approved Unleashing Creativity Secrets of Unique YT Short Content</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-seamless-saving-of-snapchat-images-on-device-memory/"><u>[New] Seamless Saving of SnapChat Images on Device Memory</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-pro-level-techniques-to-upgrade-your-iphone-photo-game/"><u>[Updated] Pro-Level Techniques to Upgrade Your iPhone Photo Game</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/mp4mov-moviconvert/"><u>免費網站從MP4到MOV格式提高 - 利用 MoviConvert</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/aifc-file-transformation-no-cost-fast-and-easy-via-movavi/"><u>AIFC File Transformation: No Cost, Fast & Easy via Movavi</u></a></li>
<li><a href="https://tech-revival.techidaily.com/decoding-the-pros-and-cons-of-using-chatgpt-plus-in-digital-communication/"><u>Decoding the Pros and Cons of Using ChatGPT Plus in Digital Communication</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/gratuito-conversor-online-de-video-ogv-para-ogg-pela-movavi/"><u>Gratuito Conversor Online De Vídeo: OGV Para OGG Pela Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/guia-paso-a-paso-para-convertir-archivos-m4a-a-avi-de-forma-gratuita-en-linea-con-emovavi/"><u>Guía Paso a Paso Para Convertir Archivos M4A a AVI De Forma Gratuita en Línea Con eMovavi</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-sony-xperia-1-v-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Sony Xperia 1 V | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-vivo-y28-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Vivo Y28 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/online-dts-to-wav-conversion-tool-free-service-by-movavi/"><u>Online DTS to WAV Conversion Tool: Free Service by Movavi</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ditors-top-list-best-portable-devices-for-visual-storytelling-for-2024/"><u>Pro-Editors' Top List Best Portable Devices for Visual Storytelling for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/step-by-step-guide-downloading-podcast-episodes-across-various-platforms-pc-iphone-and-android-movavi/"><u>Step-by-Step Guide: Downloading Podcast Episodes Across Various Platforms (PC, iPhone & Android) - Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/top-5-editoras-mais-populares-de-filmes-mov-em-2024-acesso-completamente-livre/"><u>Top 5 Editoras Mais Populares De Filmes MOV Em 2024 - Acesso Completamente Livre</u></a></li>
<li><a href="https://hardware-help.techidaily.com/ultimate-guide-to-the-finest-windows-laptops-of-2024-professional-evaluations-and-ratings-by-experts-zdnet/"><u>Ultimate Guide to the Finest Windows Laptops of 2024: Professional Evaluations and Ratings by Experts | ZDNet</u></a></li>
</ul></div>

