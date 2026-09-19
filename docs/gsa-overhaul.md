# GSA Overhaul

**Written by Cyclehead**

**Feel free to share, copy, and duplicate**

**Just give me a little credit**

Updated October 2024

Email: cyclehead21@gmail.com

**Scope:** This chapter covers GSA overhaul on a workbench. It assumes the GSA has already been removed from the car and is on the bench for repairs. Removal from and installation into the car are not covered.

## Contents

- [Overview](#1-overview-of-the-gsa)

- [Repair Procedure Summary](#2-repair-procedure-summary)

- [Repair Steps](#3-repair-steps)

- [Disassembly Pictures](#4-disassembly-pictures)

- [Reassembly Pictures](#5-reassembly-pictures)

---

## Caution

Installing new “rubber” seals in the GSA requires careful use of common hand tools. The GSA contains hydraulic actuators that require very smooth surfaces to function. If the work is done carelessly and the soft aluminum sealing surfaces are scratched, you will permanently destroy the entire GSA unit. Here is an example of poor workmanship…and some permanently destroyed (irreplaceable) GSA parts.

![Source example of a scratched GSA bore](../images/gsa-overhaul/01-damaged-gsa-bore.jpg)

## 1. Overview of the GSA

### History

The gear shift actuator (GSA) is one of the two hydraulic components of the Toyota MR2 Spyder SMT system. It was designed by LuK Leamington UK, part of Schaeffler Group, and manufactured in Bad Homburg in Germany. Toyota subcontracted LuK to design and supply the HPU and GSA for the MR2 Spyder. Unfortunately for Spyder owners, Toyota wrote a tight contract with LuK (or vice versa), and neither LuK nor Toyota would sell any component parts for the HPU or GSA - Toyota would only sell complete units. Today spare GSA and HPU units are discontinued so new spare parts are not available. Don’t despair though, many folks are “converting” their Spyders to standard shift, so there is a steady supply of removed units - which can be rebuilt.

Ref GSA P/N 33960-0W011

### Repair Kit

With lots of help from good folks on the Spyderchat Forum, I have rounded up replacement seals from a variety of sources. Some are commercially available o-rings, others are custom made seals. I invested a few months measuring bores, trying different seals and contacting manufacturers to come up with a comprehensive kit of seals.

The primary reason to buy a repair seal kit is to fix leaks. If your SMT system has failed, simply installing new seals will most likely NOT fix the problem. It is best to get the system working properly before tearing the GSA apart to install new seals. An external fluid leak may not immediately stop operation, but low reservoir level or damage to a position sensor can do so. Internal solenoid leakage can also cause shifting or clutch-control problems. Video of GSA leak inspection is here:

[https://youtu.be/miinrmJShLM](https://youtu.be/miinrmJShLM)

Exception: Very seldom, the seals on the fluid control solenoids can leak (internally). You cannot detect this by doing an external inspection. Leaking solenoid seals can cause shifting and clutch control problems.

Kit Contents: My GSA seal kit contains the replacement O-rings and rubber seals used in this overhaul\*. I also include a new push-on retaining ring, a piece of stiff steel wire (tool) to disengage the clutch cable, a dust cover boot for the clutch actuator (old ones are often torn), a small container of silicone assembly lube, and a plastic “fixing tool” you’ll need when you reinstall the GSA onto the transmission. Also included are two steel pins - tools used to unscrew and disassemble the actuator pistons.

Note \*: There is one o-ring inside the hydraulic hose quick connect fitting that cannot be replaced. I don’t include them in the GSA kit. They will never cause trouble unless you pour oil into the GSA. Oil will cause all the rubber parts to swell and rupture. If yours is damaged, the internal o-ring inside the quick connect fitting can be picked out and discarded since its only function is to prevent dribbling while the hoses are disconnected.

Each solenoid also contains one O-ring buried inside that remains in place during this overhaul. This internal O-ring is separate from the four external O-rings replaced on each GSA solenoid.

I’m happy to send repair seal kits anywhere in the world.

### GSA Function

The gear shift actuator (GSA) is an assembly of three actuators and two electric solenoids, all mounted in an aluminum block. The solenoids route hydraulic fluid to the actuators when the Transmission Computer Unit (TCU) instructs. The TCU sends varying current to the solenoids to make the actuators “hover” in the correct position. The TCU monitors the actuator movement by monitoring feedback from three position sensors (one position sensor for each actuator). The GSA comes with three hydraulic hoses: Blue is Clutch pressure, Gold is GSA pressure supply or Master Pressure, and Red is fluid return.

### Failures

The most common failure of the GSA happens when an actuator piston rod seal starts leaking. The fluid dribbles out of the GSA onto one or two of the Position Sensors. (The third sensor is mounted on top, out of harm’s way) The position sensor(s) fail and quit sending accurate feedback info to the TCU, and the SMT system loses its mind. If you replace the seals and fix the leaks, you may also need to replace or repair some bad position sensors before your SMT system will begin working properly again. Here is a procedure to bench test the position sensors using a 5V power source and a voltmeter. [Position Sensor Testing guide](position-sensor-test-and-repair.md)

Note: I’ve had good success repairing position sensors. This involves cutting the sensor lid off, and inspecting the conductive strip inside. Youtube video shows the process here: [https://youtube.com/shorts/fXODdR9hTdQ?feature=share](https://youtube.com/shorts/fXODdR9hTdQ?feature=share)

I have also repaired one sensor with broken conductors on the mylar strip, using “conductive paint”. Testing and Repair instructions for Positions Sensors are [here. (Link)](position-sensor-test-and-repair.md)

### Relearn

After rebuilding your GSA, you must perform a re-learn process. This process is needed for the TCU to learn the new actuator and sensor positions. Very seldom, the self-relearn process will be sufficient. More likely though, you will need to use Techstream software to perform a full “utility/part replacement” relearn.

### Techstream

Techstream can be downloaded for free. However, license for a legal password is pricey. One of the guys on the forum wrote a crack to bypass the password screen. The procedure is defined here:

[techstream-relearn-sequence.md](techstream-relearn-sequence.md)

It works.

## 2. Repair Procedure Summary

A. Remove the three actuator pistons and replace all the rubber seals.

B. Remove the two GSA solenoids and replace the four external O-rings on each solenoid.

C. Reassemble

D. Run the Techstream re-learn process so the TCU can learn where everything is.

### 2.1 Tools needed

Long skinny circlip pliers are needed. Similar to these [LINK](https://www.amazon.com/dp/B00UM7CUO0?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_1)

7” Knipex Parallel Jaw pliers - may be needed for the hoses at the HPU [LINK](https://www.amazon.com/8603-7-Pliers-Wrench-180-35mm-1-3/dp/B00A8SHULG/ref=sr_1_48?crid=1WNTDSW3N3T8Y&dib=eyJ2IjoiMSJ9.3r8crZ_o0rwOex9TMgsiSfGiZWHJlTbrHjf2RCfYh-Iz593QiwE57ZBYqovtFOre2PRyyIfhQVHNI0IeONnxQookmy736Z6-hLcGeclpyMNYyJXJbwcMqpUnVkr25KO1eD3o38Tu1YcZwTo9a1_6NQd9K3W7DjjzFzKvSQodK4stdFe-CuN_jO19iqb9U9sw7JZXQs6rZ94yTz1yYbGqGhSov4bxJaGn3SRavX0YAjbOlZSp4JmIdZ4OYonkQj7I71qRuyVdOGbRlTKZCSQhowkEMpJVhLlPyQOi5zJ31p0.xwOEOAWDUUAVqrJikow39RPdU85yTuUZirY-dOlakro&dib_tag=se&keywords=knipex%2B8%22&qid=1745613297&sprefix=knipex%2B8%2B%2Caps%2C156&sr=8-48&th=1)

Carpenter’s Bar Clamp - to help compress pistons into the bores [LINK](https://www.amazon.com/WORKPRO-Woodworking-Quick-Release-Spreader-Projects/dp/B0875RW1Y6/ref=sr_1_3_sspa?crid=RNYTB4496I3I&dib=eyJ2IjoiMSJ9.8VkkpcPktfQacNuptoQTe1J0j_iiutCvssVLjC9izXZk47U5XInHiWksSXqux52ndSFuQbH3d9quyOmDvm9yOeSF1GeGF_1eX0g14Z5iUNouXFT8mvjBkCIkVH4P7WuMyMH1-pZ4xblNgn-hzssOS_AWLSGMnfoQu9WLJLmulyv91JV9NvtRfc0UlBc09bsBQNXgasNsqFG_nifyFU_qVaCWCz3Hcj42z1oXeu3IXOitvpA3Eg8X0u1_5_aJHclCVgmd7t68cxqO2ohyOHpc94SRWAeJDC72_rzssmRj-Z8.o1wO_jDglYVTIck7fgalUd3iC4tOigH3u3LlwNj9Y6M&dib_tag=se&keywords=bar%2Bclamp&qid=1745613049&sprefix=bar%2Bclamp%2Caps%2C158&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)

Scraps of PVC pipe to make non-scratching tools (see photos)

Various screwdrivers, pliers, and hand tools

## 3. Repair Steps

GSA [video overhaul playlist link](https://youtube.com/playlist?list=PLmyK-d4KYeZ6r3V1l4SKXACsUAAJQbGaX&si=4Qvz7kYog9fL-EDH)

(Not nicely edited, sorry)

### 3.1 Terminology

- Each actuator has a piston, a rod and a cylinder cap. The cylinder cap has a hole in the center for the rod to pass through.

- Each of the three actuators have a piston-seal (like engine rings), a rod-seal mounted on the inner diameter of the cap, and a cylinder cap o-ring that mounts on the outer diameter of the cap.

- Rubber parts in my kits are identified as “Seals” and “O-rings”. Seals have one or two lips to keep fluid from leaking past a shaft. O-rings are simple rings, like a donut.

- Parts are labeled in the pictures below

- Caution. This is important! Hydraulic components don’t tolerate scratches and gouges. Sharp edged scratches in a rod or piston bore will leak and will also damage the new seals. The GSA body is made entirely of aluminum; some attached components contain steel. Exercise care! The pistons and rods are soft aluminum with a “hard anodized” surface coating. The GSA housing is bare aluminum. These parts cannot tolerate damage that will result from careless use of steel tools.

### 3.2 Details

- Fluid leaking out of the GSA usually means fluid is getting past the rod seals. The piston rods slide every time the actuator strokes. The rod slides against a rubber seal, which is inside the cylinder cap.

- The outer diameter of the cylinder cap is sealed by a static o-ring which is not very likely to fail. However, this o-ring is sheared in half when you yank the piston and cylinder cap out of the bore. So it must be replaced. (The bores have a one-way chamfer that prevents damaging the o-ring during installation.) Therefore, you must replace the cylinder cap O-ring every time you remove a piston and cap from its bore. The clutch actuator’s rubber lip piston seal is also damaged during removal and must be replaced. Removing the shift and select pistons from their bores does not damage their Teflon piston seals. **Never remove the Teflon seals from the pistons; they are irreplaceable.**

- Piston seals may wear, but I have a theory that worn piston seals never cause a GSA to quit working. The pump has excess volume capacity, plus there’s an accumulator in the system. I think that a leaking piston ring (piston seal) will continue to function, because the TCU will simply route more fluid to the actuator to make it stay in position. It would require a huge leak to exceed the pump and accumulator’s capacity. For this reason (plus I couldn’t find a supplier) teflon piston rings (seals) ARE NOT INCLUDED the GSA overhaul kit. **<u>DO NOT REMOVE THE TEFLON PISTON RINGS (SEALS) FROM THE TWO SMALL ACTUATORS.</u>**

### 3.3 Disassembly

Removing the GSA actuator pistons can be difficult, since you're shearing the cylinder cap O-ring and, on the clutch actuator, the rubber lip piston seal in the process. The two smaller actuators are easier since you can pry on the linkage parts (nice edges you can grab with a screwdriver). The clutch actuator has a much larger diameter so it can be pretty hard to pull it from the bore.

Remove all three position sensors. It’s okay to mix them up since they’re all identical. Plan to bench test them before reinstalling them.

**Penetrating oil and cleaning:** Penetrating oil may be used during disassembly because almost all the rubber seals will be replaced. Each solenoid contains one internal O-ring that remains in place, so use penetrating oil sparingly on solenoids and **do not submerge or soak a solenoid in penetrating oil**. Clean the entire GSA body and all components, removing all penetrating-oil residue, before reassembly with new seals.

#### 3.3.1 Clutch Actuator

- The clutch actuator is the most difficult actuator to disassemble. It is a ship-in-a-bottle assembly of parts. There is a strong spring that is fighting you all the time. No special tools are needed to overhaul the clutch actuator, just lots of hands and lots of patience.

- Note that the clutch actuator is the only actuator that uses a rubber piston seal. The other two actuators use teflon piston seals.

##### 3.3.1.1 Clutch Piston Removal

[VIDEO](https://www.youtube.com/playlist?list=PLmyK-d4KYeZ7NdRF37CJcLOhTPpvmyYJE) tips

**Remove the retaining circlip before attempting to extract the clutch piston by any method.** The circlip retains the piston regardless of whether you pull it mechanically or use compressed air. The access steps below explain how to move the dust cover, push-on retaining ring, and sensor ring out of the way to reach it. Protect your eyes and place a heavy towel over the piston to absorb its energy and catch it if it releases suddenly.

###### Clutch Piston Removal Steps

- Peel back the rubber dust cover and cut it off for better access (a new one is included in my kit)

- Pry off the "push-on retaining ring", wedge a screwdriver under it and work it off the end of the rod.

- Cut off the old push-on retaining ring and slide the position sensor ring out of the way, to make a little more room for the next step. You can use a rubber band to hold the gold colored position sensor ring,

- Reach in from the end of the bore with snap ring pliers and remove the circlip . Bulky snap ring pliers won’t fit, you’ll need long skinny ones or a small pair like these from Amazon. [LINK ](https://www.amazon.com/dp/B00UM7CUO0?ref_=ppx_hzsearch_conn_dt_b_fed_asin_title_2)

![Thin circlip pliers and bent awl](../images/gsa-overhaul/02-thin-circlip-pliers.jpg)

Alternatively, I’ve had some success using an awl bent to 90 degrees. It can disengage one side of a circlip and allow you to slip a small screwdriver behind the circlip and hold it out. Then work the circlip out of its groove. Another option, grind the tips of a pair of long pliers to make your own thin snap ring pliers.

With the circlip removed, the cylinder cap O-ring still resists withdrawal. <u>Do not pry on the aluminum cap from the side</u>; you will gouge the cylinder surface.

The clutch actuator piston is particularly difficult to remove because the only part you can grab is the pyramid fitting on the clutch cable. Sometimes the pistons come out easily, others are very stubborn. The most reliable idea is to clamp the swaged cable-end of the heavy clutch cable in a vice and yank on the body of the GSA, using its weight like a “slide hammer”. Some guys say a claw hammer and a block of wood to protect the cylinder will work. If those ideas don’t work, you must build a puller tool. I made a horse-shoe shaped tool to slide around the cable and pull on the pyramid fitting. (Picture below) I made it from two pieces of ¼-20 all-thread, and a big steel washer.

Edit: With the circlip removed, I tried a new method — I blew the clutch actuator out of the bore with compressed air. I unscrewed the blue hose and applied 100psi to the Clutch port (located on the GSA body between the two solenoids), and the clutch head flew out with a pop. Protect your eyes! Place a heavy towel over the piston to absorb its energy and catch the assembly when it comes out of the clutch bore.

- After you get the piston and cable assembly into the bench, you need to remove the cable. Use a stiff wire (included with the repair kit) and hammer to tap the "U" clip cable-keeper out of the opposite end of the piston to free the cable. The keeper has a tapered outer circumference, and it is wedged inside the piston (opposite end from the seals), and holds the end of the cable. Thread the stiff wire tool inside the piston rod, following the cable through the piston rod. Tap on the end of the wire with a hammer to dislodge the keeper. Note that you cannot simply rest the end of the piston on a bench, because the tip of the cable must extend below the piston surface to allow the keeper to come free. Rest the edge of the piston on a wooden workbench while you tap on the stiff wire, or even better: drill a 3/4 inch hole in a piece of wood so that the hollow shaft is supported, but the center cable is free to move as you hammer on the keeper “u”clip.

![Wood support with clearance hole for cable-keeper removal](../images/gsa-overhaul/03-cable-keeper-support.jpg)

I have seen some that are VERY tightly wedged in there. If necessary, try cutting the stiff wire shorter, or try a small diameter steel pin to apply more impact to the keeper. Note that if you get too aggressive, it’s possible to twist/rotate the keeper in the hole and wedge it even tighter. Avoid tapping on one side only, instead you must “walk” it out by tapping on alternate sides. I have sprayed penetrating oil on some rusty keepers to help them turn loose. Remove all penetrating-oil residue during cleaning before reassembly.

##### 3.3.1.2 Clutch Piston Re-assembly

[VIDEO](https://www.youtube.com/playlist?list=PLmyK-d4KYeZ7NdRF37CJcLOhTPpvmyYJE) tips

- It is a good idea to trial fit the piston and cap <u>WITHOUT ANY</u> rubber parts installed, just to make sure there aren't any burrs created when you removed the piston.

- File and sand any gouges on the upper end of the piston where the old push-on retaining ring was located. If there are sharp edges there, you could damage the new seal when you push it onto the shaft. (**Do NOT trial fit any rubber parts, because they will be destroyed as you pull the piston back out of the bore. You only get one attempt to assemble!**)

- I have burnished small imperfections on the piston rod surface using 2000 grit sandpaper. The hard anodized coating is quite hard, but not impervious to scratches.

- Carefully clean the internal groove in the GSA bore that receives the circlip . It will likely have shards of old o-ring floating around in there.

- Lube up the seals and bore chamfers with plenty of silicone assembly lube (included in my kits).

- The piston seal is very tight to stretch over the clutch piston, requiring lots of thumb strength to slide into position. Be certain you have the seal facing the correct direction, then start with one side of the seal in the groove. Then stretch the seal over the top of the piston using your thumbs (like installing a bicycle tire).

(Video example: [VIDEO](https://youtube.com/shorts/VWHz7FesJv4?feature=share))

- My kit includes a new push-on retaining ring. Alternatively, you can flatten the old push-on retaining ring fingers to fix the tabs you bent while removing it and re-use the old push-on retaining ring.

- Don't forget anything. Get the sequence of parts stacked up on the cable correctly before you push the piston into the bore. You only get one chance!! Double check the stack up of parts. Make sure the rubber boot is right side up. Make sure the push-on retaining ring is right side up. **<u>Never test-fit by pressing a piston or cap into the bore after you have the seals mounted on the piston!</u>**

- Take a small hammer and tap the end of the clutch cable to seat the “U” shaped cable keeper inside the piston. When fully seated, the end of the cable will be flush with the surface of the piston. (You do NOT want that keeper to fall out after the piston is inserted into the bore!)

The next steps require patience and possibly an extra helper:

- First CHECK CAREFULLY to make sure you have all the parts threaded onto the clutch cable. 1. Pyramid fitting, 2. rubber dust boot, 3. push-on retaining ring, 4. gold position sensor ring, 5. aluminum cap/plug (with new seal inside, and new o-ring on outside), 6. spring, and 7. U shaped cable-keeper (seated firmly).

- DO NOT push the push-on retaining ring onto the rod yet. (You should not push the push-on retaining ring into position while on the bench, or installation into the GSA will be very very difficult due to limited space to work.)

- Lubricate the o-ring and the clutch actuator bore liberally with assembly lube. Press the cap into the bore to start compressing the o-ring. Make a tool from a 2 inch long piece of pvc tubing. Cut a ¼ inch wide slot along the side to clear the clutch cable. Use the pvc tool and a long bar-clamp to squeeze the pvc pipe and press the cap into the bore. Press on the gold colored ring. Be careful not to get the cap twisted sideways.

Photo shows the PVC tool with the slot. And the bar clamp (like this - [LINK](https://www.amazon.com/WORKPRO-Woodworking-Quick-Release-Spreader-Projects/dp/B0875RW1Y6/ref=sr_1_3_sspa?crid=RNYTB4496I3I&dib=eyJ2IjoiMSJ9.8VkkpcPktfQacNuptoQTe1J0j_iiutCvssVLjC9izXZk47U5XInHiWksSXqux52ndSFuQbH3d9quyOmDvm9yOeSF1GeGF_1eX0g14Z5iUNouXFT8mvjBkCIkVH4P7WuMyMH1-pZ4xblNgn-hzssOS_AWLSGMnfoQu9WLJLmulyv91JV9NvtRfc0UlBc09bsBQNXgasNsqFG_nifyFU_qVaCWCz3Hcj42z1oXeu3IXOitvpA3Eg8X0u1_5_aJHclCVgmd7t68cxqO2ohyOHpc94SRWAeJDC72_rzssmRj-Z8.o1wO_jDglYVTIck7fgalUd3iC4tOigH3u3LlwNj9Y6M&dib_tag=se&keywords=bar%2Bclamp&qid=1745613049&sprefix=bar%2Bclamp%2Caps%2C158&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1)) ready to press the cap into the bore.

![Slotted PVC tool and bar clamp for clutch-cap installation](../images/gsa-overhaul/04-slotted-pvc-tool.jpg)

- When the aluminum cap is pushed far enough into the bore, the O-ring temporarily engages the circlip groove and can be expected to hold the cap and piston assembly against spring pressure while you gather the circlip and snap ring pliers. Push the cap farther into the bore to expose the groove, then install the circlip. This O-ring engagement is temporary; the circlip is the final retainer.

- At this point slide the gold colored ring out of the way, to allow access to the circlip.

- Have an assistant standing by. It may take many hands to get everything back together. You must push the aluminum cylinder cap deeper into the bore, to expose the circlip groove. Then install the circlip , while pushing the cap inside the bore, and pushing against the compressed spring. If the spring pressure tries to push the cap back out of the bore, before you can get the circlip installed, it’s easy to hold it depressed in the bore using a small screwdriver (as you install the circlip)

I have used two skinny, long flat-blade screwdrivers to push the cap down. Push directly on the aluminum cap. Don’t scratch the piston rod or bore surface.

**Note: You cannot push on the gold colored position sensor ring to push the cap into the bore when installing the circlip. It will bottom out on the piston shaft before the cap is deep enough into the bore.**

- Reach into the bore with snap ring pliers to get the circlip installed. It is much like doing a root canal inside the GSA bore.

- Caution: I do not recommend pushing the “push-on retaining ring” into position on the workbench before assembly into the GSA housing, because it makes the final circlip installation much more difficult due to severely limited space. It might work if you have a set of snap ring pliers that are exceptionally long and thin.

- After installing the GSA and running the car, you should pull back the clutch actuator dust cover and peek inside the clutch bore to check for leaks.

#### 3.3.2 Shift and Select Actuators

- **<u>DO NOT DAMAGE OR REMOVE THE TEFLON PISTON RINGS (SEALS) FROM THE ACTUATOR PISTONS.</u>**

- The long and short pistons are simple to remove from the GSA. Remove the circlip holding the cylinder cap, then pry the piston out of the bore using a big screwdriver.

Note: The long actuator is partially hidden behind a round aluminum cover plate (like a freeze plug). It’s just a dust cover. Pop it out using a long screwdriver on the inside. Tap the screwdriver and it will pop loose.

- To replace the rod seals (mounted inside the cap), you must unthread the linkage parts from the rods. The rod ends are threaded into the piston rod, and stuck with loctite. There are small tool holes in the end of the piston that are used to hold the piston while you unscrew it. **<u>Do not damage the piston or the teflon rings (seals)</u>**. Little burrs on the flat end of the piston won’t hurt anything, just don’t gouge the seal surface. Clamp the two steel taper pins (provided in my kit) in a bench vice. Leave 1/8 inch of the pins sticking out above the vice to engage the tool holes. Occasionally I am able to unthread some of the rod ends by holding the piston with leather gloves. If needed, apply heat with a propane torch **only to the threaded end**, using only enough heat to soften the Loctite. **Do not heat the entire piston; doing so will damage the Teflon ring.**

- Reinstallation of the two actuator pistons is simple, just press them into the bores. Make sure the o-ring and chamfer are slippery with assembly lube. Watch that the o-rings are not pinched as they guide into the bore. A short piece of PVC pipe works very well as a tool. Use a woodworking “bar clamp” to press against the PVC pipe and squeeze the caps into the bores.

![Bar clamp and PVC tool pressing an actuator cap](../images/gsa-overhaul/05-actuator-cap-bar-clamp.jpg)

- Lubricate the o-ring and the GSA bore liberally with assembly lube. Press the cap into the bore. After the cap is fully inserted fully into the bore, look closely for slivers of sheared o-ring. If you see a large sliver and you’re not happy with the installation, pull the cap back out, throw away the o-ring and try again. (Be sure to remove ALL the sheared pieces of old o-ring.) I include two extra o-rings in the kit for this purpose. I am satisfied when I see a small sliver of sheared o-ring after inserting the cap into the bore.

##### Dome cap installation

Tap the round dome cap back into place over the long actuator bore. If it won’t stay you can try flattening the disc a little to make it larger. If it still won’t stay in place you can just glue it into position using a bead of silicone sealant. It’s only a dust cover.

#### 3.3.3 Solenoids

- There are two solenoids mounted in the GSA housing.

- Each solenoid is held in place by a long threaded retaining pin. Use a bench vice with a 5 inch throat, a large C clamp, or a bar clamp to squeeze the solenoid into its seat, compressing the fat base O-ring and relieving pressure on the pin. **Keep the base O-ring compressed while you unthread and fully remove the retaining pin.** Only after the pin is removed should you release the clamp pressure and pull the solenoid from its bore.

Note: The pins require a T25 torx tip. Use a nice sharp tip, you don’t want them to strip. These pins can be rusted in place. I have had them shear off half of the pin, requiring me to drill out the remainder. If so, use a 11/64 inch drill bit. The pin is made from soft steel. The drill will stop and grab when you hit the stainless steel solenoid body. (Drill depth 1.25 inches)

Caution: I was stupid and clamped the solenoid too hard. This put a bind on the pin causing it to shear during removal! Only tighten your clamp enough to compress the rubber base seal and relieve pressure on the pin. Adjust the clamp pressure as you try to loosen the pin til you find the sweet spot.

- Each GSA solenoid has a total of **four external O-rings**. HPU solenoids have three external O-rings. The fat base O-ring seals the base of the GSA solenoid to the GSA body.

**Kit contents for each GSA solenoid:** One fat base O-ring, one small O-ring for the tip, and two identically sized O-rings for the medium and large positions.

**The photograph below compares the six non-base O-rings for the two GSA solenoids. Hold them between your fingertips to separate the small tip rings from the larger, identically sized rings used in the medium and large positions. The two fat base O-rings are separate and are not shown in this six-ring comparison.**

![Six O-rings held together for size comparison](../images/gsa-overhaul/06-solenoid-o-ring-comparison.jpg)

#### 3.3.4. Installation Caution

The wobbly piece ( actuator shift link) is held to the shift shaft by one very-fine-thread bolt. It MUST be tightened correctly or it will fatigue and break.

<u>Factory spec</u> **<u>torque is 18 ft-lb</u>**! The bolt takes a 12 mm wrench. Do it.

— See Pictures below —

## 4. Disassembly Pictures

**The quick-release connectors are always problematic. If you cannot get the quick connect joint to release, you can simply unscrew the hoses. This “Knipex” tool (**[LINK](https://www.amazon.com/8603-7-Pliers-Wrench-180-35mm-1-3/dp/B00A8SHULG/ref=sr_1_48?crid=1WNTDSW3N3T8Y&dib=eyJ2IjoiMSJ9.3r8crZ_o0rwOex9TMgsiSfGiZWHJlTbrHjf2RCfYh-Iz593QiwE57ZBYqovtFOre2PRyyIfhQVHNI0IeONnxQookmy736Z6-hLcGeclpyMNYyJXJbwcMqpUnVkr25KO1eD3o38Tu1YcZwTo9a1_6NQd9K3W7DjjzFzKvSQodK4stdFe-CuN_jO19iqb9U9sw7JZXQs6rZ94yTz1yYbGqGhSov4bxJaGn3SRavX0YAjbOlZSp4JmIdZ4OYonkQj7I71qRuyVdOGbRlTKZCSQhowkEMpJVhLlPyQOi5zJ31p0.xwOEOAWDUUAVqrJikow39RPdU85yTuUZirY-dOlakro&dib_tag=se&keywords=knipex%2B8%22&qid=1745613297&sprefix=knipex%2B8%2B%2Caps%2C156&sr=8-48&th=1)**) is the absolute best tool to remove the threaded fittings. If you use an open-end wrench it will slip and round-off the soft steel nuts. Clamp the GSA in a bench vice and use all the leverage on the Knipex handles to get a good bite on the nuts. I think Harbor Freight has similar pliers.**

![Pliers wrench on a hydraulic hose fitting](../images/gsa-overhaul/07-hose-fitting-pliers.jpg)

**Removing the clutch cylinder circlip (this picture lies, because the clutch cable isn’t shown). Pliers shown are actually too bulky. I have better success using an awl bent to 90 degrees, and a small screwdriver, or some long thin snap ring pliers.**

![Clutch circlip removal reference photograph; source notes cable omitted](../images/gsa-overhaul/08-clutch-circlip-removal.jpg)

### Removing the Clutch Actuator

**Remove the retaining circlip before using any of the following methods.** Protect your eyes and place a heavy towel over the piston to absorb its energy and catch it if it releases suddenly.

I’ve had best results by clamping the cable end in a bench vice, and yanking hard on the GSA body (like a slide hammer).

Alternatively you can try using compressed air in the clutch port to blow the piston assembly out. Protect your eyes.

<u>If all fails, and as a last resort</u>: then you may need to build an extractor tool like shown below. The tool needs to grab the clutch cable by the pyramid fitting.

![Threaded clutch-extractor components](../images/gsa-overhaul/09-clutch-extractor-parts.jpg)

![Clutch extractor fitted around the cable end](../images/gsa-overhaul/10-clutch-extractor-cable.jpg)

![Clutch extractor assembled over a support sleeve](../images/gsa-overhaul/11-clutch-extractor-assembled.jpg)

### Clutch Actuator Parts

![Labeled clutch-actuator parts and seal orientation](../images/gsa-overhaul/12-clutch-actuator-parts.jpg)

### Clutch Cable Removal

Cut the old dust boot off before you start this step. (My repair kit includes a new dust boot.) Slide the stiff wire tool inside the rod. Tap the cable keeper out of the opposite end. It is a tapered, horseshoe-shaped plug. Use the stiff wire to hammer the plug loose. Be careful to “walk” the plug out evenly. It can get wedged if you only hit one side. If the wire provided in my kit is not stiff enough, then try a thin steel punch.

![Wire tool used for clutch-cable keeper removal](../images/gsa-overhaul/13-cable-keeper-wire-tool.jpg)

![Annotated path of wire tool beside clutch cable](../images/gsa-overhaul/14-wire-tool-path.jpg)

![Annotated cable-keeper removal tool at piston end](../images/gsa-overhaul/15-keeper-removal-tool.jpg)

![Cable keeper and cable end exposed](../images/gsa-overhaul/16-cable-keeper-detail.jpg)

Clean out all this crusty crud hidden under the old seals and o-rings. It creates a leak path. (I believe this is what results from never changing the Toyota brand SMT fluid for 20 years. )

![Deposits beneath an old seal](../images/gsa-overhaul/17-deposits-under-seal.jpg)

![Deposits on the cylinder cap](../images/gsa-overhaul/18-cylinder-cap-deposits.jpg)

### Actuator Pistons

Short piston (“Select Actuator”) on the left, Long piston (“Shift” Actuator) on the right

End fittings must be unthreaded to access the rod seal. Clamp two small drill bits or “taper pins” into a bench vice to hold the piston while you unscrew. If necessary, apply heat with a propane torch only to the threaded end and only enough to soften the Loctite. Do not heat the entire piston; doing so will damage the Teflon ring. 3mm drill bits are perfect. 7/64 dia is okay.

My picture below is wrong - **<u>DO NOT REMOVE the teflon piston rings!</u>**

![Shift and select actuator pistons; source warns not to remove Teflon rings](../images/gsa-overhaul/19-shift-select-pistons.jpg)

To hold the pistons as you unthread the end fittings, clamp two steel pins in a vice. These steel “Taper Pins” fit perfectly into the holes. (Thanks Triz for the idea!) These pins are included in my GSA seal repair kit.

![Source product screenshot of taper pins](../images/gsa-overhaul/20-taper-pin-product-screenshot.png)



![Piston held by two pins in a bench vise](../images/gsa-overhaul/21-piston-holding-pins.jpg)

If necessary, heat only the threaded end of the rod, opposite the Teflon ring, and only enough to soften the Loctite. Do not heat the entire piston; doing so will damage the Teflon ring. It may help to smack the end with a small hammer to help break the Loctite loose.

![Shift and select rods, caps, seals, and end fittings](../images/gsa-overhaul/22-shift-select-components.jpg)

O-ring gets sheared off when you pull the piston out of the bore. Be sure to find all the chunks of rubber and remove them. Note: There is a chamfer that prevents damage to the o-ring when inserting the piston into the bore with a new o-ring.

![Sheared cylinder-cap O-ring after removal](../images/gsa-overhaul/23-sheared-cap-o-ring.jpg)

There will be slivers of old o-ring floating around after removing the pistons. Be sure to remove them all.

![Old O-ring fragments remaining near bore groove](../images/gsa-overhaul/24-o-ring-fragments-in-bore.jpg)

## 5. Reassembly Pictures

The short actuator bore has a nasty detail. Part of the circumference is missing a chamfer to guide the o-ring. Check to make sure the o-ring doesn’t get pinched on the sharp edge.

![Short-actuator bore and incomplete lead-in chamfer](../images/gsa-overhaul/25-short-actuator-chamfer.jpg)

The end of the clutch actuator will have gouges from removing the old push-on retaining ring. File and sand it smooth, so you don’t damage your new rod seal as it slides over this area. Don’t go crazy removing material though, the new push-on retaining ring must grab the piston in this area.

![Clutch-rod end with marks from old push-on retaining ring](../images/gsa-overhaul/26-clutch-rod-push-nut-marks.jpg)

Caution: This picture is for reference only! If you completely assemble the piston assembly on the bench as shown below, it will be VERY DIFFICULT to get the circlip installed. **This method is NOT recommended!** Better practice is to install the push-on retaining ring AFTER the piston is installed in the GSA bore, and the circlip is in place. Note: This picture is missing the rubber boot and the push-on retaining ring! Get the stack-up correct before you push it into the bore. You only get one chance!

Note the orientation of the large piston seal. Don’t get it backwards.

![Clutch assembly reference photograph; source notes omitted parts](../images/gsa-overhaul/27-clutch-assembly-reference.jpg)

Use a rubber band to keep the boot, push-on retaining ring, and sensor ring out of your way when you install the circlip .

![Rubber band holding clutch boot, push-on retaining ring, and sensor ring clear](../images/gsa-overhaul/28-rubber-band-holding-parts.jpg)

Note which way the push-on retaining ring goes. The fingers “slide” onto the rod, then bite the rod to keep from coming back off. Press on both sides at the same time to press it onto the rod.

![Push-on retaining ring orientation on clutch rod](../images/gsa-overhaul/29-push-nut-orientation.png)

### Pictures for general information

![Annotated actuator rod seal and cap O-ring](../images/gsa-overhaul/30-rod-seal-cap-o-ring.jpg)

![Annotated clutch actuator bore](../images/gsa-overhaul/31-clutch-actuator-bore.jpg)

Left - Short “Select” Actuator piston

Center - Long “Shift” Actuator piston

Right - Clutch Actuator Piston

![Annotated select, shift, and clutch actuator pistons](../images/gsa-overhaul/32-three-actuator-pistons.jpg)

![Source reference photograph labeled pressure-sensor O-ring](../images/gsa-overhaul/33-pressure-sensor-o-ring.jpg)

![Annotated solenoid-retention pin](../images/gsa-overhaul/34-solenoid-pin-reference.jpg)

![Source image warning that Teflon piston ring is not included in seal kit](../images/gsa-overhaul/35-teflon-ring-not-in-kit.jpg)

### Solenoid Retention Pin

![Solenoid-retention pin beside housing](../images/gsa-overhaul/36-solenoid-retention-pin.png)

### Solenoid positions

The solenoids will fit into either bore, but only one is correct. Check to make sure the wires go to the connector as shown. (For reference: Shift solenoid is shown on the left adjacent to the hoses, and “Select” solenoid is shown on the right adjacent to the clutch actuator.)

![Source reference photograph of solenoid positions and connector](../images/gsa-overhaul/37-solenoid-positions.jpg)
