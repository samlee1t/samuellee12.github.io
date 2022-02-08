---
layout: post
title: Scramjet Inlet Analysis
---

For our Rocket Science (ME-433) course, my classmate and I decided to run simulations on theoretical scramjet inlets that we had computed as classwork. We used a wedge and flat plate in order to create oblique shock reflections that would cancel out when the flow reached the  constant area section. The height of the inlet is 1 m and this is a 2D case.

![Geometry][logo1]

[logo1]: https://imgur.com/jyyF0wj.png "Mach 6 Geometry"

The above image shows the Mach 6 geometry calculated using oblique shock angles with an initial flow condition of Mach 6, 0.2 atm, and 216.65 K. These initial conditions were also used as inlet conditions (pressure far-field) in ANSYS Fluent. A density based solver was used in addition with ideal-gas for density to account for compressible flow. The nozzle was designed with arbitary dimensions

The initial results of the flow at design conditions (Mach 6) are shown below.

![Mach6-1][logo2]

[logo2]: https://i.imgur.com/a6qmt3K.png "Mach 6 Results 1"

![Mach6-2][logo3]

[logo3]: https://i.imgur.com/PL8aZsx.png "Mach 6 Results 2"

We can see that the reflections almost cancel out, but do not quite hit the angle at the end of the wedge, which would have cancelled out the reflection. Instead, the reflections continue down the constant area section into the nozzle, which results in fluction in density, and thus pressure, temperature, and velocity.

Below, the off-design case is shown at Mach 4. We expected to see different flow patterns due to the initial design of the geometry.

![Mach4-1][logo4]

[logo4]: https://i.imgur.com/Jr8YeZK.png "Mach 4 Results 1"

![Mach4-2][logo5]

[logo5]: https://i.imgur.com/LsSA3GF.png "Mach 4 Results 2"

At Mach 4, the geometry results in significantly more reflections in the constant area flow section. The density is higher in general in the constant area section, which would also decrease temperature and increase mass flow rate through the constant area section. 
