[← Chapter index](../README.md)

# SMT - Bleed-Down Tests

## Pressure Bleed-Down Test

Spyderchat “state of the units” thread (health) proposed a test that monitored pump run time, and rest time.

[https://www.spyderchat.com/posts/1685537/](https://www.spyderchat.com/posts/1685537/)

This test monitors how long it takes to pressurize the system up to “turn off” pressure. Then monitors how fast the pressure bleeds down until the “turn on” pressure is reached.

**Run time: ROUGHLY 7-9 SECONDS**

Run time should be determined mainly by electric motor speed/torque and accumulator back pressure (or lack of). And of course, accuracy of the HPU pressure sensor.

**Bleed down: REST TIME ROUGHLY 1:40 to 2:40**

Bleed-down time should be determined by: the capacity of the accumulator, leakage past the HPU check valve, leakage past the clutch and master solenoids. And again, accuracy of the HPU pressure sensor.

When performing this test with the engine off (ignition on), the clutch and master solenoids are closed - so the run-time/rest-time test simply monitors bleed down time of a small portion of the hydraulic system (pump, accumulator, and internal HPU passages up to the solenoids.) The hoses and all of the GSA are excluded. The clutch and master solenoids would trap pressure inside the HPU.

However with the engine idling, I believe the clutch solenoid is held open and the clutch actuator is fully pressurized (clutch disengaged).

## Solenoid leakage

I suspect that static pressure is retained by the metal spool inside the solenoid, and the solenoid o-rings only see pressure when the solenoid is sending pressure to an actuator. If that is correct, then the bleed-down test won’t help detecting leaky solenoid o-rings.

## Optional tests

It might be interesting to monitor bleed-down with the master solenoid held open. That would send pressure to the shift and select actuators and include those two solenoids in the test (plus one of the hoses).

The most extensive static test of the system could be accomplished by holding the master solenoid open, and the shift and select solenoids open. That would test leakage past all three solenoid o-rings, and include leakage past the teflon piston rings on the shift and select actuators. Or better yet, hold BOTH master and clutch solenoids open!

I have speculated that leakage past an actuator piston seal (the teflon seals) is not critical, since a leaky actuator would simply be sent more volume by the solenoid, until it moves as commanded. The only limiting factor would be the capacity of the system (pump plus accumulator volume). I suppose an excessively leaky piston could gobble up too much system volume and delay clutch or shift cycles that were requested in rapid succession.

## With all solenoids closed

- Run time is about 7-8 seconds
- Rest time is about 2 minutes

**Note:** These absolute voltages below may not be accurate. I think my voltmeter reads low. But the variation should be helpful.

### Using my digital test box

- Max pressure is barely 2.7V
- Bleed time to 2.4V is 2 minutes
- Bleed time to 2.0V is 5 1/2 minutes
- Bleed time to 1.5V is 15 1/2 minutes
- Bleed time with Master Solenoid held open - down to 2.5V is 30 seconds
- Bleed time with Clutch Solenoid held open - down to 2.4V is 30 seconds
- (Note that 2.7V drops to 2.5V immediately upon hitting the clutch solenoid

## Results on my spyders

### Engine Off

- Rest 2:45 min/sec
- Run 7.9 sec
- Rest 2:42 min/sec
- Run 8.7 sec

### Engine On

- Run 7.6 sec
- Rest 1:48 min/sec
- Run 7 sec
- Rest 2 min
- Run 7.4 sec

### Engine off

- Rest 1:22 min/sec
- Run 8.2 sec
- Rest 1:47 min/sec
- Run 8.2 sec
- Rest 1:44 min/sec
- Run 9.1 sec
- Rest 1:41 min/sec
- Run 8.5 sec

---
