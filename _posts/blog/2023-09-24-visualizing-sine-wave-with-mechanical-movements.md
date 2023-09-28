---
layout: post
title: Visualizing Sine Wave with Mechanical Movements
categories: blog
tags: itp introduction-to-fabrication fabricating-mechanical-automatons
description: 
published: true
---

I have been making and posting daily creative coding experiments (on my [Instagram](https://www.instagram.com/jackbdu/)) for almost 2 years now. One of the mathematical functions that keep coming back is a sine function (such as in the sketch below, which utilizes a combination of sine and cosine functions). As I have been studying fabrication techniques and mechanical movements recently, I had this idea of creating an automaton that visualizes a sine wave.

![](/media{{ page.url }}20230803-v2-animated-thin-long-curve-512x512@15fps.gif){: width="50%"} |
:---: |
Sketch on on August 3, 2023 |
[ [View post on Instagram](https://www.instagram.com/p/CvfJJ54BF6h/) ] |

One of the mechanisms that I recently learned is called [cam](https://en.wikipedia.org/wiki/Cam), which is commonly used to transform rotary motion into linear motion. I tried imagining and sketching what a cam would look like if the linear movement it produces follows a sine wave. I started with a regular sine wave, and tried to wrap it around a circle. While it gave me a general idea of what it might look like, it was far from accurate.

![](/media{{ page.url }}20230925-sketches-of-sine-cam.jpg)

Luckily, I have created similar shapes with code before, so I was able to quickly sketch out a much more accurate contour in p5.js.

![](/media{{ page.url }}20230923-sine-cam-in-p5js-web-editor.jpg)

I started with just a cam, and then added a vertical shalf and its trace to better illustrate this movement.

![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-1-cycle.gif)

I also tried cams whose own full rotation produces multiple cycles of a sine wave.

![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-2-cycles.gif) | ![](/media{{ page.url }}20230923-fab-experiment-rotating-sine-cam-3-cycles.gif)

I think these ones are going to be helpful when I need to combine sine waves of different frequencies. For now, the first one, which has the smallest dimple, should be the easiest to fabricate and also most likely to create least amount of frication when interacting with a shalf. Hence, I exported a high resolution picture of that cam so that I could adjust it to my desired dimensions in Adobe Illustrator before it was sent to print.

![](/media{{ page.url }}20230923-sine-cam-layout-in-adobe-illustrator.jpg)

With the printed reference in hand, I started to work on a cardboard prototype. I found a large thick cardboard box, which ended up being my sole cardboard source.

![](/media{{ page.url }}IMG_9115.jpg)

For the first few cam pieces, I started by scoring the outline with a small flat-head screwdriver, then cut and trimmed the piece with a utility knife until it was as close to the reference as possible.

![](/media{{ page.url }}IMG_9117.jpg) | ![](/media{{ page.url }}IMG_9116.jpg)

Very quickly, I became impatient and started stacking and cutting multiple pieces of cardboard at the same time.

![](/media{{ page.url }}IMG_9118.jpg) | ![](/media{{ page.url }}IMG_9120.jpg)

That really helped speed up the process. I was able to make about 23 cams in a relatively short period of time, even though I did have to go back and trim some of them a bit more so that the sides are as even as they could be.

![](/media{{ page.url }}IMG_9123.jpg)

The next step was to look for a rod (Yes, I did not have a rod. I sort of went with it without much planning). Tres, who just finished his automaton prototype, was kind enogh to lend me one of his wooden rod, and I also picked up another broken one that he persumably disposed of. Since we were discouraged to use any power tool, I manually made holes for all of the cams with a drill bit.

![](/media{{ page.url }}IMG_9125.jpg)

Looking good! Time to hot glue them together! I found the gluing process very satisfying, maybe it was because I have not worked on a physical piece for a very long time. It also felt so special to see this repetitive pattern coming together physically, as I have only experimented with repetition in digital forms.


![](/media{{ page.url }}IMG_9126.jpg)

At this point, I needed build a structure to hold the rod. It was such a coincident that the unused portion of the cardboard box seemed to serve as a perfect base. I did some rough measurements and cut it into a shape that could be folded into a half-opening box.

![](/media{{ page.url }}IMG_9128.jpg)

After being fully assembled, it seemed to rotate pretty well. The cams alone were already creating a very interesting motion as they were rotated.

![](/media{{ page.url }}IMG_9130-1024x576@10fps.gif)

As a bonus, here are the scrap pieces that had been accumulating.

![](/media{{ page.url }}IMG_9137.jpg)

Finally, I needed to figure out what should go on top of the cams. My immediate thought was to have multiple short rods, which I did not have. I considered many different materials that I could find either at ITP or at [NYU MakerSpace](https://makerspace.engineering.nyu.edu/) right across the street, but none of them worked. Despite it was a rainy day, I eventually decided to go to Target, the closest department store, and I found some Twistables colored pencils. They are smooth throughout, at just about the right length, and they are colorful. All seemed to be good characteristics for my prototype.

![](/media{{ page.url }}IMG_9143-1024x576@10fps.gif)

After fighting with the rain and the wind, these pencils safely arrived at ITP.

![](/media{{ page.url }}IMG_9144.jpg)

I was so excited to try them out! I made a thick cardboard block and drilled holes to hold the pencils in place. It was impossible get it to work. The holes were either too tight for the pencils to move freely, or too loose for the pencils to stay straight. I had to switch to a wood block, hoping it would work better.

![](/media{{ page.url }}IMG_9145.jpg) | ![](/media{{ page.url }}IMG_9146.jpg)

The wood block definitely worked better, but with the amount of frication between the cardboard cams and the pencil, the mechanism kept getting stuck. My classmate, Josh, suggested that I should try increasing the touching surface. I did that by hot-gluing an extra piece of cardboard at the bottom of the pencil and it worked!

![](/media{{ page.url }}IMG_9147-1024x576@10fps.gif) |
:---: |
Me taking a video while holding the prototype and rotating the shalf, trying not to bother other people |

While the motion was far from perfect, this (mostly) cardboard prototype proved that my idea could work. It also convinced me that a wooden prototype would work much more reliably.

***I will add more details on the woodworking process too. Stay tuned!***

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
