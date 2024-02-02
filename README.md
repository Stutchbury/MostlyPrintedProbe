# Mostly Printed Probe
A mostly printed kinetic probe for CNC machines

![MostlyPrintedProbeWiredLED](images/MostlyPrintedProbeWiredLED.png)

After my 21 year old ebay 'bargain' Renishaw gave up the ghost, I needed a probe quickly to continue developing my [CNC Probe Interface](https://github.com/Stutchbury/CNCProbeInterface) but it worked so well, it is now an official side project...

![MostlyPrintedProbeExploded](images/exploded_view.png)

With the exception of the 3mm diameter pins and the stylus, all of this probe is able to be FDM printed - even the spring is made from a length of filament!

There are two different bodies - one is wired only and the second can also accomodate a 3mm LED (single or bocolour). The non-LED version requires no soldering.

This is the first build, it is fairly compact at 38mm diameter x 28mm tall. The 25mm/30° taper allows concentricity to be tuned in on a mandrel.
![first buid](images/first_build.jpeg)

As with all mechanical kinetic probes, this will work best with a [resistive switching interface](https://github.com/Stutchbury/CNCProbeInterface) but will also work fine as a plain old NC (normally closed) switch.


## Materials & Tools Required

A quick list of things you'll need - I will create a proper print/build guide VSN.

- **Pins** - I have used 3mm tungsten carbide rods, but any decently conductive metal would work and is probably a lot easier to cut.
  - 6off 12mm - 12.5mm
  - 3off 11mm-12mm (just use the ones you cut a bit short...)

- **Filament** - I used plain old PLA on a rather old & tired Ender 3.

- **Accurate 3mm drill** or reamer (measure your drills, they vary a lot).

- **M3 tap** - to fit the stylus and optionally the spring tensioner.

- **Thin stranded wire** - as fine as you can. I stripped out a ribbon cable but old USB charging cables are a good source.


All the STLs are available [here](stl/).

