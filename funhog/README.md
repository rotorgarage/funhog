# Fun Hog Sub-250 Gram Frame Manual

[IN PROGRESS]

The Fun Hog frame is a modular sub-250-gram frame with the broadest range of support.  Being built by pilot engineers, the Fun Hog is the number one choice for unrestricted FPV flight, whether freestyle, race, or casual.

## Field repairable using common parts

The design of the Fun Hog is around existing 250-gram-plus drones. In particular, **M3 hardware** like screws and stand-offs.  

The M2 hardware is common, one size, and limited to the stack (and optional, depending on configuration).

The rest of the build relies on FPV standards: Sticky tape, cable ties, and some e-tape—all common materials.

Our continued commitment to design represents a deep understanding of repairs, upgrades, and maintenance and now simplifies this omnipresent requirement.  Complete everyday tasks quickly field and with minimal tools.  Further modularization of electronics, standardization of builds, and consistency across multiple builds will provide an experience that prioritizes flight and minimizes downtime and waste.

## 2 to 6-inch props

The Fun Hog design is sub-250-gram. Nowhere does that requirement state what prop or motor you should use!

The body (plates and stack) uses a standard hole pattern for all arms.  Control the ratio (length: width) and width to facilitate the best prop and motor combination for your desired flight.

See the favorite builds section below.

## No 3DP Parts!

The Fun Hog frame has **no 3DP dependencies***.  We are confident there are addons for flight and assembly, but we wanted simplicity. Dependencies on 3DP parts represented considerable overhead and risk and were unnecessary.

# Assembly

The assembly instructions are brief. Moderate or better FPV build skills are assumed.

Parts:

* Large cable tie
* Small cable tie
* M2
* M3 stand-off
* M3 hardware
* Sticky tape

### Decide on your stack height. 

The stack height will vary from 20mm to 30mm depending on the configuration chosen.  Typically a 3 PCB stack on M2x6 nylon stand-offs fit comfortably in 30mm.

Knowing the stack height, find some M3 stand-offs and M3 screws.

### Assemble Bottom Up

Using an M2x6 metal screw, push into an M2x6 nylon stand-off four times for the stack.

Drop a PCB onto the four nylon stand-offs, and fasten with more M2x6 nylon stand-offs.  

> Note: Be that the nylon stand-off clears all of the components. Occasionally the washer space on the PCB is small and requires trimming the stand-off for proper fitment.

Repeat as needed.

Complete the assembly with an M2 nylon nut, an M2 stand-off, or an M2 knurled brass nut.  Again, be mindful of where the PCB receives the downward thread movement. Sometimes knurled nuts are required to avoid components on a PCB.

### Add the Arms and Motors

Confirm the stack order with the stack assembled ("dry hump") and leave it unassembled while the arms and motors are mounted.

Both frame (plate) and ar have three holes for mounting.  We have found that only 2 of the three are necessary for a safe flight regardless of the drivetrain.  The holes used are the "outside" holes in the triangle pattern.

[image reference]

The default arm mounting style is to the bottom of the plate.  Many variations exist; start here.  Use M3 metal hardware to hold the arm to the plate (stand-off and screw). Locktite this and all metal-to-metal threaded connections.

Pay attention to the motor mounting to be sure the wires travel well down the arm.

Repeat and mount all four motors on both arms. The arms connect via the M3 hardware described above.

### Finish the stack

Before soldering, trim or handle excess motor wire. Either cut it or loop the wire and fasten it to the arm.  Now use a thin strip of e-tape to secure the motor wire to the arm. Repeat for each motor.

Disassemble and solder all of the necessary connections in the stack. 

> Suggestion: Build with an AIO ESC on the bottom, then flight control, then an optional HD camera (PCB) for a classic 3 PCB stack.

Assemble all components such as data RX, VTX, OSD, camera, and HD, but leave the antennas loose for now.

Smoke test whenever you feel safe.

### Complete the build

There are many directions to take. How to complete the build depends on your skill, parts, and stack choice.  The following approach is a typical finished product like the ones we have flown for years testing.

