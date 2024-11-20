---
title: "Discover New Alternatives: Top Substitutes for Linux's Popular Deprecated Terminal Utility"
date: 2024-11-17T00:58:16.004Z
updated: 2024-11-19T16:43:14.897Z
tags:
  - desktop
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e12562333e85045ab9221a99e913b83b793150ee785e5f59fee7c9f18bec3976.png
---

## Discover New Alternatives: Top Substitutes for Linux's Popular Deprecated Terminal Utility

### Key Takeaways

* It's time to say goodbye to neofetch, as the developer has abandoned the project due to farming commitments.
* Fastfetch, macchina, NerdFetch, and others are viable alternatives offering new features and better maintenance.

 If you're a Linux user, you might know about neofetch, a popular command-line tool that shows system information in the terminal. Many users love it because it's customizable and looks great. Unfortunately, the developer has discontinued the project, so it's time to say goodbye to this helpful tool.

##  Is neofetch Dead?

 Yes, it's true—the neofetch project has been officially declared dead. Although the developer archived the project on April 26th, 2024, the last update was three years ago. The developer left a note in the README file stating he had taken up farming, which is the only explanation for the archiving.

 neofetch's abandonment doesn't mean it will disappear immediately. Since it's a Bash script, it will likely continue to work for a long time until the applications it relies on become outdated.

 You can continue using neofetch if you wish, but be aware that it is no longer maintained or updated. Using outdated software can pose security risks, so I strongly advise against relying on expired or out-of-date tools. Instead, consider exploring alternative, actively supported options.

##  Alternatives to neofetch

 neofetch's abandonment might be sad, but it's not the end. Explore alternatives like Fastfetch, macchina, and others, which offer new features and better maintenance.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886015/19272" target="_top" id="1886015">
  <img src="//a.impactradius-go.com/display-ad/19272-1886015" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886015/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  Fastfetch

