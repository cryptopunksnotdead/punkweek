---
title: "artbase - Zero-Config (Web) Server / Services Update - What's News? Scalable Vector Grapics (SVG) Format Support - Yes, Turn Your Punks, Cool Cats, And More Into High-Quality XXL Posters w/ Crisp Edges"
---


A follow-up to [**artbase - Zero-Config (Web) Server / Services Update - What's News? Philip! Phree the Phunks! And Yes, Use Your Own Background Colors (V1, V2, V3) And More**](https://old.reddit.com/r/CryptoPunksDev/comments/somirg/artbase_zeroconfig_web_server_services_update/) I added some more web services. What's news?

1) Turn any pixel art (punks, cool cats & more) into high-quality xxl posters w/ crisp edges

<!-- more -->

Let's try the $20+ million punk #5822  - `/punks/5822.svg`
(see above text-encoded in the scalable vector graphics format).

How does the text-encoding work? Pixels get "encoded" as rectangle "shapes" with a width and height
of one (1×1).  Transparent pixels
with the red/green/blue/alpha (rgba) value of (0 or 0/0/0/0)
get dropped.


That's it for now. Find out more at [**artbase - the (web) server / service edtion**](https://github.com/pixelartexchange/artbase.server).

Questions and comments welcome.
