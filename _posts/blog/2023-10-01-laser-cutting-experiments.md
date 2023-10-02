---
layout: post
title: Laser Cutting Experiments
categories: blog
tags: itp introduction-to-fabrication
description: 
published: true
---

This week, I have been experimenting with laser cutting. I wanted to continue incorporating computational thinking into my process, so the first thing I thought of was to create a p5.js sketch for the laser cutter. While p5.js usually only renders raster images, laser cutter requires a vector file to perform cutting. Although raster files can still be used for engraving, I think it would be more interesting to generate a path for cutting.

After some research, I found [an open-source project](https://github.com/zenozeng/p5.js-svg) that provides a SVG runtime for p5.js. In order to use it in a p5.js project, first include `<script src="https://unpkg.com/p5.js-svg@1.5.1"></script>` in the index.html file.

![](/media{{ page.url }}20230929-p5js-svg-setup-script-tag.png)

Then specify SVG as the renderer in `createCanvas()`.

![](/media{{ page.url }}20230929-p5js-svg-setup-specifying-renderer.png)

Now, everything we draw in p5.js will be rendered as a SVG element.

![](/media{{ page.url }}20231002-p5js-svg-setup-web-inspector.png)

After some experiments with this SVG runtime, I decided to try it out with one of my old sketches, which converts any reference image to a drawing formed by scribbles (in the sketch below, the reference image is a QR code). To my surprise, it worked right away after doing the steps above.

![](/media{{ page.url }}20230930-p5js-web-editor-svg-experiment-scribble-filter-jackbdu-instagram-qr-code.png)

I did not yet find any easy way to export it to a SVG file, instead, I grabbed the SVG code directly from the web inspector and pasted it into a blank .svg file. Once I had the SVG file, I could then edit it however I like. In my case, I was using Adobe Illustrator.

![](/media{{ page.url }}20231002-illustrator-svg-experiment-scribble-filter-jackbdu-instagram-qr-code.png)

<table style="width: 100%;">
  <thead><tr><th>
    <video controls width="100%" preload="auto" poster="">
      <source src="/media{{ page.url }}IMG_9353.mp4" type='video/mp4'>
    </video>
  </th></tr></thead>
  <tbody><tr style="text-align: center;"><th></th></tr></tbody>
</table>

![](/media{{ page.url }}20230930-p5js-web-editor-svg-experiment-scribble-filter-three-petal-flowers.png)

![](/media{{ page.url }}20230930-illustrator-svg-experiment-scribble-filter-three-petal-flowers.png)

![](/media{{ page.url }}20230930-p5js-web-editor-svg-experiment-scribble-filter-jackbdu-self-portrait-16x16.png)

![](/media{{ page.url }}20231001-ZVE03798.jpg)

![](/media{{ page.url }}20230930-p5js-web-editor-svg-experiment-scribble-filter-jackbdu-self-portrait-32x32.png)

![](/media{{ page.url }}20231001-illustrator-scribble-filter-jackbdu-self-portrait-32x32.png)

![](/media{{ page.url }}20231001-epilog-dashboard-scribble-filter-jackbdu-self-portrait-32x32-outline-with-custom-settings.png)

![](/media{{ page.url }}20231001-epilog-dashboard-scribble-filter-jackbdu-self-portrait-32x32-scribbles-with-custom-settings.png)

![](/media{{ page.url }}IMG_9399.jpg)

<table style="width: 100%;">
  <thead><tr><th>
    <video controls width="100%" preload="auto" poster="">
      <source src="/media{{ page.url }}IMG_9401.mp4" type='video/mp4'>
    </video>
  </th></tr></thead>
  <tbody><tr style="text-align: center;"><th>
  </th></tr></tbody>
</table>

![](/media{{ page.url }}20231001-ZVE03686.jpg)

![](/media{{ page.url }}20231001-ZVE03835.jpg)

![](/media{{ page.url }}20231001-ZVE03731.jpg)

![](/media{{ page.url }}20231001-ZVE03746.jpg)
