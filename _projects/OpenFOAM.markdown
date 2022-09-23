---
layout: page
title: Melt flows for in-situ alloying
description: Modelling thermosolutal Marangoni Convection in Laser Powder Bed Fusion with the Finite Volume Method
img: /assets/img/Melt_pool.png
importance: 1
category: work
---

As many authors and groups have discovered previously, the melt pool dynamics occuring during Laser Powder Bed Fusion (PBF-LB/M) is rather tough to model. This is both due to the complex physics interactions as well as the various parameters involved.

There is one phenomenon in particular that drives the internal melt flow that is of particular interest to me, namely Marangoni Convection. It has been shown that this effect alters the flow pattern considerably.

This problem becomes even more relevant when in-situ alloying is involved. With this method, melting doesn't take place with pre-alloyed feedstock but rather uses elemental powder blends that mix during the process. This can save feedstock cost considerably, especially when experimenting with alloy consitution. This however poses another source for Marangoni flow, specifically a solute-driven one.

For this reason, I'm working on an open source implementation of a Finite Volume solver that can capture both thermal and solute-driven Marangoni effects. This way I'm hoping to model the even more complex melt pool dynamics during in-situ alloying in Laser Powder Bed Fusion. This is important in order to understand the technological constraints you face when applying this method of producing parts, such as to what extent local inhomogeneities are present.

You can follow my work at my [GitHub Repo](https://github.com/pzimbrod/lpbfFoam).