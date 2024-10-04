---
title: Navigating New Gadgets & Gizmos at Tom's Hardware Hub
date: 2024-10-03T00:12:55.450Z
updated: 2024-10-03T22:54:06.897Z
tags:
  - cpu
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/MC9WwgK8bJ99PhUas7KVcb-320-80.png
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
<li><a href="https://youtube-docs.techidaily.com/tandout-thumbnails-start-here-20-top-font-picks-for-2024/"><u>[New] Standout Thumbnails Start Here 20 Top Font Picks for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-download-and-organize-facebook-urls-top-8-tools-of-the-year/"><u>[Updated] Download & Organize Facebook URLs Top 8 Tools of the Year</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-a-step-by-step-approach-to-screening-on-switch/"><u>[Updated] In 2024, A Step-by-Step Approach to Screening on Switch</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-newcomers-guide-profiting-from-live-streaming-on-periscope-for-2024/"><u>[Updated] Newcomer’s Guide Profiting From Live Streaming on Periscope for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-prime-20-anime-openers-soundscape/"><u>[Updated] Prime 20 Anime Openers' Soundscape</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-achieving-peak-zoom-resolution-effective-techniques/"><u>2024 Approved Achieving Peak Zoom Resolution Effective Techniques</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/exploring-toms-tech-insights-a-comprehensive-guide/"><u>Exploring Tom's Tech Insights: A Comprehensive Guide</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/first-ever-release-of-sabrents-unique-single-sided-rocket-nvme-gen5-1tb2tb-ssds-optimized-dram-free-storage-solutions-perfect-for-laptops-and-gaming-console2/"><u>First Ever Release of Sabrent's Unique Single-Sided Rocket NVMe Gen5 1TB/2TB SSDs: Optimized DRAM-Free Storage Solutions Perfect for Laptops & Gaming Consoles</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/flash-deal-alert-the-4tb-ssd-by-crucial-is-now-a-steal-only-005-per-gb-but-hurry-limited-stock-available/"><u>Flash Deal Alert! The 4TB SSD by Crucial Is Now a Steal - Only $0.05 per GB, But Hurry, Limited Stock Available!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/hardware-review-hub-unveiling-the-best-tech-at-your-brand-name/"><u>Hardware Review Hub: Unveiling the Best Tech at [Your Brand Name]</u></a></li>
<li><a href="https://extra-tips.techidaily.com/hdr-mastery-essential-steps-for-sdr-to-hdr-upconversion/"><u>HDR Mastery Essential Steps for SDR-to-HDR Upconversion</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/high-performance-vs-excess-analyzing-the-need-for-a-120mm-radiator-in-teamgroups-sub-12w-m2-ssd-setup/"><u>High Performance Vs. Excess? Analyzing the Need for a 120Mm Radiator in TeamGroup’s Sub-12W M.2 SSD Setup</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/high-performance-risc-v-pcie-gen5-ssd-nvme-controller-from-china-achieves-up-to-142gbs-speeds-no-cooling-required/"><u>High-Performance RISC-V PCIe Gen5 SSD NVMe Controller From China Achieves Up to 14.2GB/S Speeds - No Cooling Required</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/imminent-arrival-new-trademark-discoveries-point-to-a-launch-of-samsungs-990-evo-plus-and-9100-pro-ssds-soon/"><u>Imminent Arrival? New Trademark Discoveries Point to a Launch of Samsung's 990 EVO PLUS and 9100 PRO SSDs Soon</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://solve-news.techidaily.com/online-movavi-mp3-flv-freemp3flv/"><u>무료 표준화: Online Movavi MP3 및 FLV 파일을 원형화하기 위한 바이트를 아닌 효율적인 소스 - FREEMP3FLV</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016165/19272" target="_top" id="2016165">
  <img src="//a.impactradius-go.com/display-ad/19272-2016165" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016165/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

