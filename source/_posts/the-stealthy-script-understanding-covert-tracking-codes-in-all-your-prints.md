---
title: "The Stealthy Script: Understanding Covert Tracking Codes in All Your Prints"
date: 2024-08-28 13:52:16
updated: 2024-08-29 10:37:50
tags:
  - hardware
categories:
  - tech
thumbnail: https://thmb.techidaily.com/38deee1fec1c0bec7cba4dcb61a1033e4c5fd684f75205d6b2dd2ff58f0ec205.jpg
---

## The Stealthy Script: Understanding Covert Tracking Codes in All Your Prints

### Key Takeaways

* Printers embed yellow dots into documents, impacting privacy and raising potential concerns.
* Tracking codes in printers are created by firmware and reveal printer info and timestamps.
* Tracking codes, present since the '80s, facilitate law enforcement but pose privacy risks.

 Printers embed hidden yellow dots on pages, revealing who printed what and when. This tracking tech, existing for over 20 years, aids in preventing counterfeiting but raises privacy concerns.

##  Tracking Codes in Detail

 If you [add a printer to Windows 11](https://video-capture.techidaily.com/updated-browsing-made-memorable-the-leading-screen-recorder-software-for-2024/), you'll still be getting tracking codes printed on your pages. Even though you could theoretically change the [settings to adjust the privacy in Windows 11](https://win-able.techidaily.com/reviving-game-playthroughs-solve-xbox-headset-problems-with-these-proven-steps/), you can't change dots from going on your printed pages. Tracking codes are a form of steganography that involves hiding information within another medium, such as an image or document. In the case of printers, tracking codes are used to embed identifying information about the printer and the printed document within the document itself. The most well-known type of printer tracking code is the yellow dot pattern, where tiny, barely visible yellow dots are arranged in a grid to encode data.

![Brother HL-L3295CDW Color Laser Printer Screen](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/wm/2024/04/brother-hl-l3295cdw-color-laser-printer-screen-1.jpg) 

Patrick Campanale / How-To Geek

 Tracking codes are typically created by the printer firmware and embedded in the document as it is being printed. The firmware contains algorithms that generate the specific pattern of dots or other steganographic markings based on the printer's identifying information and the timestamp of the printing job. This process is automatic and does not require any user intervention. In fact, most users don't even know their printers are printing information that can track them.

##  How Did These Codes Come About?

![A printer printing a black and white "How-To Geek" page.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/10/52775531323_2850f9e4cf_o-1.jpg) 

## Jason Montoya / How-To Geek

 Printer tracking codes, also known as machine identification codes (MIC) or yellow dots, have been used by printer manufacturers since the mid-1980s. The [patent for this technology](http://patents.google.com/patent/US5515451A/en) was originally granted in 1993 but has expired. The origin of printer tracking codes can be traced back to the cooperation between the U.S. government and printer manufacturers to prevent counterfeiting. In the 1980s, the U.S. Secret Service approached the Japanese Ministry of Finance to address [the issue of counterfeit currencies](https://www.bbc.com/future/article/20170607-why-printers-add-secret-tracking-dots) produced using color copiers.As a result, copier manufacturers agreed to implement machine identification codes.

 Printer manufacturers have stated that the primary reason for implementing tracking codes is to assist law enforcement in tracing the origin of counterfeit currency and other illegal documents. However, privacy advocates[have expressed concerns](https://www.eff.org/issues/printers) about the potential abuse of this technology, as it enables the tracking of individuals based on the documents they print.

 Despite the controversies surrounding printer tracking codes, they continue to be a standard feature in most modern printers. There used to be [a list of printers](https://www.eff.org/pages/list-printers-which-do-or-do-not-display-tracking-dots) where this stenography showed up, but it was last updated in 2017 and hasn't been kept running since then. The list notes that almost all modern laser printers have some form of steganography tracking, even if they don't print yellow dots.

##  How Printer Tracking Codes Function

![A person using an all-in-one printer in an office setting.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/03/aio-printer-office.jpg) 

_[New Africa/Shutterstock.com](https://www.shutterstock.com/image-photo/employee-using-modern-printer-office-closeup-1923681830)_

 When someone prints a sheet of paper on a color printer, a grid of [15 by 8 yellow dots](https://w2.eff.org/Privacy/printers/docucolor/) is embedded within the sheet. The grid is repeated throughout the printed page, and the grids are offset to ensure that each grid print doesn't run into another. The grids are also parallel to the edges of the page. The dots form a series of data, much like punch cards used on the earliest computers.

 The tracking codes are encoded using a binary system, where each dot represents a bit of information. The presence or absence of a dot at a specific location in the pattern corresponds to a "1" or "0" in binary code. The dots are organized in a grid, and each row of the grid encodes a specific piece of information, such as the printer's serial number, manufacturing date, and the timestamp of the printed document.

 To [decode the tracking information](https://www.instructables.com/Yellow-Dots-of-Mystery-Is-Your-Printer-Spying-on-/), the printed page is first illuminated with blue light, which makes the yellow dots more visible. The page is then photographed or scanned at a high resolution, typically 600 dpi or higher. The resulting image is processed using specialized software that analyzes the dot pattern and converts it into binary code. The binary code is then translated into human-readable information based on the known structure of the tracking code grid.

 If you can get the dots to show up, you can potentially read what they encode. This is the data each row represents:

* The printer serial number is encoded in bytes 14, 13, 12, and 11 using binary-coded decimal (BCD), with two digits per byte. It is unique to each printer and remains constant.
* Byte 15 is often zero, but its value may be constant for each printer and convey non-user-visible information about the printer's model or configuration.
* Byte 10 acts as a separator and typically consists of all ones. It does not appear to encode any information.
* The year the page was printed (without the century) is encoded in byte 8\. For example, the year 2005 is coded as 5.
* The month and day the page was printed are encoded in bytes 7 and 6, respectively.
* The hour the page was printed is encoded in byte 5\. This may be in the UTC time zone or set inaccurately within the printer.
* The minute the page was printed is encoded in byte 2.
* Bytes 9, 4, and 3 are unused.
* Byte 1 is a row parity bit, which is set to ensure an odd number of dots are present per row.

 Instead of reading all of this information, if you want to decode this, there's [a handy website](https://w2.eff.org/Privacy/printers/docucolor/#program) that can attempt to process the data and give you a result.

##  Could This Feature Be Abused?

 Like many features installed for security reasons ([like Microsoft's upcoming Recall feature](https://youtube-stream.techidaily.com/in-2024-the-best-of-yt-a-deep-dive-into-music-dance-clips-23/)), steganography can be used for nefarious purposes. One of the main concerns is the lack of transparency surrounding the use of tracking codes. Many users are unaware that their printed documents contain hidden identifying information, and printer manufacturers have not always been forthcoming about the presence or purpose of these codes.

 The potential for misuse and abuse of printer tracking codes is another significant concern. While the technology is intended to assist law enforcement in investigating crimes such as counterfeiting, there is a risk that it could be used for other, less legitimate purposes. For example, tracking codes could be used to monitor and suppress political dissent, track whistleblowers, or target individuals based on their beliefs or associations.

 This is a significant red flag for any individual who's concerned about the privacy of their information. Its use in some cases to [prosecute whistleblowers](https://blog.erratasec.com/2017/06/how-intercept-outed-reality-winner.html#.WTcCt%5Fryvft) who have leaked documents is well-documented.

##  Can You Disable This Tracking?

![A Star Delta-10 dot matrix printer.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/06/star_dot_matric_printer.jpg) 

[Star](https://www.vintagecomputing.com/index.php/archives/973/retro-scan-of-the-week-star-dot-matrix-printer)

A Star Delta-10 dot matrix printer.

 To date, it is impossible to remove the document tracking dots unless you decide to print on a dot-matrix printer. The instructions for printing these tracking dots are embedded in the firmware for the printer. The only solution some people have come up with is printing on yellow paper to make the dots even less visible. However, under a blue LED light, you'll still see the gridlike patterns printed on every sheet. It's funny that you can even [optimize Microsoft Edge for increased privacy](https://screen-capture.techidaily.com/2024-approved-zoom-webinars-for-newbies-a-practical-starter-manual/), but not your old-technology printer.

 These days, not many people use printed sheets for anything other than permanent documentation. With so much cloud storage available to whoever wants it, it's unlikely that people will continue using printers at the same scale that they did in the '90s and early '00s. However, these dots still exist, and it doesn't take a rocket scientist to read them. When printing something sensitive, be aware that the date and time of the document are also recorded. It could be used to prove the existence of a printed page for time-specific issues.

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
