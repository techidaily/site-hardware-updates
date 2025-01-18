---
title: "Navigating the World of Computing: Insights From Tom's Hardware Hub"
date: 2025-01-12T19:14:30.329Z
updated: 2025-01-18T16:44:55.464Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/f780668281f43de469309d641324f16afda3a68eb738e8c283227d7e47f57830.jpg
---

## Legacy Over: How LLVM Compiler's Departure Signals the End of AMD's 3DNow

AMD’s near-ancient 3DNow! instructions have faded even further into obscurity.[Open-source compiler LLVM](https://github.com/llvm/llvm-project/commit/f0eb5587ceeb641445b64cb264c822b4751de04a) is finally removing support for the set of instructions that hasn’t been supported by AMD’s CPUs since 2011.

 The 3DNow! instruction set was introduced in 1998 as a competitor to Intel’s MMX. It added Single Instruction, Multiple Data (SIMD) instructions to AMD’s base x86 instruction set, which helped the CPUs do vector processing of floating-point operations using vector registers.

[AMD replaced 3DNow!](https://www.tomshardware.com/news/3dnow-simd-extensions-phenom-sse,11128.html) with the newer SSE equivalents in 2011 and stopped including that feature flag bit beginning with the K10 Bulldozer CPUs. It did take some time for compilers to start dropping support for the instruction set, though, since the CPUs remained in use for quite some time.

 In 2021,[Linux retired the instruction set](https://www.tomshardware.com/news/linux-says-goodbye-to-amd-3d-now) from its kernel, but LLVM maintained support long after everyone else dropped it. The developers behind the LLVM compiler also work to remove MMX types and instructions from the tool.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

 A commit for LLVM 19, expected to be released in September or October, confirmed the impending removal.

 _“This set of instructions was only supported by AMD chips starting in the K6-2 (introduced 1998), and before the “Bulldozer” family (2011). They were never much used, as they were effectively superseded by the more-widely-implemented SSE (first implemented on the AMD side in Athlon XP in 2001)._

 _This is being done as a predecessor towards general removal of MMX register usage. Since there is almost no usage of the 3DNow! intrinsics, and no modern hardware even implements them, simple removal seems like the best option.”_

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 The AMD 3DNow! instructions were popular in the late 90s and early 2000s for improving gaming, video playback, and Adobe Photoshop workflows. Then, Intel released the SSE instructions, which became more dominant overall. When Intel released SSE2, AMD adopted it and dropped its older SIMD instruction set.

 Developers who need to write for old AMD processors can still use 3DNow! instructions in Assembly, including inline Assembly code with LLVM. Other than that, anything related to 3DNow! should be considered deprecated and no longer used.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-studio-vs-campers-contest/"><u>[New] In 2024, Studio vs Camper’s Contest</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/a-week-with-an-ergo-split-keyboard-how-one-change-transformed-my-tech-experience/"><u>A Week with an Ergo-Split Keyboard: How One Change Transformed My Tech Experience</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/anticipated-announcements-at-apples-upcoming-october-showcase-the-new-m4-mac-mini-advanced-ipads-and-latest-innovations-in-siri-technology-insights/"><u>Anticipated Announcements at Apple's Upcoming October Showcase: The New M4 Mac Mini, Advanced iPads, and Latest Innovations in Siri Technology - Insights</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/beyond-the-iconic-macbook-discovering-a-phenomenal-performance-leader-in-todays-laptops-zdnet-review/"><u>Beyond the Iconic MacBook: Discovering a Phenomenal Performance Leader in Today’s Laptops | ZDNet Review</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/enhancing-your-game-experience-tips-to-resolve-frame-rate-issues-fps-drops-and-stutters-while-playing-diablo-4-on-pc/"><u>Enhancing Your Game Experience: Tips to Resolve Frame Rate Issues, FPS Drops & Stutters While Playing Diablo 4 on PC</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/lg-gram-pro-vs-macbook-air-showdown-top-three-surprises-from-a-tech-reviews-comparison-on-zdnet/"><u>LG Gram Pro Vs. MacBook Air Showdown: Top Three Surprises From a Tech Reviews Comparison on ZDNet</u></a></li>
<li><a href="https://win-blog.techidaily.com/master-the-track-without-interruptions-solving-f1-2020s-instability-on-desktop/"><u>Master the Track without Interruptions: Solving F1 2020'S Instability on Desktop</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/new-in-2024-record-your-desktop-like-a-pro-a-filmora-scrn-guide/"><u>New In 2024, Record Your Desktop Like a Pro A Filmora Scrn Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/prime-day-oct-score-the-macbook-air-m1-at-an-unbeatable-price-of-799-exclusive-deal-alert/"><u>Prime Day Oct: Score the MacBook Air M1 at an Unbeatable Price of $799 - Exclusive Deal Alert!</u></a></li>
<li><a href="https://win-answers.techidaily.com/rogue-company-game-crashes-fixed-now-running-smoothly-on-your-pc/"><u>Rogue Company Game Crashes Fixed: Now Running Smoothly on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/silent-no-more-restore-functional-slack-notifications-in-win-11/"><u>Silent No More! Restore Functional Slack Notifications in Win 11</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-pre-upload-website-testing-and-content-inspection/"><u>The Ultimate Guide to Pre-Upload Website Testing and Content Inspection</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-test-picks-the-ultimate-all-rounder-laptop-wowing-users-and-boasting-strong-hardware/"><u>Top Test Picks: The Ultimate All-Rounder Laptop Wowing Users and Boasting Strong Hardware</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/unravel-your-cable-woes-with-this-game-changing-tangle-free-usb-c-lifesaver-for-travelers-techinsider/"><u>Unravel Your Cable Woes with This Game-Changing 'Tangle-Free' USB-C Lifesaver for Travelers | TechInsider</u></a></li>
<li><a href="https://blog-min.techidaily.com/flvmp4/"><u>シェアしてください：ステップバイステップで無料FLVとMP4変換</u></a></li>
</ul></div>