[Fastfetch](https://github.com/fastfetch-cli/fastfetch) is a faster, lighter, and up-to-date alternative to neofetch. It is written mainly in C and compatible with various platforms like macOS, Linux, and Windows. Fastfetch is actively maintained with community support and regular updates. Furthermore, it is easy to install and provides more information than neofetch, including desktop environment, window theme, and font.

 Fastfetch is not available by default in Debian or Ubuntu's software repositories. You can manually install its more recent version by adding a PPA repository to Ubuntu.

sudo add-apt-repository ppa:zhangsongcui3371/fastfetch

 Next, update your system's package list and install Fastfetch.

sudo apt update && sudo apt install fastfetch

 To get system information using Fastfetch, run:

fastfetch

![Linux terminal displaying system information using fastfetch tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-displaying-system-information-using-fastfetch-tool.png) 

 You can install Fastfetch on Fedora, CentOS, and RHEL by running this command:

sudo yum install fastfetch

 If you're an Arch Linux user, use this:

sudo pacman -S fastfetch

 Fastfetch displays your local IP address as well, so be careful when sharing your Fastfetch information screenshots with others.

###  macchina

[macchina](https://github.com/Macchina-CLI/macchina) is a quick and easy tool for gathering information about your system. It's a lightweight alternative to neofetch that's all about speed and simplicity. It's designed with customization in mind, allowing you to tailor your system information display to your preferences.

 macchina has a theming system that lets you customize its appearance. You can create several themes and shift between them easily without affecting the main configuration.

 Moreover, you have two options to get started with macchina: either download the pre-built binary from the [Releases page](https://github.com/Macchina-CLI/macchina/releases) and use it directly, or install it using Cargo, Rust's package manager.

 If you choose to install using Cargo, first install Cargo on your Linux PC. To install Cargo on Ubuntu, for instance, run:

sudo apt install cargo

 Next, run the following command to install macchina:

cargo install macchina

 Once installed, you can display your system information by running the **\~/.cargo/bin/macchina** command with your desired flags. However, this is not a practical approach for getting system information using macchina.

 To avoid typing the full path to the macchina executable every time, you can add its installation directory to the PATH environment variable. This allows you to run macchina from any directory in your terminal.

 You can do this by editing your user's profile file. Simply open the file with gedit:

gedit ~/.profile 

 Next, add the ".cargo/bin" directory to your PATH.

![Adding macchina directory path in user profile file.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/adding-macchina-directory-path-in-user-profile-file.png) 

 Now, you can get system information directly using:

macchina

![Linux terminal window showing system information by executing macchina](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-macchina.png) 

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If you are an Arch Linux user, you can also install macchina [from the AUR using Yay](https://win-answers.techidaily.com/resolved-overcoming-ies-webpage-display-issues/).

yay -S macchina

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  screenFetch

[screenFetch](https://github.com/KittyKatt/screenFetch) is another handy terminal utility just like neofetch that displays system information in a terminal. In fact, screenFetch is older than neofetch. While it may not have the same level of visual appeal as some of the newer options, screenFetch is a reliable and well-established tool that gets the job done.

 By running the **screenfetch** command, you can quickly display a snapshot of your system’s current state, including OS, kernel version, uptime, package counts, and more. You can also screenshot the displayed output using **screenfetch -s**.

 screenFetch is available in the default Ubuntu repositories. To get it, run:

sudo apt install screenfetch

![Linux terminal window showing system information by executing screenfetch](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-system-information-by-executing-screenfetch.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 screenFetch also allows you to display a different ASCII art logo than the default one detected by screenFetch. You can simply specify a distribution name with the **\-A 'distribution\_name'** option like this:

screenfetch -A 'Debian'

![Linux terminal window showing debian ASCII art logo along with system information by using screenfetch tool](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-window-showing-debian-ascii-art-logo-along-with-system-information-by-using-screenfetch-tool.png) 

 To get screenFetch on RHEL/CentOS/Fedora, run:

sudo dnf install screenfetch 

 On Arch Linux:

sudo pacman -S screenfetch

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389">
  <img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

###  NerdFetch

[NerdFetch](https://github.com/ThatOneCalculator/NerdFetch) is a POSIX-compliant fetch script that displays system information in a visually appealing format in the terminal. It utilizes [Nerd fonts](https://www.nerdfonts.com/font-downloads) to enhance the visual presentation of system information.

 Like other system information tools, NerdFetch also fetches and displays details such as your operating system name, version, and others. However, NerdFetch sets itself apart with its high level of customization, offering three distinct font modes for displaying system information, such as Cozette, Phosphor, and Emojis. You can switch between different fonts with the command-line options -c, -p, and -e.

 To install NerdFetch, simply download its script from the GitHub repository using [curl](https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-mix-fold-3-frp-locks-by-drfone-android/):

sudo curl -fsSL https://raw.githubusercontent.com/ThatOneCalculator/NerdFetch/main/nerdfetch -o /usr/bin/nerdfetch

 After downloading, you need to make the script executable with:

sudo chmod +x /usr/bin/nerdfetch

 To display your system information, run:

nerdfetch

![Linux terminal showing system information in three different modes by using nerdfetch with flags](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/linux-terminal-showing-system-information-in-three-different-modes-by-using-nerdfetch-with-flags.png) 

 Arch users can get NerdFetch using any AUR helper like Yay or Paru:

yay -S nerdfetch

##  Customize Your Linux System for a Better Experience

 Customizing your Linux system can be a fun and rewarding experience. Whether you want to create your own Linux distribution or tweak your existing setup, there are numerous ways to make your desktop your own. For example, you can personalize your existing Linux installation by changing desktop themes and adding new icons and fonts. Furthermore, you can also use [Conky](https://facebook-video-content.techidaily.com/new-2024-approved-the-social-media-economy-maximizing-your-facebook-revenue/) to customize your widgets that display different system information.

 You can also use [Ubuntu Tweaks](https://youtube-web.techidaily.com/nfluencer-collaborations-impacting-video-view-counts-for-2024/) to customize your Ubuntu system easily. It lets you change settings and customize your Linux desktop to your liking.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-to-link-youtube-to-tiktok-complete-guide/"><u>[New] 2024 Approved How to Link YouTube to TikTok? [Complete Guide]</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-how-to-double-down-on-your-youtube-success-in-a-month-for-2024/"><u>[New] How to Double Down on Your YouTube Success in a Month for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-free-and-uncomplicated-youtube-image-extractor-tools-reviewed/"><u>[New] In 2024, Free and Uncomplicated YouTube Image Extractor Tools Reviewed</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-from-budget-channels-to-big-brands-youtube-sponsorships-demystified/"><u>[New] In 2024, From Budget Channels to Big Brands YouTube Sponsorships Demystified</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-how-to-effectively-archive-snapchat-videos-on-mobile-phones/"><u>[New] In 2024, How to Effectively Archive Snapchat Videos on Mobile Phones</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-hitch-youtube-sounds-into-imovie-tracks-swiftly/"><u>[Updated] 2024 Approved Hitch YouTube Sounds Into iMovie Tracks Swiftly</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-football-film-breakdown-premier-insights-on-youtube-for-2024/"><u>[Updated] Football Film Breakdown Premier Insights on YouTube for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-ingredients-to-inspiration-cooking-videos-for-2024/"><u>[Updated] From Ingredients to Inspiration Cooking Videos for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-how-to-create-youtube-channel-in-mobile-with-ease-personal-and-business-for-2024/"><u>[Updated] How to Create YouTube Channel in Mobile with Ease [Personal & Business] for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-maximize-engagement-mastering-sound-editing-for-youtube/"><u>[Updated] In 2024, Maximize Engagement Mastering Sound Editing for YouTube</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-no-cost-memes-made-simple-our-meme-kit/"><u>[Updated] No-Cost Memes Made Simple Our Meme Kit</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-the-ultimate-trifecta-for-instagram-video-borders/"><u>2024 Approved The Ultimate Trifecta for Instagram Video Borders</u></a></li>
<li><a href="https://tech-hub.techidaily.com/best-online-ai-prompt-design-programs-ranked-top-5-picks/"><u>Best Online AI Prompt Design Programs Ranked - Top 5 Picks</u></a></li>
<li><a href="https://hardware-help.techidaily.com/brother-l2700dw-driver-setup-and-download-instructions-for-windows-pcs/"><u>Brother L2700DW Driver Setup & Download Instructions for Windows PCs</u></a></li>
<li><a href="https://win-blog.techidaily.com/conquer-technical-terrors-a-guide-to-preventing-dragon-age-origins-crashes-on-windows-10/"><u>Conquer Technical Terrors: A Guide to Preventing Dragon Age: Origins Crashes on Windows 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1726225248906-m1v-avi/"><u>M1V 포토로 가드를 AVI로 바꾸기 – 컴퓨터에서 무료 구현</u></a></li>
<li><a href="https://tech-revival.techidaily.com/whats-next-after-gpt-4-speculations-surrounding-the-upcoming-gpt-5-release/"><u>What's Next After GPT-4? Speculations Surrounding the Upcoming GPT-5 Release</u></a></li>
</ul></div>

