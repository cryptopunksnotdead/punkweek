---
title: "How-To Turn Raster Graphics / Bitmaps One-Pixel At A Time Into High-Quality Scalable Vector Graphics (SVG) Drawing Instructions - Request For Comments"
---

  I am looking / researching how to turn small-ish (e.g 24×24 punks or cool cats) raster graphics / bitmaps
one-pixel at a time into high-quality scalable
vector graphics (svg) drawing instructions.

<!-- more -->

  The first "brute force" way I tried / copied is using (filled) rectangles with a width and height of one (1×1). See [**artbase - Zero-Config (Web) Server / Services Update - What's News? Scalable Vector Grapics (SVG) Format Support - Yes, Turn Your Punks, Cool Cats, And More Into High-Quality XXL Posters w/ Crisp Edges**](https://old.reddit.com/r/CryptoPunksDev/comments/stb0xd/artbase_zeroconfig_web_server_services_update/).

   Searching the internets I found comments such as:

> My script outputs one `<path>` for each color with a stroke of that color and the `d` attribute populated with `M[x],[y]h[line-length]` in place of each `<rect>`. So two pixels of black at `[0,1]` would be `<path stroke="#000" d="M0,1h2">`.
>
> Example:
>
>     <path stroke="#e8eef7" d="M0,0h35 M0,1h2 M33,1h2 M0,2h1  ... />
>     <path stroke="#cc0000" d="M2,1h31 M1,2h33 M1,3h33 M1,4h33 ... />
>     <path stroke="#ffe3e3" d="M7,5h1 M7,6h1 M7,7h1 M7,8h3  ... />

What's your style / approach?

Any tips and tricks or pointers on how-to turn raster graphics / bitmaps "loss-free" one pixel-at-a-time
into scalable vector graphics (svg) drawing instructions more than welcome.

