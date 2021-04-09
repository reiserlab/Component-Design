---
title: Holder
parent: Tethering

---

# Holder 

[![Open GitHub folder](/assets/img/GitHub-Mark-32px.png) to GitHub project folder](https://github.com/reiserlab/Component-Design/tree/main/Tethering/Tether_holder){:.ifr}
These designs are related to holding a fly in place, for example during an experiment. Here we list ideas to body fixate a fly. Take a look at [Flyplate](/flyplate), if you are looking for head fixation. In addition to the Luer lock holder, we are also using blunt dispensing needles for friction mounting to the [micro manipulator](/micromanipulator).

## Holder cone

During behavioral experiments, the thorax of flies is tethered to a thin thread. The conic holders represent different approaches on how to mount the thin thread to material that is big enough for manual and robotic pickup. In one of the setups, we are using a magnet that has the inverse form of the wider cone, for example as shown in [Holder-cone_pointy](Holder-cone_pointy.stl). For this particular design, we tried to glue the thinner and pointy end to the fly. The design [Holder-cone_pointy_tip-0.07](Holder-cone_pointy_tip-0.07.stl) is intended for a similar use, and in fact the results are show here:

![Fly tethered to a pointy holder](/assets/img/Tethering/Tether_mount/Tether_holder_cone_tip-0.07_form3_03_2019-11_fly.jpg){:.ifr .pop}
Just a quick explanation of the design – which should be similar for many of the other holder designs as well: The wide cone ending in a cylindrical form will be attached to counter piece with the inverse shape. Note that one part from the circumfence is cut of. This keying of the form is used to orient the holder in its pickup form. The gap inside the cylinder can house a [1/16" thick, 1/4" OD magnet](https://www.mcmaster.com/5862k141). Using a static magnet has the advantage that an inverse electro-magnetic field can be used to push the holder away from the pickup. Instead, a metal piece can be used if only static magnetism is needed. The long and thin cylindric share below the large and flat cylinder is required to provide space for the mount. Finally, the conic pointy end on the other side is where the fly is going to be attached. One of the weak spots of this design is that 3D printer use support material inside the magnet gap and through its closed form, it's not all washed out during the cleaning process. This problem is addressed in later designs, such as [Holder-cone_pointy_neck-wedge](Holder-cone_pointy_neck-wedge.stl). Here an additional but smaller opening on the opposite side of where the magnet is slipped in, allows better cleaning.

Talking about the [Holder-cone_pointy_neck-wedge](Holder-cone_pointy_neck-wedge.stl): this is an attempt to see how thin current printers like the [Form 3](../README.md) can currently print. This never really worked, but we keep it to test future printers.

Similarly, a number of designs have a hole instead of the pointy end. These holes come at different diameters to account for different printing materials and leave just enough room, to glue a thinner metal thread into that gap. In addition to the cylindrical holes, the size and quality of which largely depends on the printer, printing material, and some environmental factors, [Holder-cone_flat_helical-cutout](Holder-cone_flat_helical-cutout.stl) uses a different way to form a holder for the tether: Similarly the steps in a spiral staircase, helical cutouts are situated around the center. Their overlap over different of these steps form a space that can be used to glue in the fly tether.

Another approach recently followed is the Luer lock based holder.

## Holder Luer

Based on the observation, that flies seem to behave ok in experiments when tethered to a [34 gauge dispensing needle](https://www.amazon.com/dp/B07KGPDSHX/). The design [Holder-Luer](Holder-Luer.stl) is an adapter between the wide conic magnetic pickup and a luer lock for the dispensing needles.