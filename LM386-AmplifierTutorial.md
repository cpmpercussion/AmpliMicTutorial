# Mini Amp and Contact Microphone Tutorial

In today's tutorial we're going to little amplifiers! Making stuff louder is a fundamental part of electronic music and something that everybody should try.

Plus you get to learn to solder which is useful too!

You'll need:

- Mini amp kit
- 9V battery snap
- 9V battery
- speaker
- some hookup wire
- some shielded audio wire
- a piezo disk
- 4x alligator clip leads


# Building the amplifier circuit.

Soldering is a fairly easy skill but your first try might be a bit challenging. Go slow and check what you're doing before rushing in.

To get the solder to stick to the component leg and the circuit, everything needs to be pretty hot - but if you hold the iron on the board for a long time, it could burn. It's a bit of a balance.

## 1. Check all components are there

![amplifier kit!](0-OpenBag.jpg)

- 2 x 4.7kOhm resistors
- 1 x 10Ohm resistor
- 2 x 0.1uF capacitor (104)
- 10uF capacitor
- 100uF capacitor
- 1000uF capacitor
- LED
- power socket
- 3.5mm stereo jack
- 10kOhm potentiometer
- 8 pin IC socket
- LM386 IC

![Roll Call!](1-RollCall.jpg)

The PCB has labels for

- R1 - 4k7 resistor
- R2 - 4k7 resistor
- C5 - 0.1uF ceramic capacitor
- C6 100uF electrolytic capacitor
- C7 10uF electrolytic capacitor
- C8 - 0.1uF ceramic capacitor
- C9 1000uF electrolytic capacitor
- R10 4R7 resistor (but the kit comes with a 10R resistor...)

## 2. Assemble components from the shortest to tallest

#### 1. solder on the two 4.7k Ohm resistors (R1 and R2)

![First two resistors.](2-First2Resistors-Soldered.jpg)
![Here's how you solder them.](2-First2Resistors.jpg)

#### 2. Solder on the IC socket - make sure the notch is at the correct side as marked on the board!

![Make sure the IC socket goes in the right way - look at the notch.](3-ICSocket.jpg)

#### 3.  solder on the two ceramic capacitors (C5 and C8) - it doesn't matter which way around these two go!

![Put in the flat capacitors.](4-CeramicCaps.jpg)

#### 4. Solder on the LED (D1 LED) - the longer leg goes in the + side marked on the board.

![Next comes the LED and third resistor.](6-LEDand3rdResistor.jpg)

#### 5. Solder on the third resistor - R10 (labelled 4.7ohm - but the kit comes with a 10ohm resistor - go figure.)

#### 6. Cut 3 two-pin headers from the row 

![Use wire cutters to cut up the headers.](5-DividingUpHeaders.jpg)

#### 7. Solder the three headers onto the spaces on the board - "SP", "5-12V", "J5"

#### 8. Solder the smallest electrolytic capacitor on the board - 10uF into C7 (these are the black cylinders). These need to go in the board the correct way. They have the negative lead marked with a big stripe with "-" signs on it and the negative hole on the board is shaded.

![The cylinder capacitors have to go the right way around!](7-HeadersAndC7.jpg)

#### 9. Solder on the audio socket

![The audio socket - maybe don't need to do this one?](8-AudioSocket.jpg)

#### 10. Solder on the power socket

#### 11. Solder on the last two caps - remember to get them the right way around! Minus to the shaded side.

![](9-PowerSocket-Caps.jpg)

#### 12. Pop the IC into it's socket - remember to get the notched side matched up with the notch on the socket.

#### 13. Solder on the potentiometer (volume control).

![](10-Potentiometer.jpg)

#### 14. Done!

![](11-Done.jpg)

## 3. Test out with the clip leads

Clip the speaker outputs to your speaker and the inputs to something that makes sounds!

![](12-TestingAlligatorClips.jpg)

## 4. Make a cool case

I made a case for mine out of tupperware.

![Plastic Power.](13-PlasticPower.jpg)

PS. I only made it so neatly because I'm teaching the course.
PPS. this is the 3rd project that I've put in that container!

# Making a Contact Mic

Contact mics work really nicely with this amp - and they're easy to make.

1. Get about 50cm of shielded audio wire.
2. Strip the shield off a bit and twirl up the shielding strands and the core.
3. Tin the core and shield on both ends
4. Solder the core to the white part of a piezo disc and the shield to the brass.
5. It's really hard to heat the brass up enough to take the solder. do this part first and then try for the shield.

Use the clip leads to connect to the input of your amp and blu-tack the piezo to something noisy!
