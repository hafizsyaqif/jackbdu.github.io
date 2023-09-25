---
layout: post
title: Visualizing Sine Wave with Mechanical Movements
categories: blog
tags: itp introduction-to-fabrication
description: 
published: true
---

I have been making and posting creative coding experiments daily for almost 2 years now. One of the mathematical functions that keep coming back is a sine function. As I have been studying fabrication and mechanical movements recently, I had this idea of creating an automaton that visualizes a sine wave.

One of the mechanisms that I recently learned is called [cam](https://en.wikipedia.org/wiki/Cam), which is commonly used to transform rotary motion into linear motion. I tried imagining and sketching what a cam would look like if its movement follows a sine wave. I started with a regular sine wave, and tried to wrap it around a circle. While it gave me a general idea of what it might look like, it was far from accurate. Luckily, I have created similar shapes with code before, so I
started sketching in p5.js.

![](/media{{ page.url }}20230923-sine-cam-in-p5js-web-editor.jpg)

I started with just a cam, and then added a vertical shalf and its trace to better illustrate the movement.

![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-1-cycle.gif)

I also tried cams whose full cycle translates to multiple cycles of a sine wave.

![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-2-cycles.gif) | ![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-3-cycles.gif)

I think these ones are going to be helpful when I need to combine sine waves of different frequencies. For now, the first one, which has the smallest dimple, should be the easiest to fabricate and also most likely to create least amount of frication when interacting with a shalf. Hence, I exported a high resolution picture of the cam and adjusted it to desired dimensions in Adobe Illustrator before it was sent to print.

![](/media{{ page.url }}20230923-sine-cam-layout-in-adobe-illustrator.jpg)

With the help of the printed cam outlines, I was able to cut more than 20 pieces of cams from cardboard.

***I will update this post with more details on the cardboard prototyping process later. For now, let's take a look at this semi-finished result:***

![](/media{{ page.url }}20230924-ZVE03517.jpg)

This helped me prove the basic idea, and it also convinced me wood would make it work much more reliably.

***I will also add more details on the woodworking process too. Stay tuned!***

![](/media{{ page.url }}IMG_9149.jpg)

![](/media{{ page.url }}IMG_9153.jpg)

![](/media{{ page.url }}IMG_9154.jpg)

![](/media{{ page.url }}IMG_9170.jpg)

![](/media{{ page.url }}IMG_9176.jpg)

Here is how it looked when fully assembled:

![](/media{{ page.url }}20230924-ZVE03616.jpg)

![](/media{{ page.url }}20230924-ZVE03606.jpg)

![](/media{{ page.url }}20230924-ZVE03582.jpg)

![](/media{{ page.url }}20230924-ZVE03635.jpg)

This is how it worked as stop-motion animation:

![](/media{{ page.url }}sine-cam-with-colorful-pencils-animated.gif)
