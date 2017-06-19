# Readme and Disclaimer

OEM Key profiles were measured off of a set of Vortex PBT Doubleshot 104-Key caps. 

Cherry Key Profiles were estimated off of Cherry Corp. datasheets. 

Files were made using Solidworks 2017. 

**No Measurement or Dimension is Guaranteed to be Accurate or Suitable.**

Absolutely no guarantee is made that these models will perform as expected. Use at your own risk. Models are licensed under Creative Commons Attribution 4.0. Please redistribute and/or modify at will. Please respect the open source nature of these files, and do not use them for personal profit or commercial use. 

**Modifying Base Dimensions on Wookiee’s Keycaps Files**

# Overview

1. [Base dimensions](#base-dimensions)
2. [Angle of Key Front](#angle-of-key-front)
3. [Angle of Key Rear](#angle-of-key-rear)
4. [Front and Rear Key Height](#front-and-rear-key-height)
5. [Shape of Cylindrical Top, Front Sketch](#shape-of-cylindrical-top-front-sketch)
6. [Shape of Cylindrical Top, Rear Sketch](#shape-of-cylindrical-top-rear-sketch)
7. [Wall Thickness](#wall-thickness)
8. [Upright Edge Fillets](#upright-edge-fillets)
9. [Top Edge Fillet](#top-edge-fillet)
10. [Stem Dimensions](#stem-dimensions)
11. [Final Touches/Stabilizer Stems](#final-touchesstabilizer-stems)


## Base dimensions

![Base Dimension Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model01.png)

Base key dimensions are 18x18. Including these dimensions in configurations and design table allows me to switch between any key width and length.

## Angle of Key Front

![Front Angle Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model02.png)

Front plane angle is set coincident with front edge of base, and at an angle. This angle can be adjusted for all configurations, or you can add it to the design table and set different angles for each configuration.
 
## Angle of Key Rear

![Rear Angle Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model03.png)

The angle of the rear plane is set the same way, but references the rear edge of the base sketch. 

## Front and Rear Key Height

![Key Height Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model04.png)

The front and rear height of the profile are set using a construction sketch on the right plane. These dimensions are constrained to the front and rear angle planes, and set as distances from the base plane. They are included in the design table and set in each configuration.

## Shape of Cylindrical Top, Front Sketch

![Top Front Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model05.png)

The shape of the top of the key is set by an extruded loft between the two angled planes. The front edge is defined on the front angle plane. The width is defined relative to the base, the endpoints are set by the previously sketched profile, and the depth is dimensioned to the midpoint.

## Shape of Cylindrical Top, Rear Sketch

![Top Rear Sketch](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model06.png)

The shape of the top of the key is set by an extruded loft between the two angled planes. The front edge is defined on the front angle plane. The width is defined relative to the base, the endpoints are set by the previously sketched profile, and the depth is dimensioned to the midpoint.

Theoretically, this means you can make the front and rear of the keycap completely different shapes. Just be careful, in the published .sldprt files, changing the shape in one dimension will change it for all dimensions.

## Wall Thickness

![Wall Thickness Shell](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model07.png)

A loft between the base sketch and the lofted top profile gives the key shape. This is then shelled. The wall thickness is defined by the shell.

## Upright Edge Fillets

![Side fillets](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model08.png)

The upright edge fillets are set using a multiple radius fillet. Each edge can be edited individually. 

## Top Edge Fillet

![Top fillets](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model09.png)

The top edge has a tiny fillet put on it. This is for aesthetics and can be suppressed or changed at will.

## Stem Dimensions

![Stem Extrusion](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model10.png)

The stem shape is defined on the bottom plane, and extruded up to surface to the top surface. These dimensions can be easily changed. I used 1.2mm wide x 4 long for the arms of the key cross.  

## Final Touches/Stabilizer Stems

![Stem Chamfer and Stabs Pattern](https://github.com/dankwookiee/Kieeboard/blob/master/modeling%20process/model11.png)

The stem opening is chamfered per the Vortex model these were measured from.

Stems for stabilizers are spaced using linear patterns which are suppressed or activated by configuration. Key widths 2u and up have stabilizer stems, shorter key widths do not.
