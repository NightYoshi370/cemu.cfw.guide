---
title: Optimizing Breath of the Wild
permalink: /optimizing-botw
---

<!--{% include toc title="Table of Contents" %}-->

Breath of the Wild is a particularly demanding game for a lot of systems, so people have created modifications to help you get the best performance possible in the game.

![]({{ "/assets/images/reshade.png" | absolute_url }})
{: .notice}

This game is much more demanding on your GPU than other Wii U titles. We recommend a more powerful GPU than the ones recommended on the home page, especially if you are interested in playing at higher resolutions and framerates.
{: .notice--info}

Like the previous guide, some of these instructions are GPU specific, so make sure you know what type of GPU you have before proceeding. You'll also need to make note of what rendering API you're using, either OpenGL or Vulkan.

Make sure you have followed our [Optimizing Cemu](optimizing-cemu) guide before proceeding.
{: .notice--textbox}

If you don't know what type of GPU you have, open the Settings app on Windows 10. Then navigate to `System` -> `Display` -> `Advanced display settings`.

Under your display name, it should say `Display #: Connected to [GPU]`. It should say either Intel, AMD or NVIDIA. That will tell you what brand of GPU you have.

## Graphics Packs

This section requires that you have installed Cemu's [community graphics packs](installing-cemu#configuration).
{: .notice--danger}

1. Open the Cemu application
1. Right click on `The Legend of Zelda - Breath of the Wild`
1. Click `Edit graphics packs`
1. Navigate to the `Graphics` category
1. Enable the `Resolution` checkbox
  - If you have a more powerful GPU, you can change the resolution to a higher value, e.g. 1920x1080
  - If you have a weaker GPU, e.g. an iGPU, consider changing it to a lower value to increase performance
1. Navigate to `Mods` -> `FPS++`
1. Enable all of the options in this subcategory

    Changing FPS to 60FPS can cause [some issues](https://wiki.cemu.info/wiki/The_Legend_of_Zelda:_Breath_of_the_Wild#Issues_arising_by_using_FPS.2B.2B_or_static_FPS.2B.2B) during gameplay. When these occur, simply set `Limit FPS (Required)` to 30FPS temporarily until you're past that point in the game.
    {: .notice--info}

1. Open the `Workarounds` category
1. If you're using OpenGL:
    1. Enable `Kakariko Torch Shadows (OpenGL)` and `LWZX Crash (OpenGL)`
    1. Open the `GPU specific workarounds for OpenGL` subcategory
    1. Enable all the options corresponding to your GPU (Intel, AMD or NVIDIA)
1. If you're using Vulkan:
    1. Enable `Grass Swaying (Vulkan)`
    1. If using an Intel GPU, enable `Intel GPU Shadows (Vulkan)`

---

Once understanding what each setting does, we recommend you configure your own options. These settings should work for most people as a base however.
