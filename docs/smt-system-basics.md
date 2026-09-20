[← Chapter index](../README.md)

# SMT - System Basics

Composed by Cyclehead, July 2021

Feel free to copy and share, just give me a little credit!

I wrote this to minimize repeating background and general tips for newcomers.

It is, by no means, authoritative or complete.

Please please send me corrections, additions and updates!

Cyclehead21@gmail.com

## General Info

### System

**The SMT system was designed by LuK in Leamington UK, and manufactured in Germany (LuK appears to have bought the HPU pump and motor design from Parker Oildyne). It uses an hydraulic pump driven by an electric motor. It shifts gears of a standard 5 speed transmission, upon driver input only (there is no “automatic” mode.)**

**This video appeared on Youtube recently. It is very well written, thorough, and accurate. An easy way to get familiar with the system!**

[**https://youtu.be/g_4Wn17LCP0**](https://youtu.be/g_4Wn17LCP0)

**“Toyota MR2 Spyder SMT Transmission” posted by DuckVision**

### Terminology

#### SMT

“Sequential Manual Transmission” is a misnomer. The car has a standard transmission, and standard clutch. The gears are shifted via an electro-hydraulic system, which also modulates the clutch for you. The only thing “sequential” is how the driver moves the shift lever in the cabin.

#### TCU
Transmission Control Unit. The computer that runs the SMT system.

#### GSA
Gear Shift Actuator. An Electro-hydraulic box containing three hydraulic actuators that physically shift the gears for you.

#### HPU
Hydraulic Pressure Unit. Electric motor drives a small hydraulic pump. Also houses a hydraulic accumulator and plastic reservoir tank.

#### Solenoids

Hydraulic spool valve, controlled by an electromagnet. Pulse Width Modulation (PWM) signals control the valve position. There are four solenoids in the system.

#### Actuators
Hydraulic actuators cycle the clutch fork, and push/rotate the shifter mechanism to change gears for you. There are three actuators in the GSA.

### Toyota Dealers

Avoid Toyota dealers at all costs. They don’t have the expertise or parts to repair the system. Their factory troubleshooting procedures point them to replace the major components. They do not have access to any internal repair parts. Typically they recommend replacing the Transmission Control Computer (TCU) (\$3500 ish). It is never the problem (unless it has been flooded with water). Then they will want to replace the GSA (\$4000 ish), then the HPU (\$4000 ish). If the system still won’t work, they will send you a HUGE bill and push your car outside and call you to pick it up. This has happened many times.

### Repair Options

Fix it yourself - The best option is to repair the system yourself. If you don’t have the skills, tools, or space to work, life will be difficult. Few secondary repair shops can afford the time to troubleshoot and repair the system. Very few shops in the US will claim to have any experience repairing the system. Most shops, and individuals, will recommend gutting the system and installing a standard clutch pedal and cables.

Swap to clutch pedal - This requires installing two shifter cables, clutch hydraulic system, 5 speed ECU, clutch pedal etc. These parts are occasionally available from other spyder owners for about \$1200-\$1500. Monkeywrenchracing sells a collection of kits for \$4500 (?) that contain the necessary parts. Installation requires dropping the gas tank, removing seats and console, cutting a hole in the forward bulkhead etc. - significant disassembly of the car.

Logic and rant - I heard a shop recommend scrapping the SMT system “because it will just break again”. By this logic you should give me your spyder and buy a new car “because it will just break again”! The SMT system is like anything else on a 25 year old sports car - parts wear out and require replacement or repair. New rubber seals are available (from me). Used position sensors are available - though very pricy! (\$300). However, worn out or contaminated position sensors can be infinitely repaired with new flexible PCBs that I sell for \$20.

Link: [https://docs.google.com/document/d/1EqprInUkLTpsLSfBgH3iZ_P0Kp8ObMkIpnQ6WV7pW50/edit?usp=drivesdk](https://docs.google.com/document/d/1EqprInUkLTpsLSfBgH3iZ_P0Kp8ObMkIpnQ6WV7pW50/edit?usp=drivesdk)

New reverse and neutral switches are available from various sources.

Link:

[https://docs.google.com/document/d/141oDsngYmsW6J4AebyGyAsUkGYOWjnagLtWDFc2zz0E/edit?usp=drivesdk](https://docs.google.com/document/d/141oDsngYmsW6J4AebyGyAsUkGYOWjnagLtWDFc2zz0E/edit?usp=drivesdk)

### System Overview by Cap Weir

[https://www.spyderchat.com/posts/658119/](https://www.spyderchat.com/posts/658119/)

### SMT Fluid

Toyota sells “SMT Fluid” for some ridiculous price. It has been tested and confirmed that the fluid is merely brake fluid, with a small amount of non-petroluem lubricant added. Most SMT owners (myself included) are running for over a decade now on cheap DOT3 or DOT4 brake fluid.

Caution: Do NOT use any type of hydraulic oil, nor transmission fluid, nor power steering fluid, nor any kind of petroleum oils in the SMT system. Never! These will cause the EPDM seals to swell up and fail.

### Techstream Software

Generic OBD readers from the auto parts stores cannot interrogate the SMT system. You will need a “J2534 OBD cable” made for techstream - available on Amazon, ebay or Aliexpress for about \$30. You will also need a copy of “Techstream” software. (free, see below)

Toyota’s proprietary software for the SMT system is contained in “Techstream”. Chinese (?) hackers long ago got past the dealer log-in screens and were selling cracked versions of techstream on ebay and alibaba. Currently a helpful programmer on Facebook MR2 Spyder SMT group has written batch files and drivers for us. You can download the latest copy of techstream from a Toyota site. Then use the batch files and drivers to bypass the password screens and run techstream on your laptop PC.

The instructions are here…

[https://www.aselafernando.com/files/Toyota%20GTS%20Installation.pdf](https://www.aselafernando.com/files/Toyota%20GTS%20Installation.pdf)

Also see:

[https://www.aselafernando.com/blog/2020/01/25?fbclid=IwAR1MfTr9mZdp_FaIgGmXsnD-INVyLB1VPLlXBurYNsJBsAN_it1HFzVVY_Q](https://www.aselafernando.com/blog/2020/01/25?fbclid=IwAR1MfTr9mZdp_FaIgGmXsnD-INVyLB1VPLlXBurYNsJBsAN_it1HFzVVY_Q)

## Maintenance

The system does not require any maintenance whatsoever, according to Toyota. They don’t include ANY system maintenance in their maintenance schedules!

Realistically - the SMT system fluid should be changed every 2-3 years. Besides this, the system does not require any regular maintenance.

### Change the SMT Fluid

SMT fluid goes into a plastic reservoir located beneath the air filter box. The system is not completely sealed (there is a vent in the filler cap). The system runs on brake fluid which absorbs moisture - same as your brake system. Suck out the old fluid and replace with fresh DOT3 or DOT4 brake fluid. Open the driver’s door so the pump will run. Repeat about 2 times.

Videos show how to access the reservoir.

[https://youtu.be/a9VVG3jBJ3Y](https://youtu.be/a9VVG3jBJ3Y)

[https://youtu.be/3p774j8xffU](https://youtu.be/3p774j8xffU)

## Problem Indications

### Flashing Green Light

Generally this indicates a mismatch between the gear you requested, and the gear that’s engaged. Usually accompanied by a fast beep warning. The question is - why is the car not engaging the gear you requested?

Hurrying - I see this when I start my car in the morning, and quickly shift to R or 1st gear. The system sees I requested a gear, yet there is insufficient pressure to accomplish the shift. If I put the shifter back into neutral and wait 10 seconds, and try again, it will shift promptly.

Thick fluid - I believe we’ve seen this when the reservoir is full of old gooey brake fluid.

Faulty pressure sensor - It is possible for the system to complain when it thinks the accumulator pressure is too low. There is one pressure sensor on the HPU. If it fails it likely tells the TCU that there isn’t enough pressure. However - if this happened it should tell the HPU to keep pumping past it’s normal limit. The secondary backup is a check ball and spring. If the pump overpressurizes, then the check valve and spring will bypass fluid (internally). If this happens it usually makes a screeching noise.

### Flashing “Red Gear” Symbol

This is the SMT system warning light. Occasionally the gear warning light will flash, yet the car will continue to run and shift properly. I wouldn’t intentionally drive the car with a flashing red gear warning light. You need to determine what’s going on (using techstream software). The best way to interrogate the system is using Techstream software, which is free (stolen). (Or professional automotive scanners like Autel, SnapOp, TopDon, etc).

### Engine Dies

This is a “last resort” when the SMT system detects a fatal problem it will disable the engine. It cuts fuel supply to the engine. I have seen the engine run very poorly, yet I can pump the throttle and keep it going, while the SMT system is flashing the red gear symbol.

### Gear Indication Window Goes Blank

I believe this falls under the “fatal error” category. Typically the green neutral light will also go dark when this happens. It indicates the system has a significant failure.

## Failures

### Position Sensors

There are three position sensors on the GSA. They are essentially variable resistors / potentiometers that report the position of the sensor arm, which reports the position of an actuator (one for each). The contact strip inside will wear over time, or can fail if they are soaked with brake fluid from leaky GSA actuator seals.

### External Hydraulic Leaks

The rubber seals in the HPU and GSA will eventually leak due to wear. The three actuators in the GSA have linear shaft seals, and the HPU has one seal for the rotating electric motor shaft. When these seals leak, they will dribble brake fluid on the bottom of the GSA and HPU respectively.

### Internal Hydraulic Leaks

The actuator pistons can leak internally, however I’m not aware of them causing problems as the system can compensate. However, if solenoid seals leak internally they will cause functional problems, since they disturb the positioning of the actuators.

### Sensors

There are some important sensors screwed into the transmission. There are two neutral position switches (on top), a reverse gear switch (on top), and a speed sensor (on bottom).

### Cabin Shifter

The cabin shifter in the center console is a plastic component containing electrical switches only. Never force the shift lever or you can break plastic parts. If you cannot shift gears using the console shifter, then try the steering wheel switches. If the lever is locked out of neutral (after a failure) you can remove the tiny silver trap door and insert a small screwdriver to release the locking mechanism and allow you to shift the lever into neutral.

Note: The transmission will likely need to be manually shifted into neutral also. That is done with a small screwdriver, inserted into a steel shaft on the transmission.

Video: [https://youtu.be/EIIB7LKWX6I](https://youtu.be/EIIB7LKWX6I)

### TCU

The only way to have trouble with the TCU is via water damage. Otherwise, failure of the TCU is very unlikely. It is mounted beneath the storage tray, behind the driver’s seat. It is mounted on top of the charcoal canister evap system box. It can become submerged in water if your ragtop drains are not working. Inspect the contact pins for corrosion. I like a product called “corrosion block” sold in marine stores (and Amazon). It’s worth hosing down all the pins and the whole connector with this stuff to avoid problems.

## Troubleshooting

### Shift, Select or Clutch Control Codes

By far the most common failure is position switches. They wear out eventually. If the sensors have dead spots, they will confound the computers that need constant feedback to monitor the position of the actuators.

New ones are still available from Toyota and MonkeyWrenchRacing.com. They are expensive - \$250 each?

We’ve had good success with repairing them. Cut the cover plate open, and scribble on the mylar resistance strip using a \#2 pencil. Glue the cover plate back on.

### Flashing Red Gear Light / Dark Display / Engine Died / Check-Engine Light

These are all typical indications of problems. It is impossible to determine what has failed in the SMT system, based on these indications. The only way forward is to interrogate the system using techstream. Malfunction Indication Light (MIL) codes (same as Check Engine codes) are necessary to get a clue to which component has failed. The “Data List” screens in techstream have lots of information about the system status. I am still learning how to correlate indications with specific component problems.

### HPU Doesn’t Run Long Enough

The HPU should run about 20-30 seconds when you open the door in the morning. If it runs much less, that usually indicates a failed accumulator. The accumulator should fill as the pump runs. If it is deflated, the pump will dead head and reach max pressure very quickly.

### HPU Runs Too Long

If the HPU runs much longer than 30 seconds in the morning, it’s usually a sign of a weak pump that can’t build sufficient pressure. Or a giant leak somewhere.

### P01646/P01647

These codes decode as “computer communication” problems. They do not indicate any problems with either the ECU or the TCU. They simply mean the two computers are not getting expected information from each other. After you fix the real problem, these two codes will typically disappear during techstream relearn sequences.

### All Gears Engage Except Reverse

Possibly one of the reverse sensor switches have failed. (There are two). They are screwed into the top of the transmission, buried under a snake pit of wiring harness. They are adjacent to a neutral position switch. A failed neutral switch can also prevent shifting into reverse. I don’t know why.

Alternatively, the copper switch contacts in the console shifter may be crudded up. The console shifter switches are susceptible to damage from spilling a soft drink on top of the shifter.

---

*Publication status: Initial conversion 0.1. Formatting and cursory editorial check only; detailed technical review is pending.*
