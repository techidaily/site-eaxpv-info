---
title: "Step-by-Step Guide: Setting Up & Operating the Linux Bash Terminal in Windows 10"
date: 2024-08-30T16:50:11.588Z
updated: 2024-08-31T16:50:11.588Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e31aaa74ff016883ab8f84feb3b9453dbf2ea0039f672d3d44453dbbd8a5a231.jpg
---

## Step-by-Step Guide: Setting Up & Operating the Linux Bash Terminal in Windows 10

### Quick Links

* [What You Need to Know About Windows 10's Bash Shell](https://hardware-tips.techidaily.com/toms-tech-corner-the-ultimate-guide-to-computer-components/)
* [How to Install Bash on Windows 10](https://android-unlock.techidaily.com/in-2024-the-ultimate-guide-to-samsung-galaxy-a54-5g-pattern-lock-screen-everything-you-need-to-know-by-drfone-android/)
* [How to Use The Bash Shell and Install Linux Software](https://remote-screen-capture.techidaily.com/new-leveraging-streamlabs-obs-for-engaging-live-streams-for-2024/)
* [Install the Ubuntu Font for a True Ubuntu Experience](https://some-approaches.techidaily.com/updated-toontech-complete-insight-2024-edition/)
* [Use the Ubuntu Monospace Font in the Console](https://facebook-record-videos.techidaily.com/new-in-2024-diy-youtube-openers-technique-one-and-technique-two/)
* [Use the Ubuntu Monospace Font in the Terminal](https://screen-video-capture.techidaily.com/in-2024-picking-the-right-software-bandicam-versus-camtasia/)

### Key Takeaways

 First, enable the Windows Subsystem for Linux (WSL) from the Features window or via the "wsl --install" command. After rebooting your PC, install Ubuntu or any other Linux distribution of your choice from the Microsoft Store.

 The Windows Subsystem for Linux, introduced in the [Anniversary Update](https://twitter-videos.techidaily.com/2024-approved-clear-obstacle-youtube-tweets-on-google-chrome/), became a stable feature in the [Fall Creators Update](https://phone-solutions.techidaily.com/does-samsung-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/). You can now run Ubuntu, openSUSE, a remix of Fedora, and plenty of others on Windows, with more Linux distributions coming soon.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2027209/17108" target="_top" id="2027209"><img src="//a.impactradius-go.com/display-ad/17108-2027209" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2027209/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  What You Need to Know About Windows 10's Bash Shell

###  How Windows Subsystem for Linux 1 (WSL1) Works

 Windows 10 offers a full Windows Subsystem intended for Linux (WSL) for running Linux software. This isn't a [virtual machine](https://remote-screen-capture.techidaily.com/2024-approved-essential-guide-video-recording-with-vlc/), a container, or Linux software compiled for Windows (like [Cygwin](https://tech-savvy.techidaily.com/global-network-ai-versus-closed-system-deployment/)). It's based on Microsoft's abandoned Project Astoria work for running Android apps on Windows.

 Think of it as the opposite of [Wine](https://some-guidance.techidaily.com/updated-ultimate-list-best-no-cost-lut-downloads/). While Wine allows you to run Windows applications directly on Linux, the Windows Subsystem for Linux allows you to run Linux applications directly on Windows.

 Microsoft worked with Canonical to offer a full Ubuntu-based Bash shell environment that runs atop this subsystem. Technically, this isn't Linux at all. Linux is the underlying operating system kernel, and that isn't available here. Instead, this allows you to run the Bash shell and the exact same binaries you'd normally run on Ubuntu Linux. Free software purists often argue the average Linux operating system [should be called "GNU/Linux"](https://tiktok-video-recordings.techidaily.com/perfecting-your-digital-doppelganger-a-complete-guide-to-cloning-oneself-on-tiktok-for-2024/) because it's really a lot of GNU software running on the Linux kernel. The Bash shell you'll get is really just all those GNU utilities and other software.

 While this feature was originally called "Bash on Ubuntu on Windows," it also allows you to [run Zsh and other command-line shells](https://extra-support.techidaily.com/2024-approved-master-iphone-cams-with-these-hacks/). It now supports other Linux distributions, too. You can choose openSUSE Leap or SUSE Enterprise Server instead of Ubuntu, and there is a remix of Fedora available.

 There are some limitations here. It won't officially work with [graphical Linux desktop applications](https://instagram-video-recordings.techidaily.com/updated-2024-approved-mastering-instagram-profit-the-ultimate-strategy-blueprint/). Not every command-line application works, either, as the feature isn't perfect.

<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  How Windows Subsystem for Linux 2 (WSL2) Works

 Windows Subsystem for Linux 2 (WSL2) is designed to provide the exact same user experience as its predecessor, but the similarities mostly end there.

 WSL2 runs a full Linux Kernel in [an extremely efficient virtual machine.](https://facebook-record-videos.techidaily.com/updated-the-infographic-index-youtubes-surprising-stat-treasury-2017/) Just like WSL1, WSL2 allows you use a range of different Linux Distros including, Ubuntu, Debian, Kali, openSUSE, Fedora, and others. That also means that most any Linux application, package, or command will work without an issue.

 WSL2 supports GUI applications on Windows 11.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
##  How to Install Bash on Windows 10

 This feature doesn't work on the 32-bit version of Windows 10, so [ensure you're using the 64-bit version of Windows](https://extra-tips.techidaily.com/acclaimed-websites-for-google-pixel-tonal-sounds-for-2024/). It's time to [switch to the 64-bit version of Windows 10](https://facebook-record-videos.techidaily.com/understanding-filmoras-creative-certification-protocol-for-2024/) if you're still using the 32-bit version, anyway.

 Assuming you have 64-bit Windows, to get started, head to Control Panel > Programs > Turn Windows Features On Or Off. Enable the "Windows Subsystem for Linux" option in the list, and then click the "OK" button.

![Open up the Windows Features menu, scroll down until you find &quot;Windows Subsystem for Linux,&quot; then tick the box and click &quot;OK.&quot;](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985001e7f37.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
 Click "Restart now" when you're prompted to restart your computer. The feature won't work until you reboot.

 Alternatively, you can also install it using PowerShell. [Launch PowerShell as an Administrator](https://win11.techidaily.com/a-guide-to-quickly-opens-sticky-notes-in-windows-11/), then enter:

wsl --install

 It'll take a few minutes to download and install all of the required components --- after it does, you need to restart your computer.

![PowerShell running WSL install command successfully.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/WSL-install.png) 

 After your computer restarts, open the Microsoft Store from the Start menu, and search for "Linux" in the store.

![Linux distros available on the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/ms-store-linux.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 You'll see a list of every Linux distribution currently available in the Windows Store.This includes [Ubuntu, openSUSE Leap, and openSUSE Enterprise](https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-nokia-c300-drfone-by-drfone-virtual-android/), Debian, Kali, and others. You can even find a few remixes of Fedora, though there isn't an official version available as of November 2023.

 If you want a specific distro, search for that rather than "Linux." You'll get better results.

 To install a Linux distribution, click it, and then click the "Get" or "Install" button to install it like any other Store application.

 If you're not sure which Linux environment to install, we recommend Ubuntu. This popular Linux distribution was previously the only option available, but other Linux systems are now available for people who have more specific needs.

![Installing Debian through the Microsoft Store.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/installing-debian.png) 

 You can also install multiple Linux distributions and they'll each get their own unique shortcuts. You can even run multiple different Linux distributions at a time in different windows.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  How to Use The Bash Shell and Install Linux Software

 You now have a full command-line bash shell through Ubuntu, or whichever other Linux distribution you installed.

 Because they're the same binaries, you can [use Ubuntu's apt or apt-get command](https://iphone-unlock.techidaily.com/8-safe-and-effective-methods-to-unlock-your-iphone-12-mini-without-a-passcode-drfone-by-drfone-ios/) to install software from Ubuntu's repositories if you're using Ubuntu. Just use whatever command you'd normally use on that Linux distribution. You'll have access to all the Linux command line software out there, although some applications may not yet work perfectly.

 To open the Linux environment you installed, just open the Start menu and search for whatever distribution you installed. For example, if you installed Ubuntu, launch the Ubuntu shortcut.

 You can pin this application shortcut to your Start menu, taskbar, or desktop for easier access.

![Searching for "Ubuntu" in the Start Menu.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/ubuntu-search.png) 

 The first time you launch the Linux environment, you're be prompted to enter a UNIX username and password. These don't have to match your Windows username and password, but will be used within the Linux environment.

 For example, if you enter "bob" and "letmein" as your credentials, your username in the Linux environment will be "bob" and the password you use inside the Linux environment will be "letmein" --- no matter what your Windows username and password are.

![Enter a username and password for your Linux distro.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985a5c26989.png) 

 You can launch your installed Linux environment by running the `wsl` command. If you have multiple Linux distributions installed, you can [choose the default Linux environment](https://howto.techidaily.com/8-ultimate-fixes-for-google-play-your-infinix-note-30-vip-isnt-compatible-drfone-by-drfone-fix-android-problems-fix-android-problems/) this command launches.

 If you have Ubuntu installed, you can also run the `ubuntu` command to install it. For openSUSE Leap 42, use `opensuse-42` . For SUSE Linux Enterprise Sever 12, use `sles-12` . These commands are listed on each Linux distribution's page on the Windows Store.

 You can still launch your default Linux environment by running the `bash` command, but Microsoft says this is deprecated. This means the `bash` command may stop functioning in the future.

![Running &quot;bash&quot; in the Command Prompt will launch your default Linux environment.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985b14e9795.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394"><img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 If you're experienced using a Bash shell on Linux, Mac OS X, or other platforms, you'll be right at home.

 On Ubuntu, you need to prefix a command with `sudo` to [run it with root permissions](https://extra-support.techidaily.com/maximize-your-listening-experience-ios-podcast-mastery-for-2024/). The "root" user on UNIX platforms has full system access, like the "Administrator" user on Windows. Your Windows file system is located at `/mnt/c` in the Bash shell environment.

 Use the same Linux terminal commands you'd use to get around. If you're used to the standard Windows Command Prompt with its DOS commands, here are a few basic commands common to both Bash and Windows:

* Change Directory: `cd` in Bash, `cd` or `chdir` in DOS
* List Contents of Directory: `ls` in Bash, `dir` in DOS
* Move or Rename a File: `mv` in Bash, `move` and `rename` in DOS
* Copy a File: `cp` in Bash, `copy` in DOS
* Delete a File: `rm` in Bash, `del` or `erase` in DOS
* Create a Directory: `mkdir` in Bash, `mkdir` in DOS
* Use a Text Editor: `vi` or `nano` in Bash, `edit` in DOS

 It's important to remember that, unlike Windows, the Bash shell and its Linux-imitating environment are case-sensitive. In other words, "File.txt" with a capital letter is different from "file.txt" without a capital.

 For more instructions, consult [our beginner's guide to the Linux command-line](https://facebook-clips.techidaily.com/downloading-facebook-gifs-pc-android-and-ios-guide/) and other similar introductions to the Bash shell, Ubuntu command line, and Linux terminal online.

![The command &quot;ls&quot; run in the C:\ directory to list files and folders.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985d46b3c57.png) 

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->
 You'll need to [use the apt command](https://screen-sharing-recording.techidaily.com/updated-best-practices-in-winning-tv-recording-with-software/) to install and update the Ubuntu environment's software. Be sure to prefix these commands with `sudo` , which makes them run as root--the Linux equivalent of Administrator. Here are the apt-get commands you'll need to know:

* Download Updated Information About Available Packages: `sudo apt update`
* Install an Application Package: `sudo apt install packagename` (Replace "packagename" with the package's name.)
* Uninstall an Application Package: `sudo apt remove packagename` (Replace "packagename" with the package's name.)
* Search for Available Packages: `sudo apt search word` (Replace "word" with a word you want to search package names and descriptions for.)
* Download and Install the Latest Versions of Your Installed Packages: `sudo apt upgrade`

 If you installed a SUSE Linux distribution, you can use the [zypper command](https://doc.opensuse.org/documentation/leap/reference/html/book-reference/cha-sw-cl.html#sec-zypper) to install software instead.

 After you've downloaded and installed an application, you can type its name at the prompt, and then press Enter to run it. Check that particular application's documentation for more details.

![Installing GNU Compiler Collection with apt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985e7d80a6b.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
##  Install the Ubuntu Font for a True Ubuntu Experience

 If you want a more accurate Ubuntu experience on Windows 10, you can also install the Ubuntu fonts and enable them in the terminal. You don't have to do this, as the default Windows command prompt font looks pretty good to us, but it's an option.

 Here's what it looks like:

![The default font, Consolas.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a9864cb2035c.png) 

 To install the font, first download the [Ubuntu Font Family](http://font.ubuntu.com/) from Ubuntu's website. Open the downloaded .zip file and locate the "UbuntuMono-R.ttf" file. This is the Ubuntu monospace font, which is the only one used in the terminal. It's the only font you need to install.

![Open the font ZIP file, then double-click the font you want to preview or install.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985eba01a04.png) 

 Double-click the "UbuntuMono-R.ttf" file and you'll see a preview of the font. Click "Install" to install it to your system.

![Click &quot;Install&quot; near the top if you want to use the font.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a985ee273570.png) 

##  Use the Ubuntu Monospace Font in the Console

 To make the Ubuntu monospace font become an option in the console, you'll need to add a setting to [the Windows registry](https://facebook-record-videos.techidaily.com/new-economical-mic-options-for-youtube-vloggers-for-2024/).

 Open a registry editor by pressing Windows+R on your keyboard, typing `regedit` , and then pressing Enter. Navigate to the following key or copy and paste it into the Registry Editor's address bar:

HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows NT\CurrentVersion\Console\TrueTypeFont

![Navigate to the &quot;TrueTypeFont&quot; key.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a986517b1bec.png) 

 Right-click in the right pane and select New > String Value. Name the new value `000` .

 Double-click the "000" string you just created, and then enter `Ubuntu Mono` as its value data.

![Create a new string named &quot;000&quot;, then set the value to &quot;Ubuntu Mono&quot;.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a98652a926c4.png) 

 Launch an Ubuntu window, right-click the title bar, and then select the "Properties" command. Click the "Font" tab, and then select "Ubuntu Mono" in the font list.

![Right-click the title bar of the terminal application you're using, go to &quot;Properties,&quot; then click &quot;Font.&quot; Select &quot;Ubuntu Mono&quot; from the list.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2018/03/img_5a986560320a0.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
##  Use the Ubuntu Monospace Font in the Terminal

 If you're using the Windows Terminal—and you should be, it is [a big improvement in most ways](https://video-screen-grab.techidaily.com/updated-2024-approved-effortless-screen-saving-on-android-devices/)—changing fonts is easier. After you've installed the Ubuntu font, open up the Terminal, click the small downward facing arrow, and select "Settings."

![Open the Terminal Settings.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/open-settings-terminal.png) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
 Open to Defaults > Appearance, then select "Ubuntu Mono" from the list of available fonts.

 The Terminal automatically expands or collapses the labels in the left sidebar depending on the size of your window, much like the Settings app does. You may not see the "Default" text label depending on the size of your window.

![Enable the Ubuntu Mono font.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/11/font-ubuntu-mono.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37701530&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6fe0c81e3f9438db11ebbfba6c5ce460/products/copy_cbLogo_with_text_blue.png" border="0">CalendarBudget - Monthly subscription membership to CalendarBudget via web browser or mobile app. Support included. </a>
<!-- affiliate ads end -->
 Remember: software you install in the Bash shell is restricted to the Bash shell. You can access these programs from the Command Prompt, PowerShell, or elsewhere in Windows, but only if you [run the bash -c command](https://vp-tips.techidaily.com/building-a-brand-with-captivating-haul-videos-and-edits/).

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


