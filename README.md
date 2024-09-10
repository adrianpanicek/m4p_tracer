# Hop-up tracer for Maxx M4P - PRO hop up

## Introduction

While I was shopping for Maxx M4P - PRO, official website teased us with possibility of buying tracer upgrade for this hop up. Unfortunately even a few years later, there is no such offer on their official website and tracer units from other models don't seem to fit. So I decided to make my own and open source it.

## Design

This design uses 3 UV LED's (VLMU3100-GS08) made by Vishay, LED driver (AP3019), trimmer for adjusting driving current, switch and a reverse polarity protection MOSFET

It's designed to run on external power with voltage from 3.3V to 16 V

Module should fit on 4 corner holes of the side windows of Maxx M4P - PRO and provide sufficient power to lighten fluorescent tracer BBs

### Design notes

- This design isn't tested for connecting directly to AEG motor as other tracers are
- You can use expander attached to have more power lighting the BBs from both sides, but it's generally not needed, it is attached by removing 0 ohm resistor and soldering the leads on expander board

## Construction

PCB is designed to be manufacturable by JLCPCB but it's generally manufacturable by most providers. Parts are made to be generic and can be ordered from LCSC. Whole design is hand solderable but due to size constraints I used 0603 components which may require some experience. Using reflow soldering is recommended. 

I recommend to use conformal coating to shield parts from the moisture.

## Cost

Rough estimate is around 10 USD + shipping, not accounting for batteries required to run the tracer.

(Prices of components are estimated at the time of writing this readme and might vary by region)

### Cost breakdown

- PCB: 5 USD + shipping
- Components
    - 3x LED (VLMU3100) ~0.60 USD/piece
    - 1x Driver (AP3019) ~0.50 USD/piece
    - 1x MOSFET (SI2312CDS) ~0.30 USD/piece
    - Other components: ~2 USD/piece