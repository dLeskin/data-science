# data-science
CAPSTONE project









































CV minutes
Designer for micro-optics, displays
Название компанииNanocomp Oy Ltd. Регион компании Eastern Finland, Finland



The main tasks include the designing light guide illumination for displays based on complex micro-optical structures. You will work as part of our design team and support our marketing and sales team in product and production concept development tasks. You should possess a suitable educational background, knowledge of micro-optics design software and tools, solid practical experience preferably in industry, as well as a strong team spirit. English skills, including knowledge of special optics terminology, are essential.


Inquiries concerning the positions should be directed to Veli-Pekka Leppänen, tel. +358 400 127 680 or veli-pekka.leppanen@nanocomp.fi.

To do:
1. launch pychram to show color analysis
2. Data science certificate and computer vision courses
3. check skype and RDP




To tell:
Name Velli-Pekka, Matti?

Right now I-m optical engineer at lighting technologies. This is one of the top lighting mass production company in our region and we have also factories in India, Spain and Ukrane.
I enered here 7 years ago and gained huge expreince both in calculating and manufacturing optics and lighting fixtures too.
Now I have over 30 completed family projects and two assistants to coordinate. All LED-based products optics on web-site is desinged by me. So if you are interested I can describe any of them in tiny details.

Initially we were bying optics from LEDIL and some other suppliers. I belive you are familiar with LEDIL guys, they made really good business. I-ve visited their place in Salo. Unfortunately most of production moved to china too. So, it was about 1 million $ per year spent on purchasing optics. I believe that my biggest achivement is that I moved company from totally buying to mainly manufacturing optics at our factory. So cost reduced by more than 10 times.

Let me briefly describe the desing process and tools I use today:
1) For secondary optics for first order calculation with a point source assumption I use mathcad and visual basic. I create target-source mapping in spherical or UV coordinate systems. Check conservation of etendue to get the idea about the size. Then upload it to solidworks to check and modify the geometry. I made a routine in VBA that uses Solidworks API to automate this process. Next by bridge I send the geometry to Lighttools or Tracepro to simulate and analyze. After that I rebuild the geometry in optical software to parametrize and run optimization with LED file source. At the end of the design process I choose photoetcheing or lenslet microstructure to properly mix the color. I check all photometric , colorimetric, mechanical tolerance and visual parameters. Analyze manufacturing restrictions, choose the tooling supplier. Usually I order tooling(molds & extrusion) from Italian (good price\quality ratio) And it looks like they are in love with machines. Chinese are good at tuning the technology.
2)Also I work with laser machine for laser guide panels. It took a while to adjust our beam-splitter and laser power to get proper dot geometry (it is droplet), and choose the right acrylic supplier. For simple cases like square or rectangular shape I use embedded software to adjust density and dot size. For more complex shapes I used Lightools optimizer, now I have to use Tracepro texture optimizer for calculation of the pattern, add sinusoidal shift and spreading structure near LEDs sources. So we have successufully launched LGP luminaire family.
Before I also got some experience with silk-printing for signage application. But white ink is not UV stable.

3) We tried to get into automotive industry for headlamps and lightguides together with major LED supplier. I made some designs for showcase but we didn-t manage to sell our service. It-s a tricky business there. Just production is not enough.

4) For all this I have coded some tools:

Like I mentioned before I-ve developed tool for building by solidworks the optical geometry based on needed illumination and angle or specified light distribution.
 Implemented photometry file storage system and file converter to website database; in lighting industry we use ies&ldt text files.
 Provided luminaire LDT analysis tool on web-site (Russian version); it represents luminaire data and distribution graphs plus photobiological level of blue hazard to your eyes. 

 Developed image analysis tool (by OpenCV) and method for light-beam photos
comparison. And presented it at LPS LED Symposium LINK;
Motivation: LEDs are really non-uniform from color point of view. Their Angular and spatial distribution sometimes impossible mix by just lens. 
During any project you have to comfirm visual beam effect from your optics+LED combination inside your team. Since I work for each project in company I have to do lots of coparison at real life with real people. And due to emotional aspects their perception is not objective.
So I made a digital tool for simulataneous comparison of many photos. The program finds non-uniformity at each photo, draw a countour according to HSV values set by a user and helps to count where is the best result in area or gradient.

By the way it is possible to implement for lightguides in case of some chromatic effects due to diffraction or analyzing luminance uniformity. Similar tools has konica minolta but they made it for absolute measurement, my tool is xactly for relative and you can use just photo by your phone.


5) In addition I design all mechanical parts for prototyping and choose LED according to light charactistics. Especially to color distributions.


Impressed by features:
1. 30 deg FWHM and good field angle. It is easy to get by regular. lens, but not by a stretched surface.

skew rays

Questions:
IQ structure in prague, brightview, whiteoptics(alanod machines suits roll2roll).


three projects:
-launched first lens project
-launched LGP machine
-developed color analysis tool

experience:
calculation
manufacturing
programming
