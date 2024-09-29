---
title: "Step-by-Step Process: Finding the Motherboard Serial in Windows Computers"
date: 2024-08-30T16:50:14.034Z
updated: 2024-08-31T16:50:14.034Z
tags:
  - deals
categories:
  - tech
thumbnail: https://thmb.techidaily.com/a398f18ec0de1a37637c260e06464220af2d995e8ad26b4b76b8430c1741deb5.jpg
---

## Step-by-Step Process: Finding the Motherboard Serial in Windows Computers

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

 The run the following command to get information about your motherboard: 

Get-CimInstance -ClassName Win32_baseboard

![The information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/12/2-baseboard-deets.png) 

 Depending on what information is available, you may or may not get an actual model number. However, you'll almost always get something in the "Product" field that will be enough to figure out what motherboard is in your PC. 

##  Check Your Model Number from the Command Prompt (or PowerShell) with WMIC

 WMIC is technically deprecated but still works.

 If you're comfortable using the Command Prompt (or PowerShell, where these commands also work), you can easily check a variety of motherboard and hardware stats using the handy Windows Management Instrumentation Command-line (WMIC)—a command-line interface for Microsoft's powerful WMI tool.

 With the WMIC, you can entry the query baseboard to check motherboard stats, and then use additional modifiers like get Manufacturer, Model, Name, PartNumber, slotlayout, serialnumber, or poweredon to get more detailed information about the motherboard.

 As an example, let's check a motherboard's manufacturer, model number, and serial number using WMIC.

 Open up the command prompt in Windows via either the run dialog (Windows+R) or by searching for "cmd" on the Start menu—no need to run the Command Prompt as an administrator. And, as we mentioned, you could also use PowerShell here, if you prefer. The command works the same in both shells. At the command line, type the following text (noting that there are no spaces between the modifiers—just commas), and then hit Enter:

wmic baseboard get product,Manufacturer,version,serialnumber

![The Command Prompt will display your motherboard manufacturer and model.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_1.png) 

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 The information returned checks out for the motherboard we're using: the manufacturer is Gigabyte, the board is the Z170X-Gaming 7, and while the WMIC tool tried to check the serial number, Gigabyte left that particular bit unfilled for whatever reason. Nonetheless, the WMIC tool functioned just as it should, and without opening the case or using any third party tools, we have the basic information we're looking for.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
##  Check Your Model Number in System Information

 System Information is a no-frills way to look up the details of your PC's hardware and software. There are two easy ways to launch it. Click the Start button, type "System Information" into the search bar, and then hit Enter or click "Open."

![Click the Start button, type "system information" into the search bar, then hit Enter or click "Open."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/click-system-information.png) 

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Alternatively, you can use the Run window. Hit Windows+R to open a run dialog, then type "msinfo32" into the Run prompt and hit Enter.

 The "System Summary" page will be open by default. Scroll down and look for the line named "BaseBoard Product"—that is your motherboard.

![Look for a line named "BaseBoard Product." That is your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/look-for-baseboard-product.png) 

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
##  Check Your Model Number with Speccy

 If you want another GUI-based way to check your motherboard's model number (as well as a method that yields more information at a glance than the WMIC tool), you can grab the free tool [Speccy](https://www.piriform.com/speccy). It's a handy app to have around.

 After downloading and installing Speccy, go ahead and fire it up.

 You can see the motherboard model number right on the summary page, along with it's current operating temperature (assuming your board includes that). You can also see basic details about other system components.

![The &quot;Summary&quot; page will display your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_2.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
 Click over to the "Motherboard" tab on the left to see even more information about your motherboard, including details about the chipset and voltages, along with the types of slots included on the board and whether or not they're currently in use.

![The &quot;Motherboard&quot; tab has more specific information about your motherboard.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/wmic_3.png) 

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873313/18544" target="_top" id="1873313"><img src="//a.impactradius-go.com/display-ad/18544-1873313" border="0" alt="" width="1080" height="1263"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873313/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  Check Your Motherboard Model with HWiNFO64

[HWiNFO64](https://www.fosshub.com/HWiNFO.html) displays most of the same information as Speccy, though it looks fairly different. Downlod and launch it to get started.

 Be careful that any "Download" link you click is actually for HWiNF64, not an advertisement.

 HWiNFO64 can display any of the information about your system, including all of the information available from the sensors. That isn't necessary in this case and will only add to the clutter, so launch HWiNFO64 in "Summary-Only" mode.

 Tick the box that says "Summary-Only," then click "Start."

![Tick the box that says "Summary-Only," then click "Start."](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/tick-summary-only-then-click-start.png) 

<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
 You'll see a window that displays everything about your PC's hardware. The left section gives you all of the details about your [CPU](https://facebook-clips.techidaily.com/echoes-of-now-strategies-for-downloading-current-events/), the middle section provides information about your [motherboard](https://tech-savvy.techidaily.com/uniting-giants-how-bzs-games-meet-microsofts-ai-visionaries-tech-dialogue/) and [RAM](https://youtube-web.techidaily.com/ed-2024-approved-unlocking-youtube-success-top-video-strategies-to-explode-views/), and the right-most section focuses on your [GPU](https://android-unlock.techidaily.com/unlock-vivo-s17-pro-phone-password-without-factory-reset-full-guide-here-by-drfone-android/) and hard drives.

![The HWiNFO64 summary window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2017/10/the-summar-window.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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


