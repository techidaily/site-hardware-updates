---
title: "Navigating the Future of Electronics: Discoveries From Tom's Hardware Review Team"
date: 2025-01-13T16:59:36.865Z
updated: 2025-01-18T20:08:29.468Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://thmb.techidaily.com/66380fee6148181c7fbef919ab70be5b7f03dcd6ba9d00048b2c822f6ae741fb.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-skills.techidaily.com/new-return-artisan-set/"><u>[New] Return Artisan Set</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-a-complete-rundown-reels-vs-stories-on-instagram/"><u>[Updated] 2024 Approved A Complete Rundown Reels vs Stories on Instagram</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/best-bargains-on-amazons-prime-day-2024-top-october-offers-still-in-stock-tech-insights/"><u>Best Bargains on Amazon's Prime Day 2024 - Top October Offers Still in Stock | Tech Insights</u></a></li>
<li><a href="https://extra-hints.techidaily.com/crystal-clear-comparison-rating-the-best-8k-tvs-of-year/"><u>Crystal Clear Comparison Rating the Best 8K TVs of Year</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-6s-plus-by-drfone-ios/"><u>Easy Fixes How To Recover Forgotten iCloud Password On your iPhone 6s Plus</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/exclusive-deal-on-intel-arc-gpu-powered-systems-with-over-450-in-gaming-titles-zdnet/"><u>Exclusive Deal on Intel Arc GPU-Powered Systems with Over $450 in Gaming Titles - ZDNet</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-it-motorola-moto-g24-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Motorola Moto G24 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/slash-priced-tech-combo-alert-dual-protection-with-nordvpn-and-ms-office-365-for-just-40-dont-miss-out-on-this-limited-offer-now/"><u>Slash-Priced Tech Combo Alert: Dual Protection with NordVPN and MS Office 365 for Just $40 – Don’t Miss Out on This Limited Offer Now!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/top-ranking-apple-bargains-in-july-2024-iphone-apple-watch-and-ipad-discounts/"><u>Top-Ranking Apple Bargains in July 2024: IPhone, Apple Watch & iPad Discounts</u></a></li>
</ul></div>

