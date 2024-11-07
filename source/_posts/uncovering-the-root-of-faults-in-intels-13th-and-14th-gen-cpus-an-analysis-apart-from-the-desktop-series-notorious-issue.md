---
title: "Uncovering the Root of Faults in Intel’s 13Th and 14Th Gen CPUs: An Analysis Apart From the Desktop Series' Notorious Issue"
date: 2024-11-01T16:25:50.476Z
updated: 2024-11-07T16:24:35.812Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/50d4bf6106cc2e789648c53429943f049229011e6f572fe9945c7d91985d72b7.jpg
---

## Exploring Innovation in Computers and Gaming - Dive Into Tom's Hardware Insights

Intel has[announced that it has found the root](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) [cause](https://community.intel.com/t5/Processors/July-2024-Update-on-Instability-Reports-on-Intel-Core-13th-and/m-p/1617113#M74792) of the crashing issues plaguing its CPUs. The company will issue a microcode update to address the issues by mid-August, ostensibly ending the long-running saga that began when the first sporadic reports of CPU crashing errors surfaced in December 2022 and grew to a crescendo by the end of 2023\. Intel's response comes after complaints about the issue, which causes PCs to inexplicably crash/BSOD during gaming and other workloads,[reached a fever pitch](https://www.tomshardware.com/pc-components/cpus/game-publisher-claims-100-crash-rate-with-intel-cpus-alderon-games-says-company-sells-defective-13th-and-14th-gen-chips) in recent weeks. However, the microcode update will not repair impacted processors. Intel also confirmed a rumored issue with via oxidation in its 7nm node, but said those issues were corrected in 2023 and didn't contribute to the failures.

 Intel's advisory says an erroneous CPU microcode is the root cause of the incessant instability issues. The microcode caused the CPU to request elevated voltage levels, resulting in the processor operating outside its safe boundaries. Intel is now validating a microcode patch to correct the issues, with its release slated for mid-August. This patch will be distributed through BIOS updates from motherboard OEMs and via Windows updates, so the timing for end-user availability could vary.

 The bug causes irreversible degradation of the impacted processors. We're told that the microcode patch will_not_ repair processors already experiencing crashes, but it is expected to prevent issues on processors that aren't currently impacted by the issue. For now, it is unclear if CPUs exposed to excessive voltage have suffered from invisible degradation or damage that hasn't resulted in crashes yet but could lead to errors or crashes in the future.

 Intel advises all customers having issues to seek help from its customer support. Because the microcode update will not repair impacted processors, the company will continue to replace them. Intel has pledged to grant RMAs to all impacted customers.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 The company had previously advised its customers to stick with the basic power guidelines for its processors, rather than running them at fully unlocked settings, as it worked through the issues. Those instructions, [which you can see here](https://www.tomshardware.com/pc-components/cpus/intel-issues-official-statement-on-core-k-series-crashes-stick-to-intels-official-power-profiles) , remain in effect for now, and Intel hasn't issued any new workarounds for impacted customers. It is unclear if Intel will lift the existing restrictions after it issues the patch.

 Intel had previously[fixed an eTVB bug](https://www.tomshardware.com/pc-components/cpus/intel-denies-reports-that-it-identified-a-root-cause-for-core-i9-crashing-issues-investigation-continues) that contributed to the problems, but now says microcode is the root cause. We're told that the microcode patch currently doesn't exhibit any adverse performance impact (i.e., the chip running slower), but testing is ongoing. We can expect Intel to share more information about performance in the future.

 Intel isn't sharing many deep-dive details about the bug yet but says it will continue its validation process to ensure the microcode fully addresses the issues. The company will release more details about the bug itself in the future.

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 Today, the company also posted to Reddit that it had encountered rumored issues via oxidation in its Intel 7 process node in 2023\. Intel says that the issue was resolved and isn't the source of the Raptor Lake crashes.

 Intel has not issued a recall of its processors; sources close to the matter tell us that isn't expected. We have both of Intel's statements below.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006941/19272" target="_top" id="2006941">
  <img src="//a.impactradius-go.com/display-ad/19272-2006941" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006941/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Intel statement on 13th- and 14th-Gen instability

 _"Based on extensive analysis of Intel Core 13th/14th Gen desktop processors returned to us due to instability issues, we have determined that elevated operating voltage is causing instability issues in some 13th/14th Gen desktop processors. Our analysis of returned processors confirms that the elevated operating voltage is stemming from a microcode algorithm resulting in incorrect voltage requests to the processor."_

 _"Intel is delivering a microcode patch which addresses the root cause of exposure to elevated voltages. We are continuing validation to ensure that scenarios of instability reported to Intel regarding its Core 13th/14th Gen desktop processors are addressed. Intel is currently targeting mid-August for patch release to partners following full validation."_

 _"Intel is committed to making this right with our customers, and we continue asking any customers currently experiencing instability issues on their Intel Core 13th/14th Gen desktop processors reach out to Intel Customer Support for further assistance."_

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-ios-snapshot-spectrum-your-quick-reference-for-2024/"><u>[New] IO's Snapshot Spectrum Your Quick Reference for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-customize-your-videos-appeal-youtube-thumbnail-tips-and-tricks/"><u>[Updated] In 2024, Customize Your Video's Appeal YouTube Thumbnail Tips & Tricks</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-nixing-facebook-broadcasts-effortlessly/"><u>[Updated] Nixing Facebook Broadcasts Effortlessly</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/a-step-by-step-guide-for-meet-custom-filters-and-effects-for-2024/"><u>A Step-by-Step Guide for Meet Custom Filters & Effects for 2024</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/elevate-your-workspace-experience-the-dual-monitor-capability-with-your-m3-macbook-pro-just-as-you-can-with-the-m3-macbook-air/"><u>Elevate Your Workspace: Experience the Dual Monitor Capability with Your M3 MacBook Pro, Just as You Can With the M3 MacBook Air</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/forgot-iphone-15-password-here-are-the-best-solutions-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Forgot iPhone 15 Password? – Here are the Best Solutions | Stellar</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-restore-your-microsoft-windows-pro-license-post-reset-step-by-step-tutorial-by-zdnets-pc-experts/"><u>How to Restore Your Microsoft Windows Pro License Post-Reset | Step-by-Step Tutorial by ZDNet's PC Experts</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-oppo-a79-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Oppo A79 5G | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-gpt-written-language-and-web-integration/"><u>Mastering GPT' Written Language and Web Integration</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/octobers-premier-savings-event-unmissable-gaming-discounts-up-to-1000-grab-them-before-theyre-gone/"><u>October's Premier Savings Event! Unmissable Gaming Discounts Up to $1,000 - Grab Them Before They're Gone!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/score-big-savings-with-the-black-friday-blowout-gigabytes-a5-k1-gaming-laptop-at-an-exclusive-40-off-insider-tips/"><u>Score Big Savings with the Black Friday Blowout: Gigabyte's A5 K1 Gaming Laptop at an Exclusive 40% Off Insider Tips</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/score-big-savings-find-the-best-value-nvidia-gaming-laptops-on-sale-for-amazon-prime-day-2024-according-to-zdnet/"><u>Score Big Savings: Find the Best-Value Nvidia Gaming Laptops on Sale for Amazon Prime Day 2024, According to ZDNet</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/tutorial-reset-fotografik-lepas-dari-sistem-puspa-belanja-hasil-positif/"><u>Tutorial Reset Fotografik Lepas Dari Sistem Puspa Belanja - Hasil Positif!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-buying-guide-for-black-friday-and-cyber-monday-laptop-bargains-techradar-insights/"><u>Ultimate Buying Guide for Black Friday and Cyber Monday Laptop Bargains - TechRadar Insights</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unmissable-amazon-prime-day-offers-in-october-2024-top-bargains-you-can-snag-now/"><u>Unmissable Amazon Prime Day Offers in October 2024 - Top Bargains You Can Snag Now!</u></a></li>
<li><a href="https://fox-links.techidaily.com/what-to-expect-from-the-dji-inspire-2-experience/"><u>What to Expect From the DJI Inspire 2 Experience</u></a></li>
</ul></div>

