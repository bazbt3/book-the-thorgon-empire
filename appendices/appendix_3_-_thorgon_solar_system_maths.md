## Appendix 3 - Thorgon solar system maths {#appendix-3-thorgon-solar-system-maths}

Though the book is ostensibly a work of science fiction, perhaps the most science occurs behind chapter &#039;Why&#039;. And here is that science. Sorry it&#039;s not the later bit about fire in space, now that sounded interesting. Ok then, some words.

### Extract from chapter &#039;Why&#039; {#extract-from-chapter-why}

&#039;After consultation Tlur replied, &quot;We don&#039;t know how long it will take to refuel, it&#039;s dependent on what we find when we arrive. Our best guess is 12 hours. However it will take approximately 17 hours to reach and dock with the refuelling station, and from there 22 hours until we establish a stable orbit around Planet 9.&#039;

### Timeline {#timeline}

Here&#039;s a bit of maths to back up my previous educated guesswork. I&#039;d originally envisaged the travel times from the wormhole to the refuelling station and thence to Planet 9 as an analogue of the approximate travel times from Mercury to Jupiter and thence to Saturn. I didn&#039;t want to exceed 10% of the speed of light within the Thorgon solar system so I&#039;m happy with 6%, especially working backwards.

Non-sequitur: This might explain why Thorgon ships are so power-hungry.

1.  **41h from wormhole to refuelling station**: comprising approximately 24h estimated time from exiting the wormhole to the briefing in &#039;Why&#039;, then 17h from the briefing to the refuelling station, with a total acceleration time of 24h. The unstable area around the wormhole itself required careful navigation, hence my total of 41 hours.
2.  (12h to refuel.)
3.  **22h to Planet 9 stable orbit**.

There may be some time dilation effects but the travel time estimates are sufficiently imprecise that I&#039;ve ignored the resulting added time.

### The Maths {#the-maths}

#### Basic constants {#basic-constants}

Speed of light:

c=2.998×10^8 m/s = 299,800,000 m/s

Acceleration of a falling body due to Earth&#039;s gravity. Thorgon Prime&#039;s is sufficiently close to not require a separate calculation:

g=9.81m/s^2 = 9.81 m/s^2

#### From the wormhole to the refuelling station {#from-the-wormhole-to-the-refuelling-station}

Note that whilst Tlur indicated 17 hours until reaching the refuelling station, quite some time had already elapsed after exiting the wormhole. I&#039;ve used Earth-standard seconds here but it&#039;s worth remembering that the Thorgon day averages 3% longer than Earth&#039;s:

wormholetoStation=24 hours in seconds = 86,400 seconds

Next, I&#039;ve assumed a high rate of acceleration, 42x Earth&#039;s, i.e. 42g. Bear in mind that pressure-suit-wearing trained pilots lying nearly prone in atmospheric military flight vehicles can attain 9g vertically, but only for a few seconds. Thorgon and Earth star ships have gravity dampers to protect the ship, systems and fleshy occupants during interplanetary travel:

aStation=42* g = 412.02 meters per second^2

Here I&#039;ve assumed constant acceleration to half-distance and then constant deceleration to the destination:

tStation=wormholetoStation/2 = 43,200 seconds

Peak velocity=acceleration x time elapsed:

vStation=aStation * tStation = 17,799,264 meters per second

Distance covered=2x ((acceleration x time^2)/2): a little overdone here but it&#039;s the distance travelled during acceleration and braking added together.

sStation=2 * ((aStation * tStation^2) / 2) in km = 768,928,204.8 km

The highest velocity&#039;s proportion of the speed of light, in this case almost 6%:

maxcratiostation=vStation/c = 0.05937046

#### From refuelling station to orbit around Planet 9: {#from-refuelling-station-to-orbit-around-planet-9}

Identical method as the formulae above, but assuming a quick injection into a stable orbit:

stationtoplanet9=22 hours in seconds = 79,200 seconds

aplanet9=42 g = 412.02 meters per second^2

tplanet9=stationtoplanet9/2 = 39,600 seconds

vplanet9=aplanet9 * tplanet9 = 16,315,992 meters per second

splanet9=2 * ((aplanet9 * tplanet9^2) / 2) in km = 646,113,283.2 km

maxcratioplanet9=vplanet9/c = 0.05442292