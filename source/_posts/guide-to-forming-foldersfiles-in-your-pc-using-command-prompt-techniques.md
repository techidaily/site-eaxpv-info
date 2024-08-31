---
title: Guide to Forming Folders/Files in Your PC Using Command Prompt Techniques
date: 2024-08-30T16:50:34.942Z
updated: 2024-08-31T16:50:34.942Z
tags:
  - deals
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/52880885497_b08e2e684f_o-4.jpg
---

## Guide to Forming Folders/Files in Your PC Using Command Prompt Techniques

### Quick Links

* [Before You Begin: Copy the Folder Path and Launch Command Prompt](https://desktop-recording.techidaily.com/updated-iphone-filmmaking-101-capturing-time-in-pixels/)
* [Create a Single Folder](https://howto.techidaily.com/troubleshooting-guide-how-to-fix-an-unresponsive-honor-x7b-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/)
* [Create a Folder Inside Another Folder (Subfolder)](https://www.howtogeek.com/how-to-create-folders-and-files-from-windows-command-prompt/#create-a-folder-inside-another-folder-subfolder)
* [Create Multiple Folders at Once](https://apple-account.techidaily.com/how-to-delete-icloud-account-on-apple-iphone-xr-without-password-by-drfone-ios/)
* [Create a File with Command Prompt](https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-infinix-hot-40i-drfone-by-drfone-virtual-android/)

### Key Takeaways

* To create a folder with Command Prompt, use the mkdir command followed by the folder name.
* Mkdir can also be used to create nested folders, multiple folders simultaneously, or a combination of both.
* If you want to create a file, enter type in Command Prompt, followed by nul > filename.ext, replacing ".ext" with the file type you want.

 Whether you’re looking to create a script, make several folders at once, or you simply prefer command-line methods over graphical ones, it’s quick and easy to make folders or files using Command Prompt. We’ll show you how to do it on your Windows 11 or Windows 10 PC.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Before You Begin: Copy the Folder Path and Launch Command Prompt

 To use the following methods, you must first copy the path of the folder where you’ll create new folders or files, and then run the Command Prompt utility.

 To copy a folder’s full path, [launch File Explorer](https://pokemon-go-android.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-realme-c67-4g-drfone-by-drfone-virtual-android/) using Windows+E and find your folder. Hold down the Shift key on your keyboard, right-click your folder, and choose "Copy as Path."

!['Copy as Path' highlighted for a folder on a Windows PC.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-copy-folder-path-windows.jpg) 

 To [open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/), click the Start button, search for **command prompt**, then click the relevant result or press Enter. While making folders, if you encounter an error, [run Command Prompt as an admin](https://instagram-videos.techidaily.com/updated-2024-approved-unlocking-instagram-potential-a-comprehensible-guide/) by right-clicking the utility and choosing "Run as Administrator." Make sure to select "Yes" in the User Account Control prompt.

!['Run as Administrator' highlighted for Command Prompt in Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-open-command-prompt-as-admin.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 After opening Command Prompt, type **cd**, press Spacebar, paste the folder path you copied by pressing Ctrl+V, and press Enter. This [makes your chosen folder the current working directory](https://extra-information.techidaily.com/quick-and-easy-iphone-burst-techniques/) in the tool. Each command you run will perform the specified action in this directory.

!['cd' command typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-change-current-directory-command-prompt.jpg) 

##  Create a Single Folder

 To make a single folder, type the following command, replacing "FolderName" with the name you want to assign to your folder. Then, press Enter.

mkdir FolderName

 For example, to make a folder named "Mahesh", use the following command:

mkdir Mahesh

![Create a single folder from Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-create-single-folder-cmd.jpg) 

 To create a folder that has spaces in its name, enclose the name with double quotes like this:

mkdir “Mahesh Makvana”

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Create a Folder Inside Another Folder (Subfolder)

 One way to make a folder inside another folder is to make that other folder the current working directory. To do that, type **cd**, press Spacebar, enter the name of the folder in which you want to create a new folder, and press Enter. Then, type the following command, replace "MyFolder" with the name you want to give to your new folder, and press Enter.

mkdir MyFolder

 Another way to create a folder inside a folder is to specify the other folder right in the mkdir command itself. For example, if you have a subfolder named "Photos" and you want to create a new folder named "Personal" inside it, use the following command:

mkdir Photos\Personal

![Create a subfolder using Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-create-subfolder-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->
##  Create Multiple Folders at Once

 To [make several folders at once](https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-motorola-razr-40-ultra-drfone-by-drfone-virtual-android/), add the required folder names to the mkdir command.

 For example, to create three separate folders named Documents, Photos, and Videos, use the following command:

mkdir Documents Photos Videos

![Create multiple folders with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/6-create-multiple-folders-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Make sure to enclose the folder name with double quotes if its name has spaces.

##  Create a File with Command Prompt

 Command Prompt allows you to create empty files, which you can then use with appropriate apps. The syntax for creating a new file is as follows:

type nul > name.ext

 Here, "name" is the name of the file you want to create and "ext" is the [extension of the file](https://twitter-videos.techidaily.com/updated-the-dos-and-donts-of-youtube-videos-on-twitter-for-2024/).

 For example, to make a text file named document.txt, you’ll use the following command:

type nul > document.txt

![Create a file with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/7-create-file-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
 To create a text file and add some actual text to it, use the following command. Replace "Welcome to How-To Geek" with the text you want to add and "howtogeek" with the name you want to use for the file.

echo Welcome to How-To Geek > howtogeek.txt

 When you open howtogeek.txt in a text editor you'll find it has "Welcome to How-To Geek" written in it. 

---

 And that’s how you make folders and files without using graphical tools on your Windows machine.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-explore-beyond-youtube-with-these-top-5-video-tools/"><u>[New] 2024 Approved  Explore Beyond Youtube with These Top 5 Video Tools</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-green-screen-ease-crafting-effective-youtube-ctas/"><u>[New] 2024 Approved  Green Screen Ease  Crafting Effective YouTube CTAs</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-secure-youtube-channels-audible-content/"><u>[New] 2024 Approved  How to Secure YouTube Channels' Audible Content</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-beyond-boundaries-channel-youtube-for-exciting-green-screens-for-2024/"><u>[New] Beyond Boundaries  Channel Youtube for Exciting Green Screens for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-from-unconfident-to-impactful-embracing-youtube-blogging-for-2024/"><u>[New] From Unconfident to Impactful  Embracing YouTube Blogging for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-streamlined-multitasking-in-safari-with-pip/"><u>[New] In 2024, Streamlined Multitasking in Safari with PIP</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-nextgen-cameras-top-picks-for-professional-videography-2024/"><u>[New] NextGen Cameras  Top Picks for Professional Videography 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/nline-havens-for-sponsorship-initiatives-on-youtube-for-2024/"><u>[New] Online Havens for Sponsorship Initiatives on YouTube for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-streamlined-process-to-download-parts-from-youtube-videos/"><u>[New] Streamlined Process to Download Parts From YouTube Videos</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-7-insider-tips-to-make-money-quickly-on-youtube-shorts/"><u>[Updated] 2024 Approved  7 Insider Tips to Make Money Quickly on YouTube Shorts</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-clear-up-audio-in-youtube-a-step-by-step-guide/"><u>[Updated] 2024 Approved  Clear Up Audio in YouTube  A Step-by-Step Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-drive-more-watch-time-not-churn-discover-the-top-6-techniques-on-youtube/"><u>[Updated] 2024 Approved  Drive More Watch Time, Not Churn  Discover the Top 6 Techniques on YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-insta-unfollow-a-path-towards-a-lasting-account-discontinuation/"><u>[Updated] 2024 Approved  Insta Unfollow  A Path Towards a Lasting Account Discontinuation</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-brand-makeover-made-easy-revel-in-our-array-of-over-50-free-online-promotional-artwork/"><u>[Updated] Brand Makeover Made Easy  Revel in Our Array of over 50 Free Online Promotional Artwork!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-cease-non-filtered-youtube-video-trail-for-2024/"><u>[Updated] Cease Non-Filtered YouTube Video Trail for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-charting-the-course-of-monetization-for-creator-economy-on-youtubeshorts-for-2024/"><u>[Updated] Charting the Course of Monetization for Creator Economy on YouTubeshorts for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-cultivate-creativity-youtubes-top-inspirational-videos-for-2024/"><u>[Updated] Cultivate Creativity  YouTube's Top Inspirational Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-free-youtube-sound-ripper-collection-top-17-extractors-revealed/"><u>[Updated] Free YouTube Sound Ripper Collection  Top 17 Extractors Revealed</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-getting-to-grips-with-bandicam-your-guide-through-2023s-updates-for-2024/"><u>[Updated] Getting to Grips with Bandicam – Your Guide Through 2023'S Updates for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-clip-concoction-station/"><u>[Updated] In 2024, Clip Concoction Station</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-film-resource-highlights-where-to-start-your-search/"><u>[Updated] In 2024, Free Film Resource Highlights  Where to Start Your Search</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-guide-to-embedding-on-screen-text-on-youtube-clips/"><u>[Updated] In 2024, Guide to Embedding On-Screen Text on YouTube Clips</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-top-5-youtube-video-editor-alternatives/"><u>[Updated] In 2024, Top 5 YouTube Video Editor Alternatives</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-maximizing-online-presence-through-youtube-ad-and-image-marketing/"><u>[Updated] Maximizing Online Presence Through YouTube Ad & Image Marketing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-premium-7-video-gear-ideas-for-captivating-vloggers/"><u>[Updated] Premium 7 Video Gear Ideas for Captivating Vloggers</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-probing-financial-depths-an-analysis-of-mr-beasts-wealth/"><u>[Updated] Probing Financial Depths  An Analysis of Mr. Beast's Wealth</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-quick-guide-on-converting-videos-into-dynamic-gifs-online/"><u>[Updated] Quick Guide on Converting Videos Into Dynamic Gifs Online</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-revolutionary-ios-gaming-apples-best-vr-apps/"><u>[Updated] Revolutionary iOS Gaming  Apple's Best VR Apps</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-spreading-beauty-wisdom-setting-up-your-vloggers-virtual-space/"><u>[Updated] Spreading Beauty Wisdom  Setting Up Your Vlogger's Virtual Space</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-the-art-of-disregarding-harmful-youtube-comments/"><u>[Updated] The Art of Disregarding Harmful YouTube Comments</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-tiktok-and-youtube-shorts-comparison-for-individual-social-media-users/"><u>[Updated] TikTok & YouTube Shorts Comparison for Individual Social Media Users</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-compreenhensive-guide-to-selecting-and-cultivating-valheim-seeds/"><u>2024 Approved  Compreenhensive Guide to Selecting & Cultivating Valheim Seeds</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-maximize-android-gaming-with-funimate-apk-download/"><u>2024 Approved  Maximize Android Gaming with Funimate APK Download</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-stabilizing-your-stream-avoid-dropped-frame-errors/"><u>2024 Approved  Stabilizing Your Stream  Avoid Dropped Frame Errors</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/2024-approved-youtubes-flawless-beauty-masterclass-skincare-hairdos-and-cosmetics/"><u>2024 Approved  YouTube's Flawless Beauty Masterclass  Skincare, Hairdos & Cosmetics</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722974985403-download-free-gigabyte-audio-drivers-today/"><u>Download Free Gigabyte Audio Drivers Today</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-infinix-hot-30-5g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Infinix Hot 30 5G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-nokia-g22-by-drfone-android/"><u>In 2024, A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Nokia G22</u></a></li>
<li><a href="https://win-answers.techidaily.com/mastering-access-violation-in-civil-service-exam-2024-what-you-need-to-know-about-civ-6/"><u>Mastering 'Access Violation in Civil Service Exam 2024': What You Need To Know About CIV-6</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/optimizing-your-music-library-transitioning-from-spotify-to-youtube-music-for-2024/"><u>Optimizing Your Music Library  Transitioning From Spotify To YouTube Music for 2024</u></a></li>
<li><a href="https://apple-account.techidaily.com/protecting-your-privacy-how-to-remove-apple-id-from-iphone-15-pro-max-by-drfone-ios/"><u>Protecting Your Privacy How To Remove Apple ID From iPhone 15 Pro Max</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/seamless-techniques-for-swift-removal-of-your-youtube-comments-for-2024/"><u>Seamless Techniques for Swift Removal of Your Youtube Comments for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-experts-guide-to-360-video-conversion-and-youtube-sharing-for-2024/"><u>The Expert's Guide to 360 Video Conversion and YouTube Sharing for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/the-gamers-roadmap-navigating-a-successful-youtube-channel-for-2024/"><u>The Gamers' Roadmap  Navigating a Successful YouTube Channel for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/unlock-creativity-in-youtube-production-an-intro-to-wmm-for-2024/"><u>Unlock Creativity in YouTube Production  An Intro to WMM for 2024</u></a></li>
</ul></div>