RX (data): 

* Mount the RX under the top plate or behind the stack. 
* Run the antenna wire up and over the top plate. 
* Use e-tape to keep them in place and protect the wire.  
* RX Antenna:
* Finish the antenna using a large cable tie, heated slightly to bend, forming a classic "antenna" shape.
* Use e-tape to fasten the antenna element to the cable tie.
* Handle excess antenna wire as needed.
* Fasten the cable tie and antenna combination to the top plate's front using double-sticky and small cable ties.

OSD (if used): 

* Secure as needed with double sticky behind the stack, in front of the rear stand-offs.
* Use a small cable tie to fasten. Include the RX if in the area, and loop around the back stand-offs tight enough to hold the position.  Once the top plate is attached, pull tight and trim the cable tie.

### Camera and Top Plate:

1. Using Camera Flap technology, fasten the correct size (stand-off height) flaps to the camera.  The flat (not angeled) side faces forward in the build.
1. Adjust the camera angle, and tighten it as appropriate for the camera and hardware.
1. Cut a piece of double-sticky to place on the feed of the flaps.  Stick it there and set the camera with flaps behind the front stand-offs. 
1. Be sure not to pinch any motor or similar wires.
1. Attach the top plate. The addition of the top plate should hold the flaps and camera in place. If not, double (or greater) the double sticky in use.
1. Account for all wires. Then confirm the camera remains tightly affixed between the plates and positioned correctly.
1. Fasten any loose wires to the top plate using e-tape, leaving room for velcro (if top mounting the battery)

### VTX:

Using Ass Paddle technologies, affix the VTX/Ass Paddle combination to the rear of the drone, behind the back stand-offs.

The recommended approach is to use a quick-release connection (micro JST, for example), minimal double-sticky, and a single cable tie around the VTX conglomerate and the back stand-offs.

### Battery

The Fun Hog allows for top mount or underslung battery style.  

**Top Mount:**

Thread the battery strap.  It is often necessary to use a small cable tie to hold the D-ring to the top plate.  The extra cable tie will eliminate strap slip, which can be problematic when the top PCB is close to or touching the strap area.  Add battery velcro to the top plate strategically and concerning e-tape use to fasten wires.

**Underslung**

Thread the battery strap, similar to the top mount method. Add velcro for the battery.

## Finishing Touches

**Tuning**:  

As a KISS (FETEC) fan, builds run great on default PIDs.  Most modern flight controllers supporting higher KV motors will allow the drone to fly using default settings.  Tune as needed.

**First flights**:  

Go gentle; check the temperature of the motors often.  Watch for any wires or guts spilling out after initial aggressive flights. Treat as needed.

## Long Term

Some Fun Hog builds have flown over 500 flights without any significant repair.  Flight-to-flight maintenance is still required. Here is a good checklist:

* Tighten all stand-off+M3 screw connections. Re-Locktite as needed.
* Check motor screws. Many motors are aluminum bases, and the metal expands. Re-Locktite as needed.
* Confirm no wires are fraying or showing undue signs of wear or friction. Treat as needed.
* Inspect motors. In particular, confirm the rotation is still proper and clean.  
* Review for stress cracks in the carbon fiber.  
* Inspect the stack, and look for broken stand-offs (use nylon stand-offs to break away for safety)

### Favorite builds

* 2" 20xx props with 11xx motors 10,000k+, 2-3s
	*  Buzzy, medium performance, seems to fly under and through anything!
* 3" 30xx props 14xx motors 4000-8000kv, 4s
	* **The sweet spot** providing a 5" experience.
* 4" 40xx props 14xx motors 4000-8000kv, 4s
	* A robust build but very weight conscious, a technical build with extraordinary results.
* 6" 60xx 22xx 3500kv, 3s
	* A slower cruiser that flies like a glider, not a rocket.  Long flights, sometimes exceeding 10 minutes, great for LR, and quiet!

Please refer to the license file included with this repository.
