---
layout: splash
title: Cemu Guide
excerpt: "A complete guide to installing CEMU and optimizing performance."
permalink: /
header:  
  overlay_image: /assets/images/splash-image.png
  overlay_filter: 0.5
  overlay_color: "#1a1d24"
  cta_label: "Get Started"
  cta_url: "#get-started"
---

For complete guides to homebrew and custom firmware for other devices, check out [CFW.Guide](https://cfw.guide).
{: .notice--primary}

If you appreciate these guides, consider [donating](/donations) to support the guide.
{: .notice--textbox}

<div class="wrap-collabsible notice--danger">
  <details>
    <summary>Cemu can only run on 64-bit Windows systems.</summary>
    <ul>
      <li>If you have a 32-bit Windows system, this will not work.</li>
      <li>Some users have managed to get Cemu running using <a href="https://www.winehq.org">Wine</a>, however your mileage may vary.</li>- [Regression] The cheat menu now shows fewer items, this requires slower printing or cutting off part of the text to fix
    </ul>
  </details>
</div>

Thoroughly read all of the introductory pages (including this one!) before proceeding.
{: .notice--info}

## What is Cemu?

Cemu is experimental software used to emulate Wii U applications on your PC. This means that if you will be able to run commercial Wii U games directly off of your system.

The majority of games are completely playable from start to finish. You can check to see if your game is playable on the [wiki](https://wiki.cemu.info/wiki/Category:List_of_games).

## How do I get the games?

The guide will take you through how to dump your game copies from your Wii U over to your PC for use in Cemu. This process is easy and quick to set up, and doesn't require any permanent modification to your console.

If you don't have a Wii U console, you will not be able to dump games to your PC and therefore won't be able to use Cemu.

## Can I play online?

Yes! Cemu supports online play, using official Nintendo servers. To do this, we will need to dump your account data from your Wii U to use for connecting to the servers. This process is easy and quick to set up, and doesn't require any permanent modification to your console.

If your account is banned, or if you don't own a Wii U console, you will not be able to use online play with Cemu.

## How well can I run games?

It depends. A lot of people will be able to run most games at full speed, however you must take hardware requirements into account. While the Wii U is not a particularly demanding console, emulation requires a machine with much greater hardware than the original machine. Check below to see if your PC will work.

### CPU
---

A good processor will definitely help speed things up. While modern video-games can be less dependent, emulation can rely quite heavily on CPU performance. We recommend at least an AMD Ryzen 3 or an Intel i5 processor.

Non-Ryzen AMD chips are not recommended as they lack in single-core processing speed. These processors will struggle running demanding games on Cemu.

### RAM
---

For best performance across all games, we recommend using 8GB of RAM or more. While the Cemu website says it can run off of a minimum of 4GB of RAM, this is not recommended and may experience crashes, stuttering and general performance issues in a lot of games.

### GPU
---

NVIDIA GPUs are recommended as they can take some of the load off of the CPU. AMD GPUs are also good, but heavily reliant on the performance of the CPU.

For running any game in general, the bare minimum should be an NVIDIA GTX 700 card or AMD HD 7000 Series card, however you may want to consider something more powerful, especially for games such as Breath of the Wild.

If you're running on a thinner laptop or other low-powered machine, you may be using an iGPU instead, which is not officially supported by Cemu. While some users have reported playable framerates using integrated graphics, playing on a more powerful machine will yield much better results.

---

Now that you're aware of the requirements, you may proceed with downloading and setting up the emulator.

Continue to [Installing Cemu](installing-cemu).
{: .notice--info}

<a id="get-started"/>
