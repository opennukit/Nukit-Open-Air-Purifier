**About the Nukit Open Air Purifier**
---
Nukit Open Air Purifiers are Open Hardware devices for improving indoor air quality. They are designed to be used with North American standard HVAC filters and PC fans. They are often an improvement over commercial air purifiers as they are quieter per m3 CADR delivered, have a lower cost of ownership per year, and are easily repairable. 

![Nukit Open Air Purifier v1.0](https://github.com/opennukit/Nukit-Open-Air-Purifier/blob/main/Nukit-Open-Air-Purifier-3-v1.0.jpg?raw=true)

**General Guidelines**
---
* Nukit Open Air Purifiers are designed to be made with any 3mm or 1/8th inch material that is safe to laser cut. Care should be taken not to use materials prone to off-gassing.
* This is only an enclosure. In order to build a complete, functioning air purifier, you will need [2"x20"x20" MERV 13 furnace filters](https://www.amazon.com/Nordic-Pure-20x20x2M13-3-20x20x2-Pleated/dp/B005ESOXII), [140mm fans](https://www.amazon.com/gp/product/B07HCKWF2X), a [5.5mm barrel jack to 4-Pin PWM converter](https://www.amazon.com/DGZZI-5-5x2-1mm-Female-Supply-Adapter/dp/B085S3Q7VH), [fan grills](https://www.amazon.com/gp/product/B01BW21DXC), and a [12v power supply](https://www.amazon.com/gp/product/B07XMC6TF6) (suggested items linked).
* Regular yellow wood glue is sufficient. Polyurethane glue is somewhat stronger but significantly messier. Be sure to wipe up any excess glue with a damp sponge as you work, as hardened excess may prevent the filters from sliding in easily or the fans from sitting flush with the enclosure. If you miss a spot, it can be sanded flat or peeled off with a chisel.
* We suggest building the air purifiers on a glass tabletop for easy cleanup and to keep everything flat and square. Free-standing pieces can be held between two large food cans while the glue dries to keep them sufficiently vertical. Clothespins and thin rubber bands can be very helpful. The best results come from gluing one or two pieces to the base piece, allowing those to dry overnight, and then building the rest of the enclosure off of that firm structure.
* Once the glue is completely dry, a few light coats of sealant will ensure a service life of many years and prevent any issues with mold or mildew (although this should be checked with a flashlight when the filters are changed and the enclosure disposed of in the unlikely event of any growth- most laserply is treated). 
* Every effort should be made to use low VOC materials and finishes and allow them to fully cure before deploying the air purifier.
* Nukit Open Air Purifiers all come without a wiring port as different users prefer them in different locations. They are easy to add with [Inkscape](https://inkscape.org/), [QCAD](https://qcad.org/) or any vector editing or CAD software that can handle DXF files. Or just drill a hole where you like.
* To avoid confusion, all parts required to build a single air purifier unit are contained in a single DXF file. It is not optimized for cutting on any one machine; you will need to rearrange and remove some parts to fit your laser cutter and available material. [LightBurn](https://lightburnsoftware.com/) is the best software for this and is highly recommended. The time it saves quickly covers the cost.
* The "split" version of the DXF file in each repository is intended for a common 4060 CO2 laser cutter. A 600x600 laser diode cutter or a 6090 CO2 laser would likely not require any parts to be split- but check the actual cutting area of your machine.

The responsibility to safely deploy and use Nukit Open Air Purifiers lies entirely with the end user. Machinery Enchantress LLC offers no promises or warranties of any kind and is not liable for any mishaps that occur as a result of using these files.

**FAQ**
---
**Why would I build a DIY air purifier?**

Commercial stand-alone air purifiers follow the razor blade & inkjet printer business model. The profit is made by selling poorly built but attractively designed machines with motors that burn out within two years, cannot be serviced and require expensive proprietary filters that only fit that specific air purifier model. 

There is little money to be made, and none of it recurring, in building durable, repairable air purifiers that accept non-proprietary, standard HVAC filters, so the next best thing is to offer Open Source Hardware options.

Along with reducing e-waste, DIY PC Fan Air Purifiers usually have a substantially lower cost of ownership per M<sup>3</sup> CADR when in long-term operation.

**But aren't commercial air purifiers better?**

Often not- depending on your use case. The use of centrifugal fans allows for more pressure than radial fans but at the cost of far more noise. Manufacturers often deceptively list the highest CADR their product can achieve but at its average or lowest noise levels. By using arrays of repurposed radial PC fans, we can make up the pressure- with far less noise. Those fans can also easily and inexpensively be replaced as needed.

**Why laser cut material?**

As an industrial process, thin laser cut material is ideal when you need to make 5-500 of something (at which point you look at sheet metal or injection molded plastic). Hand-operated power tools are well suited to making one or two boxes like this but the time and labor required are substantial. Custom speaker enclosure builders can give you a quote for comparison as the specifications are very similar. Since most locations will require four or more air purifiers for full coverage, laser cutting is a very cost-effective option. The cost drops substantially as quantities go up, so group buys are an excellent idea.

**Will you make a version with...**

Hang on for a few weeks; we'll have an easy-to-use web app that will let you specify what sort of layout you want and then generate the files for you.

**I have ME/CFS, POTS, Long-COVID. Will I be able to do this?**

We think so, or let us know and we'll make changes so you can. Clear a work area that you can utilize for as long as you need- even days are fine. They key is you only need to glue one panel at a time- gluing all at once is for the impatient and offers little benefit. Spread your glue, place your piece firmly in the slots, wipe up excess with a damp sponge, close your glue, and return the next day, or even the next week- whenever you have the spoons for another piece. The entire assembly process can be broken into 5-minute segments.

**Did you invent this?**

Absolutely not, a ton of people did a massive amount of work on PC Fan Filter Boxes to get to this point, and laser-cut boxes have been around as long as laser cutters. We just posted a few handy Open Source designs people can easily have made. For some absolutely beautiful prior art (and decorative inspiration), check out [@Krytes42](https://twitter.com/Krytes42/status/1707808953911095305) on Twitter. 

**License**
---
All Nukit Open Air Purifiers are released under GPL-3. 
https://www.gnu.org/licenses/gpl-3.0.en.html

TLDR;
(For our purposes, “software” refers to the digital files used to make Nukit Open Air Purifiers)

1. Anyone can copy, modify and distribute this software.
2. You have to include the license and copyright notice with each and every distribution.
3. You can use this software privately.
4. You can use this software for commercial purposes.
5. If you dare build your business solely from this code, you risk open-sourcing the whole code base.
6. If you modify it, you have to indicate changes made to the code.
7. Any modifications of this code base MUST be distributed with the same license, GPLv3.
8. This software is provided without warranty.
9. The software author or license can not be held liable for any damages inflicted by the software.

