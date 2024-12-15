# EQHG1
EQHG1 Equatorial mount with harmonic gearing project

This is my record of a DIY equatorial mount for astronomy use. It is a design based on collated ideas from other projects and and it is designed to be built easily using readaily available parts and 3D printed parts. Whilst the goal has not been to make this the cheaapest project, consideration has been made in terms of 'value for money'.

It is set up in a modular fashion that building only one of the two motors, it can be used as a simple sky tracker. Using two will allow it to be used as a GoTo mount with dual axis tracking, etc.. Each module are identical. All 3D printed parts were printed on my Bambu P1S using Bambu Labs PETG-CF. I am sure other printer and filament combinations can be used, but you may need to test fit the parts as required. 

BoM (for 1 motor, you will need 2 for a full GoTo/2 axis tracking mount):
Hardware
1x ZXF14 100:1 Harmonic Gear (https://www.aliexpress.com/item/1005006514715087.html)
1x 50:1 Nema 17 Planetry Gear (https://www.aliexpress.com/item/1005007382016476.html)
1x 6810ZZ Bearing
1x Universal Dovetail plate ('Style Two' https://www.aliexpress.com/item/1005002630127603.html)
1x Yellow grease (but I used red lithium, as that is what I had on hand)
M3
M4
M8

3D Printed Parts (One of each)

<b>Electronic</b>
I have used a Fystec E4 as the OnStepX controller board and found that the settings that works well so far to be (for either motors):
- Steps per degree: 44,444.444
- Microsteps: 16
- Everything as standard as per the OnStepX fresh install

For reference, I tired reducing the microsteps to 8 or lower, to increase slewing speed, but found it to slip and stall. It would appear that a minimum of 16 microsteps works well so far. 


Testing
Having used this with OnStepX controller and AsiAir Lite, I have found that the tracking erros have been in the region of 1.0 RMS typically, reaching as low as 0.6 RMS. 
