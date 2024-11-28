---
title: "Step-by-Step Process: Finding the Motherboard Serial in Windows Computers"
date: 2024-11-27T18:26:59.036Z
updated: 2024-11-28T18:44:04.030Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a398f18ec0de1a37637c260e06464220af2d995e8ad26b4b76b8430c1741deb5.jpg
---

## Step-by-Step Process: Finding the Motherboard Serial in Windows Computers

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6KXVWj6Ar1M?si=Cd_jktmoN3e9OzH3&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Quick Links

* [Why Do I Want To Find My Motherboard Model?](https://fox-http.techidaily.com/updated-in-2024-joyful-journeys-the-ultimate-list-of-familial-classics/)
* [Find Your Motherboard Model Number with CIM in PowerShell](https://fox-boxes.techidaily.com/2024-approved-editorsuite-ultimate-guide-in-depth-analysis-of-androvid/)
* [Check Your Model Number from the Command Prompt (or PowerShell) with WMIC](https://www.howtogeek.com/208420/how-to-check-your-motherboard-model-number-on-your-windows-pc/#check-your-model-number-from-the-command-prompt-or-powershell-with-wmic)
* [Check Your Model Number in System Information](https://facebook-video-footage.techidaily.com/updated-master-quick-youtube-video-rendering-and-efficient-uploading/)
* [Check Your Model Number with Speccy](https://win11-tips.techidaily.com/how-to-thrive-in-free-championship-football-simulator/)
* [Check Your Motherboard Model with HWiNFO64](https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-motorola-moto-g-stylus-2023-drfone-by-drfone-virtual-android/)

### Key Takeaways

 To get your motherboard model, run "wmic baseboard get product,Manufacturer,version,serialnumber" in Command Prompt or PowerShell. You can also search "System Information" in the Start Menu, then look for "BaseBoard Product" in your system details.

 Whether you need to update drivers, check hardware compatibility, or you're just curious, it's way easier to check your motherboard model number with these simple tricks than to crack open your case to check the board itself. Here's how to check your motherboard model number from the comfort of your keyboard.

##  Why Do I Want To Find My Motherboard Model?

 Knowing your motherboard's model number is important if you're thinking of upgrading your drivers, buying new hardware (you'll need the proper expansion or memory slots, for example), or just checking the capabilities of your board if you're considering upgrading your whole rig.

 If you kept the paperwork that came with your computer (or the individual components, if you built it yourself), you can often times reference that. Even then, it's best to check to make sure the documentation is correct. Rather than open the case and search for the model number on the board itself, use tools within Windows to check things out instead.

##  Find Your Motherboard Model Number with CIM in PowerShell

 Common Information Model (CIM) cmdlets are commands you can run to get information about your PC's hardware or software from a command-line interface. If you've used WMIC in the past you'll feel right at home with CIM, and if you haven't, don't worry—it is easy to use. 

 First, open up a PowerShell or Command Prompt window. It doesn't need to be run as administrator, though that won't hurt either. 

![Search for "PowerShell" in the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/1-open-powershell.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 The run the following command to get information about your motherboard: 

Get-CimInstance -ClassName Win32_baseboard

![The information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-baseboard-deets.png) 

 Depending on what information is available, you may or may not get an actual model number. However, you'll almost always get something in the "Product" field that will be enough to figure out what motherboard is in your PC. 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Check Your Model Number from the Command Prompt (or PowerShell) with WMIC

 WMIC is technically deprecated but still works.

 If you're comfortable using the Command Prompt (or PowerShell, where these commands also work), you can easily check a variety of motherboard and hardware stats using the handy Windows Management Instrumentation Command-line (WMIC)—a command-line interface for Microsoft's powerful WMI tool.

 With the WMIC, you can entry the query baseboard to check motherboard stats, and then use additional modifiers like get Manufacturer, Model, Name, PartNumber, slotlayout, serialnumber, or poweredon to get more detailed information about the motherboard.

 As an example, let's check a motherboard's manufacturer, model number, and serial number using WMIC.

 Open up the command prompt in Windows via either the run dialog (Windows+R) or by searching for "cmd" on the Start menu—no need to run the Command Prompt as an administrator. And, as we mentioned, you could also use PowerShell here, if you prefer. The command works the same in both shells. At the command line, type the following text (noting that there are no spaces between the modifiers—just commas), and then hit Enter:

wmic baseboard get product,Manufacturer,version,serialnumber

![The Command Prompt will display your motherboard manufacturer and model.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_1.png) 

 The information returned checks out for the motherboard we're using: the manufacturer is Gigabyte, the board is the Z170X-Gaming 7, and while the WMIC tool tried to check the serial number, Gigabyte left that particular bit unfilled for whatever reason. Nonetheless, the WMIC tool functioned just as it should, and without opening the case or using any third party tools, we have the basic information we're looking for.

##  Check Your Model Number in System Information

 System Information is a no-frills way to look up the details of your PC's hardware and software. There are two easy ways to launch it. Click the Start button, type "System Information" into the search bar, and then hit Enter or click "Open."

![Click the Start button, type "system information" into the search bar, then hit Enter or click "Open."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/click-system-information.png) 

 Alternatively, you can use the Run window. Hit Windows+R to open a run dialog, then type "msinfo32" into the Run prompt and hit Enter.

 The "System Summary" page will be open by default. Scroll down and look for the line named "BaseBoard Product"—that is your motherboard.

![Look for a line named "BaseBoard Product." That is your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/look-for-baseboard-product.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Check Your Model Number with Speccy

 If you want another GUI-based way to check your motherboard's model number (as well as a method that yields more information at a glance than the WMIC tool), you can grab the free tool [Speccy](https://www.piriform.com/speccy). It's a handy app to have around.

 After downloading and installing Speccy, go ahead and fire it up.

 You can see the motherboard model number right on the summary page, along with it's current operating temperature (assuming your board includes that). You can also see basic details about other system components.

![The &quot;Summary&quot; page will display your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_2.png) 

 Click over to the "Motherboard" tab on the left to see even more information about your motherboard, including details about the chipset and voltages, along with the types of slots included on the board and whether or not they're currently in use.

![The &quot;Motherboard&quot; tab has more specific information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_3.png) 

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

##  Check Your Motherboard Model with HWiNFO64

[HWiNFO64](https://www.fosshub.com/HWiNFO.html) displays most of the same information as Speccy, though it looks fairly different. Downlod and launch it to get started.

 Be careful that any "Download" link you click is actually for HWiNF64, not an advertisement.

 HWiNFO64 can display any of the information about your system, including all of the information available from the sensors. That isn't necessary in this case and will only add to the clutter, so launch HWiNFO64 in "Summary-Only" mode.

 Tick the box that says "Summary-Only," then click "Start."

![Tick the box that says "Summary-Only," then click "Start."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/tick-summary-only-then-click-start.png) 

 You'll see a window that displays everything about your PC's hardware. The left section gives you all of the details about your [CPU](https://facebook-clips.techidaily.com/echoes-of-now-strategies-for-downloading-current-events/), the middle section provides information about your [motherboard](https://tech-savvy.techidaily.com/uniting-giants-how-bzs-games-meet-microsofts-ai-visionaries-tech-dialogue/) and [RAM](https://youtube-web.techidaily.com/ed-2024-approved-unlocking-youtube-success-top-video-strategies-to-explode-views/), and the right-most section focuses on your [GPU](https://android-unlock.techidaily.com/unlock-vivo-s17-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/) and hard drives.

![The HWiNFO64 summary window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/the-summar-window.png) 

 The first few lines will tell you everything you need to know about your motherboard, including the model name, number, BIOS version, and manufacturer.

![The motherboard segment will be near the top-middle of the window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/motherboard-setting.png) 

 If none of those options work, you can always [boot into the BIOS or UEFI](https://apple-account.techidaily.com/in-2024-turning-off-two-factor-authentication-on-iphone-14-pro-max-5-tips-you-must-know-by-drfone-ios/). The motherboard model number and manufacturer are usually plainly displayed somewhere on the BIOS or UEFI main menu.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-channel-your-inner-videographer-to-produce-top-tier-edu-videos/"><u>[New] 2024 Approved Channel Your Inner Videographer to Produce Top-Tier Edu-Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-achieving-profitability-at-half-a-million-viewers-for-2024/"><u>[New] Achieving Profitability at Half a Million Viewers for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-enhancing-online-privacy-youtubes-access-controls/"><u>[Updated] 2024 Approved Enhancing Online Privacy YouTube's Access Controls</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-effortlessly-stream-mp3-to-youtube-with-3-key-steps/"><u>[Updated] In 2024, Effortlessly Stream MP3 to YouTube with 3 Key Steps</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-mastering-the-name-game-for-top-podcast-titles/"><u>[Updated] Mastering the Name Game for Top Podcast Titles</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-capturing-skies-engaging-audiences-learn-to-stream-w-dji-drones/"><u>2024 Approved Capturing Skies, Engaging Audiences Learn to Stream W/ DJI Drones</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-tiktok-and-snapchat-face-off-a-users-perspective-guide/"><u>2024 Approved TikTok & Snapchat Face-Off A User's Perspective Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/fake-android-location-without-rooting-for-your-vivo-s18-pro-drfone-by-drfone-virtual/"><u>Fake Android Location without Rooting For Your Vivo S18 Pro | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/great-value-great-features-in-depth-analysis-of-the-asus-chromebook-flip-c302ca/"><u>Great Value, Great Features: In-Depth Analysis of the Asus Chromebook Flip C302CA</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-restore-a-bricked-lenovo-thinkphone-back-to-operation-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Restore a Bricked Lenovo ThinkPhone Back to Operation | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-mastering-the-transition-moving-your-snapchat-savings-home/"><u>In 2024, Mastering the Transition Moving Your Snapchat Savings Home</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/tech-showdown-exploring-facial-detection-in-iphones-vs-samsungs-for-2024/"><u>Tech Showdown Exploring Facial Detection in iPhones Vs. Samsungs for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/top-ios-psp-gamepads-emulation-2023s-best-list-for-2024/"><u>Top iOS PSP Gamepads Emulation - 2023'S Best List for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/turn-viewers-into-cashflow-your-online-income-plan-for-2024/"><u>Turn Viewers Into Cashflow Your Online Income Plan for 2024</u></a></li>
</ul></div>

