# Power Pickup Whisker Probe
Is a very small PCB board using only a couple of components (one LED and one resistor)
It is a simple voltage tester for use on the model railway.
Using the whiskers it can also be used to inject power to a specfic wheel set 
on a loco and thus used to detect loose, dirty, or ill fitting pickup contacts.

## Key Features
<Li>Reliable clear indication of power and polarity
<Li>Inexpensive and easy to build
<Li>DC or DCC operation
<Li>Test track, loco pickups, slow action DC motor switching

## Status of Development 
### Only one Prototype Version so Far

## Known Issues
<Li>None

## Thoughts for Improvement
<Li>Add a footprint for a terminal block

# The Panel Version
The PCB is sized less than 20mmm x 20 mm which means it can easily be panelized
in sets of 25. This makes the panelized PCB fit on a single 100mm x 100mm 
PCB which is the normal 'minimum size' for billing. 
Be Aware as the minimum board order quantity is 5 you would get 125 
Power Pickup Whisker Probe PCB's.

There is a seperate folder containing the Panelized version of the Gerbers.

As the individual PCB is small you could consider adding the 
Power Pickup Whisker Probe PCB to another PCB that you may be
ordering anyway.

# Be Aware
Normally all EDITS should be done to the 'single PCB' and then it be repanelized
To repanelize you start a new Kicad project (one with no contents)
and run a 'plug in' to panelize things. You will specfiy which other 
file has the PCB layout you want to panelize. 
You also set the number of rows (5) and collumns (5)
The only manual step needed is to add several straight edge to edge lines
(on the edge cut layer) to separate the individual test boards.
These will be intepreted as 'Vee-Cut' lines and allows separating the two PCBs easily.
