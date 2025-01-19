---
title: Flexible Connection Setup on macOS with Multiple Network Locations - Tips
date: 2025-01-15T22:13:06.032Z
updated: 2025-01-19T20:58:28.294Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Requirements

The only thing you'll need is a device running an updated version of MacOS. This feature works with both wired and wireless connections.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2ipTu54inBo?si=gRegjvtVq5gm_PHo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Open System Preferences

Click the Apple menu at the top right of your display and select System Preferences from the menu.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 2\. Open Network

From within System Preferences, click the Network icon to open the Network section.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://on-screen-recording.techidaily.com/new-win-11-strategies-to-successfully-save-mov-files-for-2024/"><u>[New] Win 11 Strategies to Successfully Save .mov Files for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-the-complete-guide-to-prevent-and-repair-fb-video-issues-for-2024/"><u>[Updated] The Complete Guide to Prevent and Repair FB Video Issues for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-ultimate-compilation-the-top-5-high-fidelity-cameras/"><u>[Updated] Ultimate Compilation The Top 5 High Fidelity Cameras</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/conversor-de-video-gratuito-on-line-formatos-amv-e-avi-para-video-tudo-facilitado-pelo-movavi/"><u>Conversor De Vídeo Gratuito On-Line: Formatos AMV E Avi Para Video, Tudo Facilitado Pelo Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/convert-mov-files-into-3gp-format-for-free-on-movavi-web-platform/"><u>Convert MOV Files Into 3GP Format for Free on Movavi Web Platform</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/descubra-os-melhores-programas-de-edicao-de-video-para-entusiastas-de-games-no-pc-selecao-exclusiva-pela-movavi/"><u>Descubra Os Melhores Programas De Edição De Vídeo Para Entusiastas De Games No PC - Seleção Exclusiva Pela Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/free-online-converter-m4v-to-mkv-without-extra-costs-movavi/"><u>Free Online Converter - M4V to MKV Without Extra Costs | Movavi</u></a></li>
<li><a href="https://vp-tips.techidaily.com/free-tools-how-to-transform-avi-videos-into-mp4-format-on-pcs-and-mac-computers/"><u>Free Tools: How to Transform AVI Videos Into MP4 Format on PCs and Mac Computers</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-nokia-g22-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Nokia G22</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-poco-x5-pro-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Poco X5 Pro Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-motorola-g54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed Guide on Faking Your Location in Mozilla Firefox On Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/leading-security-consultancy-enhances-offerings-and-scales-operations-through-innovative-autoform-technology/"><u>Leading Security Consultancy Enhances Offerings & Scales Operations Through Innovative Autoform Technology</u></a></li>
<li><a href="https://win-blog.techidaily.com/mastering-the-art-of-correcting-acrocefexe-system-errors/"><u>Mastering the Art of Correcting AcroCEF.exe System Errors</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/movavimp3-mp4/"><u>Movaviで無償オンライン音楽形式(MP3, MP4)変換機能 - 利用ガイド</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/online-opus-m4a-movavi/"><u>Online OPUS M4A 항공전화 무료 변환 - Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/tournez-gratuitement-un-fichier-avi-en-format-aac-avec-online-converter-movavi/"><u>Tournez Gratuitement Un Fichier AVI en Format AAC Avec Online Converter - Movavi</u></a></li>
<li><a href="https://win-info.techidaily.com/transferring-music-from-spotify-to-a-separate-hard-drive-a-simple-how-to-tutorial/"><u>Transferring Music From Spotify to a Separate Hard Drive – A Simple How-To Tutorial</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/transformacion-gratuita-de-archivos-pef-a-png-por-medio-de-la-herramienta-online-de-movavi/"><u>Transformación Gratuita De Archivos PEF a PNG Por Medio De La Herramienta Online De Movavi</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/transformez-votre-fichier-video-mp4mpeg-en-animation-flash-swf-gratuitement-sur-le-site-de-conversion-de-movavi/"><u>Transformez Votre Fichier Vidéo MP4/MPEG en Animation Flash SWF Gratuitement Sur Le Site De Conversion De Movavi</u></a></li>
</ul></div>

