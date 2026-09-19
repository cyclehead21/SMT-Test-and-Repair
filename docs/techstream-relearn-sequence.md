[← Chapter index](../README.md)

# Techstream Relearn Sequence

Composed by [cyclehead21@gmail.com](mailto:cyclehead21@gmail.com)

**Caution:** If your car is running properly except for one problem (ie: engine dies when you select reverse gear), then running the relearn sequence will likely disable your car completely. The relearn sequence compares all the sensor and switch readings to a table of parameters. If one component is out of range parameters, it will disable the whole SMT system by killing the gear indication display window and killing the green neutral LED (dark display). You will not be able to restore it back to the “running properly except..” state. Your only option is to correct the faulty sensor or component and perform a full relearn sequence. Apparently the SMT system does not do a full detailed parameter check during normal operation - only during a full relearn. Lesson: If your car is shifting gears, but exhibiting an error - don’t run relearn until you’re fairly certain you have fixed all the damaged parts in the system.

### Video Showing Full-Relearn Steps

[https://youtube.com/shorts/EKFBjRlzSb4](https://youtube.com/shorts/EKFBjRlzSb4)

The select options to the Techstream sequence is “SMT System/Utility/Parts Exchange”. Most people call it the “full relearn” sequence. (This is different from the “self relearn” process that does not require the use of techstream software)

Disconnecting the battery overnight is a good practice before running techstream. Use the time to fully charge the battery, And verify that the SMT reservoir has sufficient fluid in it.

Caution: Never pour any type of oil or transmission fluid or power steering fluid or hydraulic fluid into the reservoir! The system runs on brake fluid. Seriously.

Verify the transmission and cabin shifter are both in neutral.

(If the car rolls freely, then the transmission is in neutral)

(If the cabin shifter is locked, you can free it using the tiny trap door by the shifter. Press a screwdriver into the hole, and it will free the shifter handle, allowing you to put the shifter in neutral)

## Steps

Ignition on, shifter in neutral

Prompt: Reset “Transmission Control ECU”

During this step the gear indication window is likely black

No green neutral light, no orange reverse light

Ignition off

“SMT ECU Learning”

15 second countdown timer

Ignition on

At this point your green neutral light may be on, or off.

If (1. Green light on), then some of the behavior after this is not seen.

If (2. Green light off) then the extra behavior is seen.

Press “Next” and a 60 second countdown timer will start.

If 1. - then the green neutral light will stay illuminated and you won’t see anything other than the countdown time progress.

If 2. - then during the last third of the countdown, the car will shift into each gear sequentially (6),5,4,3,2,1,R,N and stop with the green light illuminated

Note: This is same as the “self relearn” sequence because it will commence stepping through the gears, regardless of whether or not you hit the “next” button that starts the 60 second countdown, or not.

Prompt: “Start the engine and run for 10 seconds”

If 1. - You’ll just see the neutral light stay illuminated, no change.

If 2. - The beeper will beep, and the neutral light will flash. Usually in about 6-8 seconds the neutral light will go solid, and the beeping will stop.

Prompt: Verify steady green neutral light

Prompt: “Drive the car 4-21 mph in first gear” step until the red “gear” warning light illuminates for 1 second.

This step does not require techstream hookup. It will complete regardless.

It’s okay to reverse the car out of a parking spot, then drive forward.

If you have the rear wheels off the ground, it’s okay to perform this step by engaging first gear and letting the rear wheels spin in the air.

After about 10 seconds of driving slowly, the red gear light will illuminate for 2 seconds and extinguish.

This happens very quickly, like about 20 yards of driving. If you have the rear wheels in the air, just engage first gear and run it slowly for a few seconds until the red gear light flashes on and off.

That’s it. If your car successfully completed this “relearn sequence” then it will likely be trouble-free for some significant time. The system acts like a computer controlled system - it’s either all good, or it’s bad.

## Footnote

The ONLY time I’ve had a problem after a successful relearn, was after significant disassembly of the HPU and/or GSA where I introduced a lot of air into the system. ( This happened on two different SMT cars) My car drove fine for 5-10 trips. Then suddenly went stupid. (car wouldn’t shift, red gear light illuminated etc) The fix was to simply let the car sit for 30 minutes or more. Upon restart - everything returned to normal. And the car never displayed any more problems!

---

*Publication status: Initial conversion 0.1. Formatting and cursory editorial check only; detailed technical review is pending.*
