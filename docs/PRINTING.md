
# Printing

This guide is for FDM printing the Mostly Printed Probe. All models are [here](../stl).

## Tolerances

![bearing face](../images/bearing-faces.png)

Most of the models have fairly relaxed tolerances with the accuracy of the probe being defined by the bearing faces shown above in blue - in particular, the 45° faces inside the body and on the bottom of the sleeve.

### Threads

Yes, the threads work just fine in a 3D printed model!

The M3 threads in the lid (for the spring tension) and spider (for the stylus)need to be carefully cut with a tap. A [threading guide](../stl/MostlyPrintedProbe-PartSpiderTappingTool.stl) is provided to help align the tap with the spider.

The main M36 x 0.5mm thread that secures the top to the body and compresses all the bearing faces can provide some challenges. The thread itself has a generaous tolerance built in, but there are many factors to acheiving a good thread but all can be resolved in the slicer.

#### Shrinkage
The first lid & body I printed fitted perfectly (yes, I know, I'm was as surprised as you are) but when I re-printed the body in red, the diameter shrank. The same filament from the same manufacturer but in black, did not.

I suggest printing the body first (or at least the top 10mm) and then printing the top, using scaling if required. The required scale changes are very, very small (less than 0.25%).

#### Sagging
If your filament is too hot, the thread overhangs (they are at 60°) can sag a little, so playing with the temperature can help.

#### Sticktion
Some filaments, especially shiny PLA, have a nasty habit of sticking to each other. Your thread may be perfect but the think just wants to stick. Matt PLA seems to work much better.

#### Cross threading

An M36 x 0.5mm thread is *really* easy to cross thread - especially when the wires are not allowing the spacers to sit flat. Check the thread works wih just the lid and body (I'm sure you would anyway...) but be exceedingly careful as once cross threaded, plastic threads are very difficult to 'get back'. If it doesn't start easily & reliably, then final assembly gets a bit fractious.

## Slicing & Printing

I'm using Cura at 0.2mm layer height. Sometimes the slicer will report errors in the STLs but then automagically repair them and print just fine. I'm working on resolving this but as everything prints OK, it is a little down the priority list.

**A Note on Seams:** Unless you are able to truly hide your Z seam (ie no blobs), I recommend having a single seam that can be filed or scraped flat where required.

Unless otherwise specified, I am using 4 walls and the default infill.

### Sleeve

![print sleeve](../images/print-sleeve.png)


No supports needed.
The pin holes are (in theory) exactly 3mm diameter - they can by adjusted with 'Hole Horizontal Expansion' in Cura but unless they are coming out loose, then leave as is because we'll be reaming or drilling them in the assembly.

The small holes in the underside are to ease the rmoval of the pins, so if you think you might need that, clean them out too.

File the seam away on the lower 45° face.

### Main Body

![print sleeve](../images/print-main-body.png)


No supports needed. There may be a little sagging at the top of the cable/LED holes but these are easily resolve with a 3mm drill.

Ensure in the preview there are no odd concentric gaps in the walls - they should be solid.

Scrape the seam away on the inner 45° face. A sharp flat-bladed screwdriver works well.


### Top

![print sleeve](../images/print-top.png)


An apparently happy part, but despite this, needs support. We are prining in this orientation because the bottom of the thread and the wide upper face need to be parallel. The underside edge at the top of the threads shouldn't actually touch the main body when screwed in.



### Spider

![print sleeve](../images/print-spider.png)


No supports required, print upside down. I printed this solid (ie 10 walls) as the three pins will try to split the layers as you push them in.


### Pins Cover


Supports are required as there is a groove underneath to accomodate dodgy pin wiring - however you can leave this support in place if your wiring and pins sit wholly below the top surface of the sleeve.


### Spacer

![print sleeve](../images/print-spacer.png)


Every project needs a spacer! No supports required but print upside down.

If your top tightens on the body before clamping the sleeve, then scale this part in Z as required.

This part also holds the (optional) LED in place.



### Spring Top

![print sleeve](../images/print-spring-top.png)


No support required but print upside down.

This sits on top (well, screws into) the top of filament-made spring to 'level out' the coils.




### Tools

These are utility prints to assist with the assemply.

#### Spider Pin Guide

![print sleeve](../images/print-spider-pin-guide.png)


No support required, used to ensure the spider's pins are sticking out just the right amount.


#### Spider Threading Guide

![print sleeve](../images/print-spider-threading-guide.png)

No support required. Sits on the spider's pins to provide a guide for the M3 tap.


#### Spring Mandrel

![print sleeve](../images/print-spring-mandrel.png)

No supports required. Used to wrap filament and 'set' using hot/cold water.

If you have any higher temperature filament, this might benefit, but I used PLA.


### Spindle Mandrels


![print sleeve](../images/print-spindle-mandrels.png)


Not strictly part of the Mostly Printed Probe but provided for testing and modelling. Ideally these shoulb be turned oeut of metal as this is the bit that is regularly tightened into the spindle.

The four M3 threads allow you to tune in concentricity of the stylus.
