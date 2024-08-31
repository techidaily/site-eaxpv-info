---
title: "Mastering File Renaming: A Step-by-Step Guide Using PowerShell"
date: 2024-08-30T16:49:04.798Z
updated: 2024-08-31T16:49:04.798Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/fe3425cd8bd2ff0c1232de1bab83bce21e82181cb81ffb7e2c2a0692c27f7927.png
---

## Mastering File Renaming: A Step-by-Step Guide Using PowerShell

### Quick Links

* [Before You Begin: Learn How to Find a File or Folder’s Full Path](https://video-capture.techidaily.com/new-top-5-xbox-external-hard-drive-you-can-find/)
* [How to Rename a Specific File](https://visual-screen-recording.techidaily.com/updated-vidmas-technology-in-screen-capturing-spotlighted/)
* [How to Rename Files in a Folder With an Increasing Number](https://bypass-frp.techidaily.com/easy-guide-how-to-bypass-xiaomi-redmi-note-12-proplus-5g-frp-android-10111213-by-drfone-android/)
* [How to Add a Prefix or Suffix to a File Name](https://facebook-video-share.techidaily.com/updated-2024-approved-achieving-excellent-illumination-on-youtube-videos/)
* [How to Add Timestamps to All Files in a Folder](https://extra-guidance.techidaily.com/srt-simplified-core-concepts-made-clear-for-2024/)

 PowerShell makes renaming files from the command line super easy. You can use specific names, add increasing numbers, add prefixes and suffixes, and even append timestamps. We’ll show you how to do that all on your Windows 11 or Windows 10 computer.

##  Before You Begin: Learn How to Find a File or Folder’s Full Path

 To rename files, you’ll have to provide PowerShell with your file or parent folder’s full path. If you know how to do this, skip to the relevant section below. If you aren’t quite sure [how to get a folder or file’s full path](https://fox-links.techidaily.com/updated-2024-approved-unparalleled-screenplay-craftsmanship-across-varied-fields/), we’ll show you.

[Open a File Explorer window](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) and find your file or folder. Press and hold down the Shift key on your keyboard, right-click your file or folder, and choose "Copy as Path."

!['Copy as Path' highlighted in Windows 11's context menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-copy-file-path-windows.jpg) 

 That action has copied your selected item’s full path to your clipboard. You can now [paste this path](https://twitter-videos.techidaily.com/new-in-2024-gain-twitter-gifs-for-pc-download-made-simple/) wherever required in the commands below.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Rename a Specific File

 To give a new name to a specific file on your PC, use PowerShell’s Rename-Item [cmdlet](https://extra-guidance.techidaily.com/new-prophotomaster-the-ai-enhanced-editing-edge/). This cmdlet takes your file’s full path, the new name you want to assign, and renames your file.

 To use it, launch a PowerShell window on your PC and type the following command. In the command, replace **PATH** with the full path to your file. Your path should have the file’s full name as well as the extension. Replace **MyName** with the new name you want to use, and **ext** with your file’s original extension.

Rename-Item PATH -NewName MyName.ext

 Make sure to use your file’s original extension when you rename the file. Using another extension can make your file unusable.

 As an example, to rename a file named Old-Test.txt located on your desktop to New-Test.txt, you’d use the following command:

Rename-Item "C:\Users\Username\Desktop\Old-Test.txt" -NewName “New-Test.txt”

!['Rename-Item' cmdlet in a PowerShell window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-rename-file-with-powershell.jpg) 

 PowerShell won’t display a message confirming your file is renamed, but know that the job is done.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  How to Rename Files in a Folder With an Increasing Number

 If you want to add an increasing number, such as 1, 2, 3, and so on, to your files in a specific folder, follow these steps.

 Launch a PowerShell window and type the following command. Replace **PATH** with the full path to your folder, and **txt** with the format of the files to rename. Then, press Enter.

Get-ChildItem PATH -Recurse -Include "*.txt" | ForEach-Object -Begin { $Counter = 1 } -Process { Rename-Item $_.FullName -NewName ("{0}_{1}" -f $Counter, $_.Name) ; $Counter++ }

![Files with an increasing number in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/3-add-numbers-to-file-names.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Add a Prefix or Suffix to a File Name

 To add text before your file name (known as a prefix), launch a PowerShell window and enter the following command. Replace **PATH** with your folder's full path, and **PREFIX** with the text you want to append, then press Enter.

Get-ChildItem PATH | Rename-Item -NewName {"PREFIX" + $_.Name}

 To add text after your file’s name (called a suffix), use the following command, replacing **PATH** with the full path to your folder, and **SUFFIX** with the text to append. Then, press Enter.

Get-ChildItem PATH | Rename-Item -NewName {$_.BaseName + "SUFFIX" + $_.Extension}

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940312&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Add Timestamps to All Files in a Folder

 If you want to add a timestamp to all the files in a folder, open PowerShell and type the following command. Replace **PATH** with the full path to your folder, and press Enter.

Get-ChildItem PATH -Recurse -Include "*.*" | ForEach-Object { Rename-Item -Path $_.FullName -NewName "$($_.DirectoryName)\$($_.BaseName)_$(Get-Date -F yyyy-MM-dd_HH-mm)$($_.Extension)"}

![Files with timestamp in File Explorer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/4-add-timestamp-to-file-names.jpg) 

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The above command uses your computer’s system time. If that time is incorrect, it’s possible to [change the timezone on your Windows 11](https://instagram-videos.techidaily.com/new-2024-approved-harnessing-the-power-of-hashtags-to-amplify-your-igtv-content/) and [Windows 10](https://extra-support.techidaily.com/in-2024-leveraging-daylight-in-home-interiors/) PC.

---

 And that’s how you assign new names one file at a time or in bulk on your Windows system, without using File Explorer. It's just one of the many ways that PowerShell aids with mundane Windows tasks.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-filmoras-quick-start-approach-for-youtube-trailers/"><u>[New] 2024 Approved  Filmora's Quick-Start Approach for YouTube Trailers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-novice-to-expert-selecting-best-yt-cameras/"><u>[New] 2024 Approved  From Novice to Expert  Selecting Best YT Cameras</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-get-premium-banners-no-cost-just-click/"><u>[New] 2024 Approved  Get Premium Banners - No Cost, Just Click</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-high-earning-video-visionaries/"><u>[New] 2024 Approved  High Earning Video Visionaries</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-illuminate-a-guide-to-great-vlog-images/"><u>[New] 2024 Approved  How to Illuminate  A Guide to Great Vlog Images</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-first-steps-into-filmmaking-the-ultimate-guide-for-making-your-first-10-youtube-videos-for-2024/"><u>[New] First Steps Into Filmmaking  The Ultimate Guide for Making Your First 10 YouTube Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-freefire-gaming-guide-maximizing-video-impact-for-2024/"><u>[New] FreeFire Gaming Guide  Maximizing Video Impact for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-shots-to-screens-the-importance-of-camera-lenses-in-vlogs-for-2024/"><u>[New] From Shots to Screens  The Importance of Camera Lenses in Vlogs for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-harness-social-blade-for-profound-youtube-stats-analysis-for-2024/"><u>[New] Harness Social Blade for Profound YouTube Stats Analysis for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-clear-the-clutter-blurring-backgrounds-for-engaging-yt-for-2024/"><u>[New] How to Clear the Clutter  Blurring Backgrounds for Engaging YT for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-a-tale-of-two-approaches-polite-vs-aggressive-asking/"><u>[New] In 2024, A Tale of Two Approaches  Polite vs Aggressive Asking</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-freshest-beats-newly-trending-music-for-youtube-short-videos/"><u>[New] In 2024, Freshest Beats  Newly Trending Music for YouTube Short Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-bland-to-brilliant-transform-your-youtube-channels-image/"><u>[New] In 2024, From Bland to Brilliant  Transform Your YouTube Channels' Image</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-blank-canvas-to-biggest-hit-mastering-youtube-thumbnail-sizes/"><u>[New] In 2024, From Blank Canvas to Biggest Hit  Mastering YouTube Thumbnail Sizes</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-raw-to-masterpiece-the-premier-free-mobile-editors-for-android/"><u>[New] In 2024, From Raw to Masterpiece  The Premier Free Mobile Editors for Android</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gain-traction-in-the-algorithm-the-insiders-manual-for-featured-channels/"><u>[New] In 2024, Gain Traction in the Algorithm  The Insider's Manual for Featured Channels</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gaining-traction-on-youtube-the-successful-sponsorship-roadmap-by-famebit/"><u>[New] In 2024, Gaining Traction on YouTube  The Successful Sponsorship Roadmap by FameBit</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-get-unlimited-echoes-for-online-content-makers/"><u>[New] In 2024, Get Unlimited Echoes for Online Content Makers</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-end-your-youtube-void-top-10-insights-on-igniting-video-interest/"><u>[New] In 2024, How To End Your Youtube Void  Top 10 Insights on Igniting Video Interest</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-reduce-buffering-and-lag-turn-on-av1-in-youtube-settings/"><u>[New] Reduce Buffering & Lag - Turn On AV1 in YouTube Settings</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-flash-freeze-focus-leading-cameras-for-slow-speed-recording/"><u>[Updated] Flash Freeze Focus  Leading Cameras for Slow Speed Recording</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-gaming-hits-with-powerful-hashtag-strategies-for-2024/"><u>[Updated] Gaming Hits with Powerful Hashtag Strategies for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-vlog-confidently-like-popular-youtubers-in-2024/"><u>[Updated] How to Vlog Confidently Like Popular YouTubers, In 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-hiring-heroes-the-most-motivating-vids-of-the-year-1-10/"><u>[Updated] In 2024, Hiring Heroes  The Most Motivating Vids of the Year #1-10</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-make-your-videos-a-youtube-hit-top-tips-and-strategies/"><u>[Updated] In 2024, How To Make Your Videos a YouTube Hit  Top Tips and Strategies</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-shave-seconds-off-your-youtube-video-submission/"><u>[Updated] In 2024, How to Shave Seconds Off Your YouTube Video Submission</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-inside-look-freewebcampro-software-overview/"><u>[Updated] In 2024, Inside Look  FreeWebcamPro Software Overview</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-ultimate-image-booster-intense-visual-upgrade/"><u>[Updated] Ultimate Image Booster  Intense Visual Upgrade</u></a></li>
<li><a href="https://article-files.techidaily.com/2024-approved-live-or-recorded-twitch-versus-youtube-face-off/"><u>2024 Approved  Live or Recorded  Twitch versus YouTube Face Off</u></a></li>
<li><a href="https://fox-that.techidaily.com/cant-get-texts-on-your-iphone-fix-apples-cross-platform-sms-problem-with-ease/"><u>Can't Get Texts on Your iPhone? Fix Apple's Cross-Platform SMS Problem with Ease</u></a></li>
<li><a href="https://extra-information.techidaily.com/capturing-movement-with-clarity-implementing-motion-blur-on-peoples-photos-with-picsart/"><u>Capturing Movement with Clarity  Implementing Motion Blur on People's Photos with Picsart</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-realme-gt-neo-5-se-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Realme GT Neo 5 SE Phone | Dr.fone</u></a></li>
<li><a href="https://win-howtos.techidaily.com/guide-to-circumventing-the-persistent-windows-10-0x800f0922-update-hurdle/"><u>Guide To Circumventing The Persistent Windows 10 0X800f0922 Update Hurdle</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Honor Play 8T? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-top-12-prominent-infinix-zero-5g-2023-turbo-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Infinix Zero 5G 2023 Turbo Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/planning-to-use-a-pokemon-go-joystick-on-poco-c65-drfone-by-drfone-virtual-android/"><u>Planning to Use a Pokemon Go Joystick on Poco C65? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/reveal-your-future-design-with-our-selection-of-top-9-websites-for-type-innovation/"><u>Reveal Your Future Design with Our Selection of Top 9 Websites for Type Innovation</u></a></li>
</ul></div>
