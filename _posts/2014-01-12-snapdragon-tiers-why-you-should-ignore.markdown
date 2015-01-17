---
layout: default
title: "Snapdragon tiers: why you should ignore"
author: "AdFad666"
image: /media/posts/2014-01-12-snapdragon-tiers.jpg
date: "2014-01-12 07:00:00 +0100"
excerpt: Smart devices based on a Qualcomm platform are usually marketed as having some variant of a Snapdragon SoC. Unfortunately these are purely marketing terms and don't easily relate to specific SoC or functionality...
---

{% include article_head.html %}

Smart devices based on a Qualcomm platform are usually marketed as having some variant of a Snapdragon SoC. Unfortunately these are purely marketing terms and don't easily relate to specific SoC or functionality. In fact as new Snapdragon naming schemes are created, existing chips sometimes get shuffled into to a new category.

This matters for Android, as you cannot know whether a device will be upgradable just by looking at the Snapdragon tier given in the brochure (manufacturer willingness is another story).

Take the example of <a href="http://www.qualcomm.com/snapdragon/processors/s4/specs" target="_blank">MSM8225Q</a> which is becoming popular in budget phones. It is marketed as a quad-core Snapdragon S4, so it must be similar to the Nexus 4, or the Sony Xperia SP, or even the Sony Xperia Z, right? In fact apart from the marketing name, this SoC has almost nothing in common with the SoC inside the devices I just mentioned.

MSM8225Q is the current 'top-end' of the family of Coretex-A5 based SoC which debuted with the <a href="http://www.qualcomm.com/snapdragon/processors/s3-s2-s1/specs" target="_blank">MSM7225A</a>. This was marketed as a single-core Snapdragon S1, the lowest of the Snapdragon tiers. All of the Cortex-A5 based SoC have an Adreno 20x GPU, which was last officially supported in Android 4.1 Jellybean. The only differences are some bumps in clock speed and adding a couple more cores.

Therefore new devices such as the <a href="http://www.phonearena.com/reviews/HTC-Desire-600-Review_id3386" target="_blank">HTC Desire 600</a> are doomed to forever run a build of Android that is already three versions out-of-date. It also means it will never see 'official' support in CyanogenMod 10.0, as the policy is that once a 'stable' build has been released, no new devices can be added.

If you're interested in running the latest and greatest the comes out of the Googleplex, you should find out which specific SoC it has, or at least look carefully at the GPU. All SoC with Adreno 3xx GPUs are supported in Android 4.4 KitKat.

However think carefully about devices that have SoC with Adreno 30x GPUs, especially the upcoming Cortex-A7 family of SoC with Adreno 302. Like their 20x predecessors, they will likely be the first to lose support from future Android revisions (and therefore also CyanogenMod).

Thankfully Sony has so far avoided using obsolete SoC in new devices, which makes our jobs at FreeXperia Project much easier.
