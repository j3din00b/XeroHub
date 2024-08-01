---
title: "BlueBuild Workshop"
date: 2024-08-01
draft: false
description: "The easiest way to build your own desktop Linux images"
tags: ["uBlue", "Distro", "Bluefin", "Fedora", "Atomic", "Builder", "Linux"]
---
### What is BlueBuild Workshop?

[**BlueBuild**](https://blue-build.org/) is a nifty toolkit for creating custom images of Linux distributions, similar to [**Bluefin**](https://projectbluefin.io). It simplifies the process by allowing you to tweak configurations in a straightforward `recipe.yml` file, perfect for those who want to share their personalized setups. You don't need to be a container wizard or a GitHub guru to get started—basic git and text editor skills will do. Just follow the documentation, ask the friendly community for help, and soon you'll be building custom Linux images like a pro.

{{< github repo="blue-build/workshop" >}}

All images will be based off of **Fedora** and have **Atomic** elements. No **Debian** or **ArchLinux** bases as of the writing of this post. Also this project is totally unrealted to **uBlue** or **Bluefin**.

### Why use it?

To answer this question, I will say, this is not meant for everyone. But if you are a **FOSS** tinkerer and would like to create your own image(s) with your *ideal* configs and set of tools that anyone could *Rebase* to, then this is for you. This thing is so flexible.

{{< article link="/posts/aurora-atomic/" >}}

Just keep in mind that This isn't a *distro builder*, just a custom image builder. Remember that. Although you can generate ISOs from it, that's not what project was meant to be used for.

### Benefits vs Drawbacks

- **The Benefits**

Now I don't know how to put this, but you can do so much with this thing. As to benefits, I can't say much beyond what I already have. With the right amount of **Linux** knowledge you can take it to another level. You can build images that rival the likes of **Bluefin** and its derivatives, even **CachyOS** to a certain degree using just images no ISOs to maintain, set it n forget it style. It's all up to you & your level of knowledge.

![bluebuild](https://i.imgur.com/4Vs4Yoq.png)

- **The Drawbacks**

This project is still young, so it will naturally come with some growing pains. As to drawbacks, it doesn't have many if any. The devs are doing a great job with it. The only thing I may not like, is the fact that it's only **Fedora** based, since am an **Arch** user myself. But that's not a drawback at all.

### My thoughts on BlueBuild

At first glance it looks easy enough to pull off a custom build. But after digging deeper, as I always do, it's not all as straightforward as I'd hoped. You will hit a few snags, which I find natural with every **FOSS** project.

One example being, dependencies. I keep running into this problem over and over and over. I am not giving up though. It's just a side project am working on.

Bottom line is, although devs are doing their best to make the project as easy as possible to use, sometimes issues happen that require a lot of Linux know-how to figure out. So as easy as it appears to be, it really isn't as I first thought.

I still love the project so should you if you like stuff like that. That's why I will keep a close eye on it and see where it goes. I have super high hopes for it. As an Arch user, and ex-Distro maintainer, I see many images being born using this down the line...

That’s it folks ..

Cheers !