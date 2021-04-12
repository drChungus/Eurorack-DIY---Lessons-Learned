# Eurorack DIY - Lessons Learned
 Lessons learned on the Eurorack DIY journey

## Foreword
As Adam Savage from MythBusters once said: 
> “The difference between screwing around and science is writing it down.”
> *Adam Savage*

It took me a few years to really grasp this idea, but here we go now. I am an engineer with a master's degree in mechatronics, so documenting my work is not a new thing for me. However, as modular synths and other fun electronic projects are basically a hobby for me I was not putting much effort into documenting those. Furthermore, I see people rather show off the end result of their work, but the endless nights of debugging and face-palming down the road are not often advertised. 
Building your own modules is tough, either you have previous experience with making such devices or not. This document is supposed to serve as a jump start for newbies and also sort of a knowledge base for experienced builders. This way experiences of an individual can be easily shared out to shorten others' learning curve, helping them avoid mistakes already made and equip them with knowledge previously discovered.

## Read this first!
Finding tutorials on how the building process should be performed is not a hard task nowadays, thus I dill not go into too much details on this topic. 
I usually avoid kits as I feel confident ordering PCBs and parts on my own, but if you are new to this I would advise starting off with a full kit for the first time. 
When it comes to SMD, I see many people tend to stay away from it. Allow me to list some pros and cons with surface mount technology:

### Advantages:
* Cheaper components
* Modern industry standard, better availability (with most of the parts)
* Smaller component outline - smaller modules, less HP, cheaper PCB 
* More compact storage of parts
* Easier to replace wrong parts already soldered
* Faster to build with hand soldering
* Can be built with re-flow method

### Disadvantages:
* Small parts are harder to see/handle
* Parts can be lost (squeeze to hard and it is gone forever)
* More tools are needed, like better iron, tweezers, solder braid, flux, etc...
* Magnification is recommended when performing build

I was drawn into the world of SMD by a college of mine, and I can verify that once you go surface mount you will not come back to THT. All in all I see many builders avoid it without even trying, so I recommend you give it a go at some point (if you can handle basic soldering). 

For me ideally the process should have the following steps:
1. Resource ingredients from multiple places
  * PCB and Front Panel
  * Passives/Generic electronics
  * Application specific ICs and parts
  * Front panel and IO (jacks, pots, LEDs, switches, etc..)

I can not recommend a best place to get all these as this might be different based on your location, but I recommend you discover the possible places to get these.

2. Waiting for delivery

Yeah, it takes a while to get all the stuff, I usually spend this time double checking if my resourcing covers everything and also maintain a record of what do I have in stock.

3. Building 
You should do this after you have the parts delivered. Never rush a build and never push yourself too much as the final result will suffer from it. Take your time, pop up some smooth jazz or some podcast and proceed in your own tempo. Take regular breaks, and stop if you feel exhausted!

4. Smoke test