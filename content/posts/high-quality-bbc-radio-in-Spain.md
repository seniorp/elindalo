---
title: "High Quality BBC Radio in Spain"
date: 2020-02-04T09:48:36+01:00
draft: false
omit_header_text: true
featured_image: "/images/radio.jpg"
---

When you are abroad the BBC limit the radio you can receive via iPlayer to lower bandwidth streams.  However every BBC radio station has a high quality stream which is only available in the UK.  Even there, these are not widely advertised.

I managed to get mine going in the south of Spain, and I think these will work anywhere in the world.

A VPN or tunnel will generally not work.  I needed a smart DNS and links to the streams.  I also needed to stop my DNS from contacting the BBC via any route other than the smart DNS.

I set up my router (which is an Asus AC68U) so that my connection to the Internet ("WAN") does not use the DNS of my ISP, but instead the DNS of the smart DNS.  Each device must connect to the router and use the router for its DNS.  Then one just needs to connect to the streams.
