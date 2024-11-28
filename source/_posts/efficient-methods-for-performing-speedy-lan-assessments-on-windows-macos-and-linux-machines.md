---
title: Efficient Methods for Performing Speedy LAN Assessments on Windows, macOS, and Linux Machines
date: 2024-11-21T19:02:57.358Z
updated: 2024-11-28T18:38:37.202Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Run a Speed Test on Mac via Terminal

 To accomplish this on Mac, we will be using [Homebrew](https://visual-screen-recording.techidaily.com/new-breaking-ground-video-capture-breakdown-for-2024/), a [popular macOS package manager](https://screen-activity-recording.techidaily.com/updated-in-2024-virtualvista-viewers-verdict/). If you haven't installed Homebrew yet or if you are unsure, open Terminal (you'll find it under Applications > Utilities) and enter the following command:

        `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
    
 This command will download and install Homebrew. Once installed, you can easily install the speed test CLI by entering:

        `brew install speedtest-cli`
    
 After the installation is complete, you can run the speed test by simply typing:

        `speedtest-cli  
`
    
![Running speedtest cli in macOS Terminal.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-macos-terminal.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 This command will initiate a quick analysis of your internet connection speed, all from within the Terminal. This method not only saves system resources but also eliminates the need for navigating through ad-heavy websites.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Run a Speed Test on Windows via Command Prompt

 Installing the speed test CLI on a Windows PC is straightforward. Start by visiting the [Speedtest CLI download page](https://www.speedtest.net/apps/cli). Scroll down to find the download option for Windows. It's important to note that the CLI tool is only available for 64-bit versions of Windows.

![Downloading Speedtest CLI on Windows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/downloading-speedtest-cli-for-windows-2.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 After downloading the installer, unzip the file to find "speedtest.exe." It's a good idea to place this file in a directory like C:\\Program Files\\speedtest.exe as this location is both easy to remember and accessible by all user accounts on your system. For added convenience, consider creating a desktop shortcut or pinning the executable to your taskbar.

 To run the speed test in Command Prompt (hit Start, type "command" and click "Command Prompt" when it appears), all you need to do is type the full path to the executable, encased in quotation marks to prevent conflicts arising from spaces, and hit enter:

        `"C:\Program Files\speedtest.exe"`
    
 To run in [PowerShell (Terminal)](https://techtrends.techidaily.com/what-are-the-stages-in-a-game-of-royal-match/), the syntax is slightly modified. You must prepend an ampersand to run the executable at the given file path, like so:

        `& "C:\Program Files\speedtest.exe"`
    
![Running Speedtest CLI in PowerShell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/07/running-speedtest-cli-in-powershell.png) 

 These commands will run the application via the command line, providing you with a quick readout of your current internet speed and related parameters.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-discover-variety-50-complimentary-youtube-banners-available/"><u>[New] 2024 Approved Discover Variety – 50 Complimentary YouTube Banners Available</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-finding-prominent-comment-spotlights/"><u>[New] 2024 Approved Finding Prominent Comment Spotlights</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-how-to-keep-unwanted-content-away-from-your-computer-and-phone/"><u>[New] In 2024, How to Keep Unwanted Content Away From Your Computer and Phone</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-the-complete-playbook-for-youtube-beginners/"><u>[New] In 2024, The Complete Playbook for YouTube Beginners</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-shedding-light-techniques-for-improving-youtube-video-quality/"><u>[Updated] Shedding Light Techniques for Improving YouTube Video Quality</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-iphone-hacks-listen-deep-to-your-podcasts/"><u>2024 Approved IPhone Hacks Listen Deep to Your Podcasts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-swiftly-start-sharing-joy-installing-the-ifunny-meme-app/"><u>2024 Approved Swiftly Start Sharing Joy Installing the iFunny Meme App</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-synopsis-of-vllo-consumer-voices/"><u>2024 Approved Synopsis of VLLO Consumer Voices</u></a></li>
<li><a href="https://fox-blue.techidaily.com/imagetangle-the-premier-montage-engineer-for-2024/"><u>ImageTangle The Premier Montage Engineer for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/jpg-tiff-movavi/"><u>JPG 및 TIFF 이미지를 원격으로 비용 없이 Movavi 소프트웨어로 바꾸기</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-realme-11-5g-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Realme 11 5G</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/stepwise-simplification-broadcasting-personal-yt-videos-using-gmail-for-2024/"><u>Stepwise Simplification Broadcasting Personal YT Videos Using Gmail for 2024</u></a></li>
</ul></div>

