---
title: Unveiling Hardware Secrets on Tom's Digital Workshop Channel
date: 2025-01-07T01:32:49.101Z
updated: 2025-01-12T16:57:23.685Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/cVdR8URKsj9vuVEWJtxzWM-320-80.png
---

## Master the Latest Tech Trends with Tom's Hardware Reviews & Tips

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Intel statement on via oxidation

**Short answer:** We can confirm there was a via Oxidation manufacturing issue (addressed back in 2023) but it is not related to the instability issue.

**Long answer:**   _We can confirm that the via Oxidation manufacturing issue affected some early Intel Core 13th Gen desktop processors. However, the issue was root caused and addressed with manufacturing improvements and screens in 2023\. We have also looked at it from the instability reports on Intel Core 13th Gen desktop processors and the analysis to-date has determined that only a small number of instability reports can be connected to the manufacturing issue._

 _For the Instability issue, we are delivering a microcode patch which addresses exposure to elevated voltages which is a key element of the Instability issue. We are currently validating the microcode patch to ensure the instability issues for 13th/14th Gen are addressed. -_ Intel representative[via Reddit](https://www.reddit.com/r/intel/comments/1e9mf04/comment/lefz09c/) .

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
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-ahead-of-tomorrow-key-youtube-gatherings-post-vidcon/"><u>[Updated] 2024 Approved Ahead of Tomorrow Key Youtube Gatherings (Post-VidCon)</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-formulating-a-singular-hashtag-for-your-tiktok-sphere/"><u>[Updated] In 2024, Formulating a Singular Hashtag for Your TikTok Sphere</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-how-to-initiate-a-collaborative-skype-group-discussion/"><u>[Updated] In 2024, How to Initiate a Collaborative Skype Group Discussion</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-incorporating-youtubes-creative-commons-in-video-making/"><u>[Updated] In 2024, Incorporating YouTube's Creative Commons in Video Making</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-unveiling-changes-in-sony-bdp-s670/"><u>2024 Approved Unveiling Changes in Sony BDP-S670</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/balance-relaxation-and-growth-with-this-ultimate-guide-to-multitasking-and-podcasting/"><u>Balance Relaxation and Growth With This Ultimate Guide to Multitasking & Podcasting</u></a></li>
<li><a href="https://win-able.techidaily.com/dirt-5-stability-issues-solutions-for-preventing-pc-game-crashes/"><u>Dirt 5 Stability Issues? Solutions for Preventing PC Game Crashes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-samsung-m2070fw-driver-easily-and-quickly/"><u>Download Samsung M2070FW Driver | Easily & Quickly</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/expert-advice-easily-remove-apps-from-your-samsung-entertainment-system/"><u>Expert Advice: Easily Remove Apps From Your Samsung Entertainment System</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722975179542-get-instant-access-to-top-notch-wireless-drivers-downloads-available-now/"><u>Get Instant Access to Top-Notch Wireless Drivers - Downloads Available Now</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-the-latest-drivers-for-msi-b350-toms-oc-motherboard-windows-117-supported/"><u>Get the Latest Drivers for MSI B350 TOM'S OC Motherboard - Windows 11/7 Supported</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-secure-your-canon-mf85cdrivers-on-various-windows-platforms-78110/"><u>How to Secure Your Canon MF85^CDrivers on Various Windows Platforms - 7/8.1/10</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/in-2024-downloadfacebookvideos-essential-browser-addons-for-a-smooth-social-media-journey-in-firefox/"><u>In 2024, DownloadFacebookVideos! - Essential Browser Addons for a Smooth Social Media Journey in FireFox</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/quick-tutorial-how-to-securely-get-the-newest-logitech-keyboard-driver-for-your-windows-10-device/"><u>Quick Tutorial: How to Securely Get the Newest Logitech Keyboard Driver for Your Windows 10 Device</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/troubleshooting-and-downloading-usb-c-hardware-drivers-for-optimal-performance-on-windows-10/"><u>Troubleshooting and Downloading USB-C Hardware Drivers for Optimal Performance on Windows 10</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-guide-install-your-logitech-momo-racing-wheel-on-windowsmac-step-by-step/"><u>Ultimate Guide: Install Your Logitech MOMO Racing Wheel on Windows/Mac - Step by Step</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unveiling-the-latest-amds-newly-launched-ryzen-7-7800x3d-outdoes-previous-gaming-champion-zen-4-flagship-by-23-in-benchmark-tests/"><u>Unveiling the Latest: AMD's Newly Launched Ryzen 7 7800X3D Outdoes Previous Gaming Champion - Zen 4 Flagship by 23% in Benchmark Tests</u></a></li>
</ul></div>

