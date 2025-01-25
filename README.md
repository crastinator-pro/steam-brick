# No screen, no controller, and absolutely no sense, just a power button and a USB port.

![Steam Brick image showing discarded components from Steam Deck](https://github.com/crastinator-pro/steam-brick/blob/main/images/header.jpg?raw=true)

# But… Why?

TL;DR Well, the Steam Deck didn’t fit in my backpack…

The Steam Deck [link] has been a game changer for travel, but I found myself leaving it behind more often than not, as it wouldn’t fit in my backpack, took up a huge amount of carry-on space, and was a hassle to bring down from the overhead compartment when I wanted to use it.
When I did use the Deck, it was either plugged in to AR Glasses ([XReal Air 2 Pro]( https://amzn.to/3CpmMgW)) or plugged in to a TV. So, I got to thinking: it could be so much smaller and lighter without the build in controller and screen, but that would be ridiculous, right? …right?

# ⚠️ Disclaimer 
“I am not a smart man”

This project was not approved or endorsed in any way by Valve and is generally a very bad idea. I’m honestly surprised it worked and have no idea how long the modified console will survive. The following is provided “as is” and without any expressed or implied warranty. If you choose to attempt this do so at your own risk. Be warned that are likely to “brick” (as in destroy, but pun intended) your console and you might get hurt in the process (lithium batteries and power tools are dangerous, among other things).

This is not a guide, more of a “how I did it”. If there’s enough interest, I might expand this to a more step-by-step style write-up. Until then, feel free to reach out via the Issues [link] page or on reddit [link] if you have any questions. If you’d like to support the project, consider using the affiliate links included on this page.

# Getting Started
 
![Meme: "screens? where we're going we don't need screens!"](https://github.com/crastinator-pro/steam-brick/blob/main/images/meme.jpg?raw=true)

First of all – huge shoutout to iFixIt for their great [Steam Deck Repair Guides]( https://www.ifixit.com/Device/Steam_Deck) as well as to Valve for supporting the DIY repair and mod community!

This mod was performed on a [1TB OLED Steam Deck](https://amzn.to/40MP0f7), there are some differences between the OLED and LCD models.

The first hurdle on this ridiculous road was figuring out if the Steam Deck would even boot without any peripherals or a screen attached. Working off the [battery replacement]( https://www.ifixit.com/Guide/Steam+Deck+Battery+Replacement/149070) and [motherboard replacement]( https://www.ifixit.com/Guide/Steam+Deck+Motherboard+Replacement/148928) tutorials was able disconnect everything from the motherboard other than the fan – success!
In this state the Deck will boot output display over USB and accept peripherals via an external dock.

 ![POC: Deck running with bare motherboard](https://github.com/crastinator-pro/steam-brick/blob/main/images/poc.jpg?raw=true)

# Internals

This initial teardown also revealed a useful aluminum(?) frame, unfortunately, you’ll have to remove the screen [link] to remove it from the shell. This shell had some unnecessary “wings” so of course they had to be removed with a rotary tool. With the excess metal removed, I had the perfect internal frame for the Brick.

Note that some of the fan and motherboard cover screws are outer-shell screws which must be added back so everything is properly held in place.
 
![Internal frame](https://github.com/crastinator-pro/steam-brick/blob/main/images/frame.jpg?raw=true)
![Cutting](https://github.com/crastinator-pro/steam-brick/blob/main/images/cutting.jpg?raw=true)
![removed material](https://github.com/crastinator-pro/steam-brick/blob/main/images/removed_metal.jpg?raw=true)

I probably should have removed or masked out the fan before grinding away the metal…

# Case

Using my limited CAD abilities, I designed a rudimentary shell for the Brick. The shell has two pegs to align the board and you can add a dollop of PLA with a 3d printing pen to further secure the board to the case. There’s a cutout in the case to accommodate the original power button, and the air intake is sized to accept the metal grill from the original back shell.

I printed out the case in Overture Polycarbonate Pro (PC) [link] which _should_ be  heat-resistant enough not to melt while the deck attempts to run Cyberpunk 2077. Color accents were added in PLA with a 3D printing pen.
 
![CAD Model](https://github.com/crastinator-pro/steam-brick/blob/main/images/model1.jpg?raw=true)
![Cutting](https://github.com/crastinator-pro/steam-brick/blob/main/images/model2.jpg?raw=true)
![CAD Model](https://github.com/crastinator-pro/steam-brick/blob/main/images/internals.jpg?raw=true)
Note: The 3rd antenna is missing in this photo, which I reattached later.
 
# Result

![Result and setup](https://github.com/crastinator-pro/steam-brick/blob/main/images/IMG_3315.jpg?raw=true)

And there it is, in all its glory: the Steam Brick!
About a 3rd of the size of the Deck, and about 4 times smaller than the Deck’s OEM case. As a bonus, it’s also 24% lighter!

 
# FAQ
**Why remove the screen? It wouldn’t have made the build larger!**

Keeping the screen would have significantly complicated the build, as you’d need something to keep in in place. More importantly – the brick was built to be tossed in a bag as-is. No case, no screen protector, just throw it in a backpack or suitcase and don’t worry about it!

**Why did you do this again?**

Because I was too so preoccupied with whether or not I could that they didn't stop to think if they should.

# Known Issue
- Accessing the BIOS is currently impossible as it requires holding down the ‘+’ button while powering up, and that button isn’t included in the build. Haven’t found a workaround yet.
- It’s difficult to tell if the Brick is on or not – as the Deck’s indicator light doesn’t indicate on/off status

# Resources
STL Files for case

# Affiliate Links
Want to support this project? Get your hardware here:
- [1TB OLED Steam Deck](https://amzn.to/40MP0f7)
- [XReal Air 2 Pro](https://amzn.to/3CpmMgW)
- [Virtue Pro XR](https://amzn.to/3PNvIjk)
- [iFixit Pro Tech Toolkit]( https://amzn.to/42ukCHr)
- [LTT Driver]( https://www.lttstore.com/products/precision-multi-bit-screwdriver-bundle) (non-affiliate, but love it!)
- [POWERWORKS Rotary Tool](https://amzn.to/3CxhhNd)

# License 
This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

![CC BY-NC 4.0](https://img.shields.io/badge/license-CC--BY--NC--SA--4.0-lightgrey)
