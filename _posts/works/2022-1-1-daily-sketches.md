---
layout: post
title: Daily Sketches
categories: works
tags: p5js glsl web featured
description: A collection of computational sketches I created with code in the year 2022.
---

[ [View sketches on Instagram](http://instagram.com/jackbdu/) \| [View source code in p5.js Web Editor](https://editor.p5js.org/jackbdu/sketches) ]

<!--more-->

<table style="width:100%">
  <thead><tr><th>
    <div style="padding-bottom:56.25%; position:relative; display:block; width: 100%">
      <iframe width="100%" height="100%" src="https://player.vimeo.com/video/830839700?h=8291bea6ce" style="position:absolute; top:0; left:0;" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
    </div>
  </th></tr></thead>
  <tbody><tr style="text-align: center;"><th>
  A compilation video showcasing select sketches
  </th></tr></tbody>
</table>

As a new year resolution, I challenged myself to create and post computational sketches on social media every single day starting on January 1st, 2022. I use it as a way to journal, turning ideas, memories, and everyday events into expressive visuals. Some visuals are in simple geometric shapes and representational forms, some are in generative, repetitive, and abstract patterns, others are combinations of both. Most sketches are either still images or short animations, and the rest are interactive. The interactive ones are what I call virtual mirrors, which are sketches that are dynamically rendered in real time based on the presence of viewers. The images and motions of the viewers are first captured by a video camera, and then reinterpreted by the code that I wrote before shown to the viewers.

![Screenshot of my Instagram posts, featuring vibrantly colorful daily sketches I created](/media{{ page.url }}screenshot-of-jackbdu-instagram.jpg) |
:----------: |
Screenshot of [my Instagram](https://www.instagram.com/jackbdu/) posts |

Most sketches started with a simple idea—a single circle, a blob, or some random scribbles. I would then spend anytime from a few days to a few weeks on these ideas by making incremental changes every day, altering colors, sizes, rotations, number of repetitions, etc. These changes often lead to unexpected results that are even surprising to me. Doing these sketches helped me practice my old coding skills as well as pick up many new techniques. It has also been a great source of inspiration for future project ideas.

Below I am showing a selection of my daily sketches based on different techniques I used.

## Scribbles

Some of the first daily sketches I created were inspired by drawings created by [Minus E](/works/minus-e/), a robotic drawing system I built in 2017. Essentially, these sketches were a recreation of Minus E's drawing style, forming images with a single thread of scribble that clusters in different densities at different spots. No longer constrained by hardware and time limitations, what surprised me the most was how easily I could bring these sketches to life by animating them.

![Linear gradient formed by a grid of white scribbles of different densities on black background](/media{{ page.url }}20220102-linear-gradient.jpg) | ![Self-portrait formed by a grid of colorful scribbles of different densities on white background](/media{{ page.url }}20220105-cmyk-young-jackbdu.jpg) | ![An abstract portrait formed by a grid of white scribbles of different densities on black background](/media{{ page.url }}20220107-monochrome-slanted-curve-short-infinite-loop.gif)
:----------: | :----------: | :----------:
Sketch on January 2, 2022 | Sketch on January 5, 2022 | Sketch on January 7, 2022
[ [View post on Instagram](https://www.instagram.com/p/CYOergphFY1/) ] | [ [View post on Instagram](https://www.instagram.com/p/CYWGTULBSrD/) ] | [ [View post on Instagram](https://www.instagram.com/p/CYaHPxBBCQu/) ]

Near the end of the year, I revisited this idea by recreating a similar [digital painting style](/works/digital-self-portraits/) I experimented with in 2019. Again, I was pleasantly surprised by the ability to animate as well as the flexibility of experimenting with different ways to connect the scribbles. In the end, I turned it into a virtual mirror that constantly regenerates new images in real time based on the presence of a viewer.

![Linear gradient formed by a grid of black zigzag scribbles of different densities on white background](/media{{ page.url }}20221129-scribble-linear-graident.jpg) | ![Mona Lisa formed by a grid of colorful zigzag scribbles of different densities in different orientation on white background](/media{{ page.url }}20221205-scribble-filter-cmyk-mona-lisa.jpg) | ![A portrait formed by rows of connected black scribbles of different densities on white background](/media{{ page.url }}20221213-symmetrical-long-scribble-filter-single-color-webcam-mirror-16x16-lifting-hair.gif)
:----------: | :----------: | :----------:
Sketch on November 29, 2022 | Sketch on December 5, 2022 | Sketch on December 13, 2022
[ [View post on Instagram](https://www.instagram.com/p/ClivVW4rj9W/) ] | [ [View post on Instagram](https://www.instagram.com/p/ClzKQwHpHYu/) ] | [ [View post on Instagram](https://www.instagram.com/p/CmIBzGdB0yz/) ]

## Repetitions

One other series of experiments I did was with repetition. I started off with simple repetitions of small hollow circles in a spiral pattern. Iterations after iterations, I realized the pattern became much more interesting as repetitions were more ordered and as gaps between hollow contours got smaller.

![A spiral of hollow circles, small yellow circles near the center gradually transitioning into larger blue circles near the edges of the frame](/media{{ page.url }}20220409-green-to-blue-animated-spiral-hollow-circles-on-dark-background-still.jpg) | ![Multiple spirals of heavily-overlapped yellow round-corner squares in an arranged with a radial look](/media{{ page.url }}20220411-yellow-animated-spiral-hollow-squares-on-dark-background-still.jpg) | ![Three threads of heavily-overlapped round-corner squares arranged with a radial look, green near the center, blue near the edges](/media{{ page.url }}20220415-three-animated-green-to-blue-spiral-springs-still.jpg) |
:----------: | :----------: | :----------:
Sketch on April 9, 2022 | Sketch on April 11, 2022 | Daily Sketch on April 15, 2022
[ [View post on Instagram](https://www.instagram.com/p/CcI-WLZL8kO/) ] | [ [View post on Instagram](https://www.instagram.com/p/CcOY3P2rY5D/) ] | [ [View post on Instagram](https://www.instagram.com/p/CcYqJzGrRiV/) ]

When gaps were completely eliminated, seamless color gradients were formed, which gave these sketches a very natural look. Afterwards, I also experimented with using Perlin noise to generate more organic shapes and then overlapping shapes by different amounts.

![Two light purple blue shells slightly-twisted around each other](/media{{ page.url }}20220417-two-animated-purple-shells-still.jpg) | ![Two intertwined shell-like structures in color gradient, from white near their center to navy, then red orange near the edges](/media{{ page.url }}20220421-animated-red-to-blue-flower-still.jpg) | ![Five interwined curly pedals in a repeating color gradient, from orange, to white, to blue, and then back to orange](/media{{ page.url }}20220424-animated-colorful-flower-still.jpg) |
:----------: | :----------: | :----------:
Sketch on April 17, 2022 | Sketch on April 21, 2022 | Sketch on April 24, 2022
[ [View post on Instagram](https://www.instagram.com/p/Ccd3dlNrWpC/) ] | [ [View post on Instagram](https://www.instagram.com/p/CcoKDVvr9W1/) ] | [ [View post on Instagram](https://www.instagram.com/p/Ccvopnjr3Sl/) ]

When I revisited this idea four months later, I decided to go with a more flowery look.

![Two flowery curly purple petals slightly-twisted around each other](/media{{ page.url }}20220817-animated-light-purple-two-petal-flower-still.jpg) | ![A flower-like visual with interwined 7 light blue petals](/media{{ page.url }}20220821-animated-light-blue-seven-petal-flower-still.jpg) | ![Three flowery petals interwined, in color gradient from navy near the center to hot pink near the edges](/media{{ page.url }}20220823-animated-magenta-three-petal-flower-still.jpg) |
:----------: | :----------: | :----------:
Sketch on August 17, 2022 | Sketch on August 21, 2022 | Sketch on August 23, 2022
[ [View post on Instagram](https://www.instagram.com/p/ChWpFj5OG89/) ] | [ [View post on Instagram](https://www.instagram.com/p/ChgbiSYMzKL/) ] | [ [View post on Instagram](https://www.instagram.com/p/Chmp_MirW8z/) ]

Similarly, I experimented with repeating circles in a more circular fashion, which rendered some very different results.

![](/media{{ page.url }}20220429-negative-blob-from-colorful-circles-v2-fast.gif) | ![](/media{{ page.url }}20220503-balloon-blob-from-red-hollow-circles.gif) | ![](/media{{ page.url }}20220506-color-changing-blob-v3.gif) |
:----------: | :----------: | :----------:
Sketch on April 29, 2022 | Sketch on May 3, 2022 | Sketch on May 6, 2022
[ [View post on Instagram](https://www.instagram.com/p/Cc8cssErMR3/) ] | [ [View post on Instagram](https://www.instagram.com/p/CdGJl9ZsJqd/) ] | [ [View post on Instagram](https://www.instagram.com/p/CdO0WhaL54v/) ]

## Shaders

Another series of sketches were experiments with [shaders](https://en.wikipedia.org/wiki/Shader). Since this was my first time writing shaders in p5.js, I found [this tutorial](https://itp-xstory.github.io/p5js-shaders/) to help me get started, which turned out to be very helpful. I did a few different glowing sketches before unexpected results started to appear.

![](/media{{ page.url }}20220722-ten-glowing-rainbow-circles-in-a-circle-still.jpg) | ![](/media{{ page.url }}20220724-16-glowing-colorful-circles-in-a-circle-still.jpg) | ![](/media{{ page.url }}20220725-rotating-colorful-bubbles-in-a-circle-v2-still.jpg)
:----------: | :----------: | :----------:
Sketch on July 22, 2022 | Sketch on July 24, 2022 | Sketch on July 25, 2022
[ [View post on Instagram](https://www.instagram.com/p/CgUJBfiLlk1/) ] | [ [View post on Instagram](https://www.instagram.com/p/CgYVuFhMnzF/) ] | [ [View post on Instagram](https://www.instagram.com/p/CgbORLNg9Qu/) ]

After I drastically increased changes in color, the glowing effect intensified and colors became very saturated, which resulted in an interesting transition between colors. Multiple dispersed glowing spots started to look like fluids.

![](/media{{ page.url }}20220730-many-many-colorful-abstract-shapes-still.jpg) | ![](/media{{ page.url }}20220802-colorful-abstract-fluid-v2-still.jpg) | ![](/media{{ page.url }}20220803-yellow-and-blue-abstract-symmetrical-fluid.gif)
:----------: | :----------: | :----------:
Sketch on July 30, 2022 | Sketch on August 2, 2022 | Sketch on August 3, 2022
[ [View post on Instagram](https://www.instagram.com/p/CgnvZtHslDd/) ] | [ [View post on Instagram](https://www.instagram.com/p/CgwEyhWuMio/) ] | [ [View post on Instagram](https://www.instagram.com/p/CgzB-ZELZ3s/) ]

Later this year, I used shaders to create organic repetitive patterns.

![](/media{{ page.url }}20220930-black-and-white-fluids-v2-still.jpg) | ![](/media{{ page.url }}20221008-colorful-repetitive-pattern-still.jpg) | ![](/media{{ page.url }}20221019-colorful-wavy-pattern-fast.gif)
:----------: | :----------: | :----------:
Sketch on September 30, 2022 | Sketch on October 8, 2022 | Sketch on October 19, 2022
[ [View post on Instagram](https://www.instagram.com/p/CjIRqMCrZXh/) ] | [ [View post on Instagram](https://www.instagram.com/p/CjcX0JyD-F0/) ] | [ [View post on Instagram](https://www.instagram.com/p/Cj6PkTtrdpp/) ]

These are just a few examples of the ideas that I explored in 2022. To view all my daily sketches, please [visit my Instagram](http://instagram.com/jackbdu/). I will keep creating and posting daily sketches in the coming years.

## Exhibitions

2023 \| **React Summit Conference**, Amsterdam, Netherlands

2023 \| **JSNation Conference**, Amsterdam, Netherlands
