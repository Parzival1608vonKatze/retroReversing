---
layout: post
tags: 
- n64
- sdk
title: Official Nintendo 64 SDK
thumbnail: /public/consoles/Nintendo 64.png
image: /public/N64/N64 SDK.jpg
permalink: /n64-sdk
breadcrumbs:
  - name: Home
    url: /
  - name: Nintendo 64 Software Development Kit
    url: /n64
  - name: Oman Archive
    url: #
recommend: n64
editlink: /n64/N64SDK.md
updatedAt: 9th May 2020
twitterimage: https://www.retroreversing.com/public/N64/N64 SDK.jpg
---
This post covers the Official Nintendo 64 Software Development kit that was sent to developers is actually split among a number of different discs due to its size.

These Discs include:
* N64Kit - Applications used for N64 development
* N64 OS - The SDK files (includes, libraries etc)
* Nintendo 64 Sound Tools - Tools for Musicians
* Documentation

# N64Kit (N64 Developers Toolkit)
The N64 Developers toolkit contained all the following applications used for N64 Development:
* ccbl
* DDTools
* DPTEST
* HVQ/HVQM
* Monegi Multi Viewer64
* NIFF
* NuSYSTEM
* N64 Disk Drive Multi File System (MFS)

On Windows it was installed into `C:\nintendo\n64kit` and contained pre-compiled executables for all of the main applications.

## Known Versions of N64Kit
Latest Version: **5.2**
Released Versions: **3.0**, **4.0**, **4.1**, **5.0**, **5.1**, **5.2**

Version 5.1 (10th Feb 2000) of the kit was partially released in the BroadOn archive leak of May 2020 due to its use in the iQue players development.

## ccbl - ColorCombiner and Blender Demo
This is an application that runs on the Nintendo 64 hardware to teach programmers about the RDP features. It has the ability to communicate with a Windows Application called `dptest` for which the source code is also available.

## dptest - Display Processor Test tool
Windows application that communicates with the N64 application `ccbl` to save and load configurations.

It works with a number of different N64 development flash cartridges such as:
* MSP-A/MSP-B/MSP-C
* Partner-N64
* IS-Viewer64

<div class="rr-changelog-category">
  <div class="rr-version-gen" version="Files" date="Files in the dptest folder" ></div>
    <ul class="rr-changelog-more">
      <div class="rr-info-gen" badge="dptest.exe" desc=""></div>
      <div class="rr-info-gen" badge="TargetN64.dll" desc="DLL for communication between flash cartridge and the PC "></div>
 <div class="rr-info-gen" badge="KMCCtrl.dll" desc="DLL for communication theough the KMC Partner N64 flash cartirdge" ></div>
 <div class="rr-info-gen" badge="dptest.n64" desc="Compiled N64 rom of CCBL that communicated with dptest" ></div>
    </ul>
</div>

---
# N64 Operating System
The N64 OS was initially released with both SGI and PC versions on the same disc, later it was moved to a disc for each operating system.

On Windows it was installed into `C:\Ultra\usr` and used a UNIX-like directory structure containing the following folders:
* include - C Source code Header files
* lib - compiled static libraries for N64
* sbin - a few custom command line tools
* src - Source code for Demo applications and the libultra and libnaudio libraries

## Known Versions
Latest Version: **2.0L**
Released Versions: **2.0J**, **2.0K**, **2.0H**, **2.0L**
