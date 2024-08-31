---
title: Efficient Methods for Performing Speedy LAN Assessments on Windows, macOS, and Linux Machines
date: 2024-08-30T16:49:45.839Z
updated: 2024-08-31T16:49:45.839Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/illustration-of-a-rocket-launching-and-a-connection-speed-bar.jpg
---

## Efficient Methods for Performing Speedy LAN Assessments on Windows, macOS, and Linux Machines

### Quick Links

* [Run a Speed Test on Mac via Terminal](https://instagram-videos.techidaily.com/new-capture-and-replay-screen-recording-for-instagram-stories-for-2024/)
* [Run a Speed Test on Windows via Command Prompt](https://fake-location.techidaily.com/ispoofer-is-not-working-on-xiaomi-redmi-note-12-proplus-5g-fixed-drfone-by-drfone-virtual-android/)
* [Run a Speed Test on Linux via Terminal](https://games-able.techidaily.com/bring-back-those-good-old-days-why-your-game-needs-pi/)

 Internet speed test websites are often bogged down with ads, slowing down your system. Fortunately, Ookla offers a lightweight Command Line Interface (CLI) version of its speed test so you can test your internet speed without the overhead of a web browser. Here's how to use it on macOS, Windows, and Linux.

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Run a Speed Test on Linux via Terminal

 Linux users have a slightly different setup process, as the steps can vary depending on the distribution. Here, we'll cover the installation process for one of the [most widely used distributions](https://win11.techidaily.com/the-art-of-merging-your-guide-to-windows-efficiency/): Debian/Ubuntu.

 First, open a Terminal window. Before installing the speed test CLI, you may need to install curl, a command-line tool for transferring data with URLs. If you're unsure whether curl is installed, you can install it by running:

        `sudo apt-get install curl`
    
 Next, add the Ookla repository to your list of package sources. This ensures that you get the latest version of the speed test CLI. Use the following command to do this:

        `curl -s https://packagecloud.io/install/repositories/ookla/speedtest-cli/script.deb.sh | sudo bash`
    
 Once the repository is added, you can install the speed test CLI with:

        `sudo apt-get install speedtest`
    
![Running Speedtest CLI on Ubuntu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-on-ubuntu-1.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 After installation, you can test your internet speed by typing "speedtest" in the Terminal and pressing enter. This command will run the test and display the results directly in the window.

---

 Using Ookla's CLI speed test is an efficient way to measure your internet connection speed without the distractions and slowdowns caused by browser-based tools. No matter which OS you're using, this lightweight tool provides accurate and quick results. It's particularly useful when you want to avoid ads or need to integrate speed tests into automated systems or scripts.

 With just a few commands or a shortcut workflow, you can have a reliable tool at your disposal for monitoring and diagnosing your network performance, empowering you to run a network test at the drop of a hat or a hotkey.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-finalizing-your-video-with-a-bold-statement/"><u>[New] 2024 Approved  Finalizing Your Video with a Bold Statement</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-frameworks-producing-uplifting-life-journey-broadcasts/"><u>[New] 2024 Approved  Frameworks  Producing Uplifting Life Journey Broadcasts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-frame-to-firm-selecting-your-mcn-partner/"><u>[New] 2024 Approved  From Frame to Firm  Selecting Your MCN Partner</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-from-raw-footage-to-polished-content-youtube-studio-edition/"><u>[New] 2024 Approved  From Raw Footage to Polished Content  YouTube Studio Edition</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guerrilla-marketing-for-youtube-upping-video-traffic/"><u>[New] 2024 Approved  Guerrilla Marketing for YouTube  Upping Video Traffic</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-hastened-steps-for-clear-background-filming-success/"><u>[New] 2024 Approved  Hastened Steps for Clear Background Filming Success</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-focusing-attention-with-eye-catching-intros-in-imovie-for-2024/"><u>[New] Focusing Attention with Eye-Catching Intros in iMovie for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-gaming-insiders-youtube-channels-you-should-see-for-2024/"><u>[New] Gaming Insiders' YouTube Channels You Should See for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-google-meet-broadcast-simplified-youtube-steps-for-2024/"><u>[New] Google Meet Broadcast Simplified  YouTube Steps for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-graphical-forecast-the-dominant-23-social-themes-for-2024/"><u>[New] Graphical Forecast  The Dominant '23 Social Themes for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-guaranteed-method-to-keep-youtube-shorts-out-of-sight-for-2024/"><u>[New] Guaranteed Method to Keep YouTube Shorts Out of Sight for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-insert-youtube-playlists-seamlessly-into-a-website-for-2024/"><u>[New] How to Insert YouTube Playlists Seamlessly Into a Website for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-stand-out-yt-thumbnail-size-and-engagement-strategies-for-2024/"><u>[New] How to Stand Out  YT Thumbnail Size and Engagement Strategies for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-find-your-way-the-insider-guide-to-youtube-video-management-hub/"><u>[New] In 2024, Find Your Way  The Insider Guide to YouTube Video Management Hub</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-fixing-the-problem-hidden-thumbnails-in-youtube-shorts/"><u>[New] In 2024, Fixing the Problem  Hidden Thumbnails in YouTube Shorts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-harness-the-full-potential-of-your-youtube-content-using-wmm/"><u>[New] In 2024, Harness the Full Potential of Your YouTube Content Using WMM</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-captivate-audiences-and-gain-traction-with-youtube-shorts/"><u>[New] In 2024, How to Captivate Audiences and Gain Traction with YouTube Shorts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-follow-the-footsteps-of-fan-driven-forums/"><u>[Updated] 2024 Approved  Follow the Footsteps of Fan-Driven Forums</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-newbie-to-pro-your-complete-guide-to-creator-studio/"><u>[Updated] 2024 Approved  From Newbie to Pro  Your Complete Guide to Creator Studio</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-create-impactful-video-elements-cardsannotations/"><u>[Updated] 2024 Approved  How to Create Impactful Video Elements  Cards/Annotations</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-find-peace-and-power-the-10-greatest-yoga-channels-online-for-2024/"><u>[Updated] Find Peace & Power  The 10 Greatest Yoga Channels Online for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-frame-by-frame-building-a-filmmaking-foundation-on-youtube-for-2024/"><u>[Updated] Frame by Frame  Building a Filmmaking Foundation on YouTube for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-free-yourself-with-top-4-applications-for-youtube-to-wav-conversion-for-2024/"><u>[Updated] Free Yourself with Top 4 Applications for YouTube-to-WAV Conversion for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-chaos-to-clarity-professional-tools-for-youtube-cuts-for-2024/"><u>[Updated] From Chaos to Clarity  Professional Tools for Youtube Cuts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-flavor-leaders-must-watch-culinary-youtube-stars/"><u>[Updated] In 2024, Flavor Leaders  Must-Watch Culinary YouTube Stars</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-easy-to-use-online-editors-for-quick-postings/"><u>[Updated] In 2024, Free, Easy-to-Use Online Editors for Quick Postings</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-gamers-nexus-1000plus-game-sessions/"><u>[Updated] In 2024, Gamers' Nexus  1,000+ Game Sessions</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-get-back-to-pure-content-how-to-block-youtube-ads-on-all-devices/"><u>[Updated] In 2024, Get Back to Pure Content  How to Block YouTube Ads on All Devices</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-add-timestamps-on-youtube-video-link/"><u>[Updated] In 2024, How to Add Timestamps on YouTube Video Link?</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-convert-youtube-videos-to-mp3-songs-on-mac/"><u>[Updated] In 2024, How to Convert YouTube Videos to MP3 Songs on Mac</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-leave-a-lasting-impression-with-your-video-ending/"><u>[Updated] In 2024, How to Leave a Lasting Impression with Your Video Ending</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unlocking-full-potential-share-videos-on-fb-effectively/"><u>[Updated] Unlocking Full Potential  Share Videos on FB Effectively</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-cinematic-clarity-hub-query-responses/"><u>2024 Approved  Cinematic Clarity Hub  Query Responses</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-unmute-youtube-links-in-silent-twitter-videos/"><u>2024 Approved  Unmute YouTube Links in Silent Twitter Videos</u></a></li>
<li><a href="https://facebook.techidaily.com/avoid-faux-friend-requests-6-key-strategies/"><u>Avoid Faux Friend Requests – 6 Key Strategies</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/boosting-online-presence-top-30-freefire-hashtags-and-tag-strategies/"><u>Boosting Online Presence  Top 30 FreeFire Hashtags and Tag Strategies</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-fixes-how-to-recover-default-printer-and-scanner-driver-support-in-windows-10/"><u>Easy Fixes: How to Recover Default Printer and Scanner Driver Support in Windows 10</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-android-photography-excellence-tips-and-tools/"><u>In 2024, Android Photography Excellence  Tips and Tools</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-beyond-the-skyline-with-yuneecs-typhoon-q500/"><u>In 2024, Beyond the Skyline with Yuneec's Typhoon Q500</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-vivo-y100a-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Vivo Y100A</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-from-your-apple-iphone-se-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock From your Apple iPhone SE</u></a></li>
<li><a href="https://fix-guide.techidaily.com/reasons-for-honor-magic-6-stuck-on-boot-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Honor Magic 6 Stuck on Boot Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/revolutionizing-raspberry-pi-pico-projects-why-breadboardos-outshines-traditional-methods/"><u>Revolutionizing Raspberry Pi Pico Projects: Why BreadboardOS Outshines Traditional Methods</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/validating-your-visual-story-on-instagram/"><u>Validating Your Visual Story on Instagram</u></a></li>
</ul></div>
