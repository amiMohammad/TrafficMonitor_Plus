**[English](./ReadMe.md) | [简体中文](./ReadMe_CN.md) | [বাংলা](./ReadMe_BN.md)**

[![Badge](https://img.shields.io/badge/link-996.icu-%23FF4D5B.svg?style=flat-square)](https://996.icu/#/en_US)
[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg?style=flat-square)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/zhongyang219/TrafficMonitor/main.yml?branch=master&label=Release%20CI&logo=github&style=flat-square)](https://github.com/zhongyang219/TrafficMonitor/actions?query=workflow:"Release+CI")
[![GitHub release](https://img.shields.io/github/release/zhongyang219/TrafficMonitor.svg?style=flat-square)](https://github.com/zhongyang219/TrafficMonitor/releases/latest)

<a href="https://hellogithub.com/repository/5ef48af2b2794d4798b17d6539ec7305" target="_blank"><img src="https://api.hellogithub.com/v1/widgets/recommend.svg?rid=5ef48af2b2794d4798b17d6539ec7305&claim_uid=CeVqou2T1dIvfQP" alt="Featured｜HelloGitHub" style="width: 250px; height: 54px;" width="250" height="54" /></a>

# TrafficMonitor পরিচিতি

TrafficMonitor হল উইন্ডোজের জন্য একটি ফ্লোটিং উইন্ডোযুক্ত নেটওয়ার্ক মনিটরিং সফটওয়ার। এটি বর্তমান ইন্টারনেট স্পিড, CPU ও RAM ব্যবহার প্রদর্শন করে। এছাড়াও টাস্কবারে এম্বেডড ডিসপ্লে, পরিবর্তনযোগ্য স্কিন এবং ঐতিহাসিক ট্রাফিক পরিসংখ্যানের মতো অন্যান্য বৈশিষ্ট্যও রয়েছে।

# সম্পর্কিত লিঙ্ক

TrafficMonitor-এর সর্বশেষ সংস্করণ ডাউনলোড করতে [এখানে ক্লিক করুন](https://github.com/zhongyang219/TrafficMonitor/releases/latest)।

বিকল্প লিঙ্ক: [Baidu Netdisk](https://pan.baidu.com/s/15PMt7s-ASpyDwtS__4cUhg) থেকে ডাউনলোড করুন। অ্যাক্সেস কোড: `ou0m`

Gitee-এ প্রকল্প পেজ পাওয়া যাবে [এখানে ক্লিক করে](https://gitee.com/zhongyang219/TrafficMonitor)

যদি আপনি কোনো সমস্যা অনুভব করেন, তাহলে প্রায়শই জিজ্ঞাসিত প্রশ্ন দেখার জন্য [এখানে ক্লিক করুন](./Help_en-us.md)।

আপনি TrafficMonitor-এর প্রি-রিলিজ বিল্ড সংস্করণ ডাউনলোড করতে [এখানে ক্লিক](https://github.com/zhongyang219/TrafficMonitor/actions?query=workflow:"Release+CI") করতে পারেন।

সংস্করণ 1.80 এবং পরবর্তী সংস্করণে টেম্পারেচার মনিটরিং ফাংশন যোগ করা হয়েছে। যদি ব্যবহারকারীর এই ফাংশনের প্রয়োজন না হয় এবং 1.80 বা পরবর্তী সংস্করণে কোনো সমস্যা দেখা দেয়, তাহলে টেম্পারেচার মনিটর ছাড়া পূর্ববর্তী সংস্করণ (Lite সংস্করণ) ডাউনলোড করার পরামর্শ দেওয়া হয়। (`Lite` সংস্করণটি Release পেজে পাওয়া যাবে।)

TrafficMonitor-এর জন্য Microsoft Visual C++ অপারেটিং পরিবেশ প্রয়োজন। প্রোগ্রাম চালু হওয়ার সময় যদি "Cannot find MSVC*.dll" টাইপের ত্রুটি দেখা দেয়, তাহলে নিচের লিঙ্কে ক্লিক করে Microsoft Visual C++ অপারেটিং পরিবেশ ডাউনলোড ও ইনস্টল করুন।

[Download the latest supported version of Visual C++ Redistributable Package | Microsoft Docs](https://docs.microsoft.com/en-us/cpp/windows/latest-supported-vc-redist?view=msvc-170)

# সংস্করণ বর্ণনা

TrafficMonitor-এর দুটি সংস্করণ আছে: স্ট্যান্ডার্ড সংস্করণ ও Lite সংস্করণ। স্ট্যান্ডার্ড সংস্করণে সব ফাংশন থাকে, আর Lite সংস্করণে টেম্পারেচার মনিটরিং, GPU ব্যবহার এবং হার্ড ডিস্ক ব্যবহারের মতো হার্ডওয়্যার মনিটরিং ফাংশন থাকে না। স্ট্যান্ডার্ড সংস্করণ চালাতে প্রশাসকের (administrator) বিশেষাধিকার প্রয়োজন, Lite সংস্করণে তা লাগে না।

যদি তাপমাত্রা ও অন্যান্য হার্ডওয়্যার তথ্য মনিটর করতে প্রয়োজন না হয়, তাহলে Lite সংস্করণ ব্যবহার করার পরামর্শ দেওয়া হয়।

দুটি সংস্করণের ফাংশন তুলনা নিচে দেওয়া হলো:

| ফাংশন | স্ট্যান্ডার্ড সংস্করণ | Lite সংস্করণ |
| --- | --- | --- |
| ইন্টারনেট স্পিড মনিটরিং | ✔ | ✔ |
| CPU ও RAM ব্যবহার মনিটরিং | ✔ | ✔ |
| CPU, GPU, হার্ড ডিস্ক, মাদারবোর্ডের তাপমাত্রা | ✔ | ❌ |
| CPU ফ্রিকোয়েন্সি মনিটরিং | ✔ | ✔ |
| GPU ব্যবহার মনিটরিং | ✔ | ✔ |
| হার্ড ডিস্ক ব্যবহার মনিটরিং | ✔ | ✔ |
| নেটওয়ার্ক কানেকশন বিস্তারিত | ✔ | ✔ |
| প্লাগ-ইন সিস্টেম | ✔ | ✔ |
| মূল উইন্ডোর স্কিন পরিবর্তন | ✔ | ✔ |
| প্রশাসকের বিশেষাধিকার প্রয়োজন | হ্যাঁ | না |

নোট: সংস্করণ 1.86 থেকে TrafficMonitor Lite সংস্করণেও GPU ও হার্ড ডিস্ক ব্যবহারের মনিটরিং ফাংশন দেওয়া হয়েছে। স্ট্যান্ডার্ড সংস্করণের তুলনায় এতে শুধুমাত্র টেম্পারেচার মনিটরিং ফাংশনটি অনুপস্থিত। পরবর্তী সংস্করণে TrafficMonitor-এ টেম্পারেচার মনিটরিং ফাংশন আর রক্ষণাবেক্ষণ করা হবে না। TrafficMonitor আর স্ট্যান্ডার্ড সংস্করণ সরবরাহ করবে না; শুধুমাত্র Lite সংস্করণেই থাকবে। টেম্পারেচার মনিটরিং ফাংশনটি [Hardware Monitor plugin](https://github.com/zhongyang219/TrafficMonitorPlugins/blob/main/download/plugin_download_en.md#hardware-monitor-plugin)-এ স্থানান্তরিত হয়েছে। যদি আপনি টেম্পারেচার মনিটরিং ফাংশন ব্যবহার করতে চান, তাহলে Hardware Monitor প্লাগইন ডাউনলোড করুন।

# প্রধান বৈশিষ্ট্য

* বর্তমান নেটওয়ার্ক ট্রান্সমিশন স্পিড ও CPU/RAM ব্যবহার প্রদর্শন
* একাধিক নেটওয়ার্ক অ্যাডাপ্টার থাকলে ব্যবহারকারী স্বয়ংক্রিয় বা ম্যানুয়ালি নেটওয়ার্ক নির্বাচন করতে পারেন
* নেটওয়ার্ক কানেকশন বিস্তারিত দেখানো
* টাস্কবারে এম্বেডড ডিসপ্লে সমর্থন
* স্কিন পরিবর্তন ও কাস্টমাইজেবল স্কিন সমর্থন
* ঐতিহাসিক ট্রাফিক পরিসংখ্যান
* হার্ডওয়্যার তথ্য মনিটরিং
* প্লাগ-ইন সিস্টেম

# ব্যবহারের নির্দেশাবলী

**[এখানে ক্লিক করুন](https://github.com/zhongyang219/TrafficMonitor/wiki) TrafficMonitor-এর বিস্তারিত ডকুমেন্টেশন দেখতে Wiki পেজে যেতে (শুধু চীনা ভাষায় উপলব্ধ)।**

# স্ক্রিনশট

মূল ফ্লোটিং উইন্ডো:  
![](./Screenshots/en_us/main1.png)  
ডান-ক্লিক মেনু:  
![](./Screenshots/en_us/main.png)  
টাস্কবার উইন্ডো  

![](./Screenshots/en_us/taskbar.png)  

রঙিন স্কিন:  

![](./Screenshots/skins.PNG)  

স্কিন পরিবর্তন:  

![](./Screenshots/en_us/selecte_skin.png)  

অপশন:  

<img src="./Screenshots/en_us/option.jpg" style="zoom:80%;" />  

# কীভাবে ব্যবহার করবেন

প্রোগ্রাম চালু হওয়ার সাথে সাথে স্ক্রিনে নেটওয়ার্ক স্পিড দেখানো একটি ফ্লোটিং উইন্ডো দেখা যাবে। ফ্লোটিং উইন্ডোতে ডান-ক্লিক করলে পপ-আপ মেনু খুলবে।

TrafficMonitor টাস্কবারে তথ্য প্রদর্শন করতে পারে। তবে ডিফল্টভাবে TrafficMonitor শুধু মূল উইন্ডো (ফ্লোটিং উইন্ডো) দেখায়। টাস্কবারে এম্বেডড ডিসপ্লে দেখাতে চাইলে উইন্ডোতে ডান-ক্লিক করে পপ-আপ মেনুতে "Show Taskbar Window" নির্বাচন করুন।

ব্যবহারকারীরা এম্বেডড টাস্কবার উইন্ডোতে প্রদর্শিত আইটেম কাস্টমাইজ করতে পারেন। ডিফল্টভাবে শুধুমাত্র নেটওয়ার্ক স্পিড দেখানো হয়। CPU ও RAM ব্যবহার বা অন্যান্য তথ্য দেখাতে চাইলে টাস্কবার উইন্ডোর ডান-ক্লিক মেনুতে “Display Settings” নির্বাচন করুন, তারপর “Display Settings” ডায়ালগ বক্সে আপনি যে আইটেমগুলো দেখাতে চান তা চেক করুন, যেমনটি নিচে দেখানো হয়েছে:

<img src="./Screenshots/en_us/taskbar_item_settings.png" style="zoom:80%;" />

# কাস্টমাইজেবল স্কিন
<img src="./Screenshots/en_us/selecte_skin.png" style="zoom:80%;" />

মূল উইন্ডো বা নোটিফিকেশন এরিয়া আইকনের ডান-ক্লিক মেনু থেকে “Other Functions”-“Change Skin” নির্বাচন করে স্কিন পরিবর্তনের ইন্টারফেস খুলতে পারবেন। ব্যবহারকারীরা আরও স্কিন ডাউনলোড করে [এখানে](https://github.com/zhongyang219/TrafficMonitorSkin/blob/master/皮肤下载.md) নিজেদের প্রয়োজন অনুযায়ী স্কিন কাস্টমাইজ করতে পারেন।

স্কিন ফাইলগুলো অ্যাপের অবস্থানকারী ডিরেক্টরির `skins` ডিরেক্টরির ভেতরে সংরক্ষিত থাকে। প্রতিটি স্কিন আলাদা ফোল্ডারে থাকে এবং ফোল্ডারের নামই স্কিনের নাম।

ফাইলগুলোর মধ্যে `background.bmp` ও `background_l.bmp` হল ব্যাকগ্রাউন্ড ছবি, `skin.ini` হল স্কিনের কনফিগারেশন ডকুমেন্ট; ব্যবহারকারীরা টেক্সট রং, ফন্ট, স্কিন ক্রিয়েটর, প্রতিটি আইটেমের আকার ও অবস্থান ইত্যাদি কাস্টমাইজ করতে পারেন।

সংস্করণ 1.80 থেকে XML ফরম্যাটের `skin.xml` স্কিন কনফিগারেশন ফাইল যোগ করা হয়েছে। XML স্কিন কনফিগারেশন ডকুমেন্ট ছাড়া TrafficMonitor তাপমাত্রা ও GPU ব্যবহার প্রদর্শন করতে পারবে না।

সংস্করণ 1.85 থেকে PNG ফরম্যাটের ব্যাকগ্রাউন্ড ইমেজের সমর্থন যোগ করা হয়েছে; আপনি PNG ফরম্যাট ব্যবহার করে স্বচ্ছ ব্যাকগ্রাউন্ডযুক্ত স্কিন তৈরি করতে পারেন। ব্যাকগ্রাউন্ড ইমেজ ফাইলের নাম হলো `background.png` ও `background_l.png`।

স্কিন তৈরির বিস্তারিত নির্দেশাবলীর জন্য নিচের লিঙ্কে ক্লিক করুন:

[皮肤制作教程 · zhongyang219/TrafficMonitor Wiki (github.com)](https://github.com/zhongyang219/TrafficMonitor/wiki/皮肤制作教程)

# অপশন কনফিগার করা
<img src="./Screenshots/en_us/option.jpg" style="zoom:80%;" /><br>
পপ-আপ মেনুতে "Options..." নির্বাচন করলে ব্যবহারকারীরা অপশন কনফিগারেশন পেজে যেতে পারেন। অপশন কনফিগারেশন ডায়ালগ বক্সে ব্যবহারকারী মূল উইন্ডো ও টাস্ক উইন্ডোর জন্য টেক্সট রং, টেক্সট ফন্ট, ব্যাকগ্রাউন্ড রং, নেট স্পিড ইউনিট, প্রদর্শিত টেক্সট ইত্যাদি আলাদাভাবে সেট করতে পারেন।

"Regular Configurations"-এ ব্যবহারকারীরা প্রোগ্রামটি অটোমেটিক আপডেট করবে কিনা, কম্পিউটার চালু হওয়ার সময় স্বয়ংক্রিয়ভাবে চালু হবে কিনা, এবং কখন নোটিফিকেশন পাঠাতে হবে তা পরিবর্তন করতে পারেন।

সংস্করণ 1.72 ও পরবর্তী সংস্করণে ব্যবহারকারীরা প্রতিটি আইটেমের আলাদা টেক্সট রং কনফিগার করতে পারেন। "Designate Colors for Each Items" বিকল্পটি চেক করুন, তারপর "text colors"-এর ডান পাশে থাকা রঙ বক্সে ক্লিক করলে বিস্তারিত রঙ কনফিগারেশন ডায়ালগ বক্স আসবে, যেখানে ব্যবহারকারী প্রতিটি আইটেমের রং আলাদা করে নির্ধারণ করতে পারবেন।

# প্লাগ-ইন সিস্টেম

সংস্করণ 1.82 ও পরবর্তী সংস্করণে প্লাগ-ইন সিস্টেম যুক্ত হয়েছে। প্লাগ-ইন DLL ফাইলটি "TrafficMonitor.exe"-এর একই স্তরের "plugins" ডিরেক্টরির ভেতরে রাখতে হবে। প্রোগ্রাম চালু হওয়ার সাথে সাথেই প্লাগ-ইন স্বয়ংক্রিয়ভাবে লোড হবে। ব্যবহারকারীরা পপ-আপ মেনু "More Functions"-"Plugin Management" থেকে লোড হওয়া প্লাগ-ইন দেখাশোনা ও পরিচালনা করতে পারবেন।

TrafficMonitor-এর প্লাগ-ইন ডেভেলপের নির্দেশাবলীর জন্য [Plugin Development Guide · zhongyang219/TrafficMonitor Wiki (github.com)](https://github.com/zhongyang219/TrafficMonitor/wiki/Plugin-Development-Guide) দেখুন।

TrafficMonitor প্লাগ-ইন ডাউনলোড করতে [এখানে ক্লিক করুন](https://github.com/zhongyang219/TrafficMonitorPlugins/blob/main/download/plugin_download.md)।

# হার্ডওয়্যার মনিটরিং ফাংশনের বিষয়ে

সংস্করণ 1.80 বা পরবর্তী সংস্করণে TrafficMonitor-এ হার্ডওয়্যার মনিটরিং ফাংশন (তাপমাত্রা, CPU ফ্রিকোয়েন্সি, GPU ব্যবহার মনিটরিং) যোগ করা হয়েছে। এটি ওপেন সোর্স লাইব্রেরি [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor)-এর উপর নির্ভর করে। যদি তাপমাত্রা মনিটরিং ফাংশন ব্যবহার করার সময় কোনো সমস্যা দেখা দেয়, তাহলে [এখানে ক্লিক করুন](./Help_en-us.md#13-about-the-temperature-monitoring-of-trafficmonitor)।

এটিও মনে রাখবেন যে তাপমাত্রা মনিটরিং ফাংশন ডিফল্টভাবে বন্ধ অবস্থায় থাকে। যদি ব্যবহারকারী TrafficMonitor-এ তাপমাত্রা মনিটরিং ফাংশন ব্যবহার করতে চান, তাহলে ["Option Settings"-"General Settings"-"Hardware Monitoring"](https://github.com/zhongyang219/TrafficMonitor/wiki/选项设置#硬件监控) এ গিয়ে এটি চালু করতে হবে।

**নোট: হার্ডওয়্যার মনিটরিং ফাংশন (তাপমাত্রা মনিটরিং ও GPU ব্যবহার মনিটরিংসহ) এখনও কিছু সমস্যা থাকতে পারে, যা CPU ও RAM আরও বেশি খরচ করতে পারে। কিছু ব্যবহারকারীর ফিডব্যাক অনুযায়ী, তাপমাত্রা ফাংশন চালু করলে প্রোগ্রাম ক্র্যাশ, সিস্টেম ক্র্যাশ ইত্যাদির মতো সমস্যা দেখা দিতে পারে। তাই হার্ডওয়্যার মনিটরিং ফাংশন চালু করার আগে উপরের ঝুঁকিগুলো বিবেচনা করুন। অন্যথায়, হার্ডওয়্যার মনিটরিং ফাংশন ব্যবহার করবেন না।**

# আপডেট লগ

**[আপডেট লগ দেখতে এখানে ক্লিক করুন।](./UpdateLog/update_log_en-us.md)**

# ডিসক্লেইমার

`www.trafficmonitor.cn` ডোমেইনটি লেখকের সাথে **কোনো সম্পর্ক নেই**। TrafficMonitor-এ বর্তমানে কোনো অফিসিয়াল ওয়েবসাইট নেই। “TrafficMonitor অফিসিয়াল সাইট” নামে যেকোনো ওয়েবসাইট কপিরাইটবিহীন/পাইরেটেড ওয়েবসাইট। এসব সাইটে যাওয়া থেকে বিরত থাকুন, এবং TrafficMonitor এমন সাইট থেকে ডাউনলোড করবেন না। TrafficMonitor ব্যবহারকারীদের জন্য শুধুমাত্র নিম্নলিখিত চ্যানেলগুলোতে উপলব্ধ:

* [GitHub পেজ (github.com/zhongyang219/TrafficMonitor)](https://github.com/zhongyang219/TrafficMonitor)  
* [Gitee পেজ (gitee.com/zhongyang219/TrafficMonitor)](https://gitee.com/zhongyang219/TrafficMonitor)  
* [লেখকের Baidu Netdisk শেয়ার লিংক](https://pan.baidu.com/s/15PMt7s-ASpyDwtS__4cUhg) এক্সট্রাকশন কোড: `ou0m`
