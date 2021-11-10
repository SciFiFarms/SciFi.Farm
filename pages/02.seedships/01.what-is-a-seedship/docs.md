---
title: 'What is a Seedship'
taxonomy:
    category:
        - docs
---

## Seedship Definition

At it's core, a Seedship is a controlled growing environment. The micro-controllers (ESP8266 & ESP32s) and their various sensors and switches are programmed using ESPHome, can be controlled in Home Assistant, and have history available via Grafana.

## Current System Pictures

### Seedship V7 (Plastic Totes) [11/2021 - Current]

|This is the current Seedship design. At this point, it's only been running for around a week, but so far, it's been both easier to build and not leaked at all.| Using magnates to mount the power strip and LED driver has worked better than using velcros strips without having to put additional holes in the shoot zone.|Future builds need to either use 1ft LED strips or a tote that is at least 2ft.|
|---|---|
|![V6 turned on](v6-turned-on.png?lightbox)|![V6 shoot zone](v6-shoot-zone.png?lightbox)|![V6 root zone](v6-root-zone.png?lightbox)|![V6 electronics](v6-electronics.png?lightbox)|

### Water Supply V2 (Plastic Tote) [07/2021 - Current]

|The tote for the frame has worked well enough so far. It's a lot more cramped than the wire cart, but that's encouraged me to rethink if all of the bits were necessary (some weren't).| The main change from V1 is that the system is now recirculating rather than drain to waste. The original idea was to still have the water go through the RO process before misting, but that caused other issues. So for now, that component isn't actually being used. | Another area that presented challenges has been priming pumps if they run dry. Turns out the conditions on the output end matter a lot. If there isn't any water on that side, it can prevent the pump from self priming.|
|---|---|
|![Water Supply V2 inside](water-supply-v2-inside.png?lightbox)|![Water Supply V2 outside](water-supply-v2-outside.png?lightbox)|

#### Previous Water Supply (V1, Wire Cart) [07/2019-06/2021]

|This was connected to the house's water line and drainage and made small consistent batches of water when the PSI dropped below 80. It would first run the water through a reverse osmosis system, then would add small amounts of fertilizer, and finally would pump the water to an accumulator/bladder that would store it under pressure until a Seedship misted and used it. |This was inspired by LED Gardner's build. There are two big differences between the builds. The first is that this is drain to waste while LED Gardner's is recirculating. The second is that for the Seedship Water Supply, the logic is handled on the ESPs, while the LED Gardner's build has the logic in Home Assistant.|
|---|---|
|![Water Supply V1 front](water-supply-v1-front.png?lightbox)|![Water Supply V1 electronics](water-supply-v1-electronics.png?lightbox)|![Water Supply V1 back](water-supply-v1-back.png?lightbox)|

### User Interface

There are 2 main services that are used to operate a Seedship.

|Home Assistant is the main one. It has controls for all the switches, as well as to start operations (misting, draining), and the current status of all the sensors and switches.|Grafana is the other main interface. It strength is displaying historical data via graphs and charts. The below picture is the current setup and only has 1 Seedship running.|While this picture is from June when there were 6 Seedships running. You'll notice there was an issue in the morning, and that put the system in emergency mode, so it misted every 30 minutes rather than every 5.|
|---|
|![Home Assistant interface](home-assistant-example.png?lightbox)|![Grafana reporting on single Seedship](grafana-single-seedship.png?lightbox)|![Grafana reporting on multiple Seedships](grafana-multiple-seedships.png?lightbox)|

## Old Seedship and Water Supply Designs

These are listed reverse chronological order. They've all had issues of various degrees, the biggest one across all of these designs has been water leakage.

### Seedship V5 (Styrofoam) [06/2021 - 10/2021]

|Idea was simple enough, just cut up insulation and use some silicone caulk to "glue" the pieces together. Lots of issues though. |The biggest issue was that it took a week to cure. I didn't let it go that long and the root zones ended up leaking because of that. I also found the thickness of the styrofoam made it hard to mount and consistently aim the nozzles.|
|--------|----|
|![V5 in closet](v5-in-closet.png?lightbox&resize=400)| Looking into the way Styrofoam burned made me think that it was a fire risk.|

### Seedship V4 (PVC pipes and pond liner) [07/2019 - 06/2021]

|I used this for nearly 2 years leaks and all and managed to get a couple of strawberry harvests out of the build. See harvests above to check them out. | Working with PVC turned out to be a mess to cut to size and it took a day or two for the glue to set. Also, because I was simply taping the pond liner together, it leaked like crazy, even after using a rubber sealing tape on the bottom.| Originally I had planned to use the PVC of each frame as an accumulator to store a "buffer" of pressure rather than use a single bladder. It turned out that it was hard to glue well enough to support 100 PSI, and that PVC isn't great to pressurize - it can shatter dangerously.|
|--------|----|
|![V4 finished](v4-finished.png?lightbox)|![V4 running](v4-running.png?lightbox)|![V4 in garage](v4-in-garage.png?lightbox)|

### Seedship V3 (Cardboard, Metal Drywall Corner Bead, and Aluminum extrusion - all with pond liner) [2018]

|Notes:|All of these frame materials were rapid failures. The designs weren't waterproof enough for cardboard, the corner bead wasn't strong enough, and the aluminum extrusion was harder to work with than I expected.|
|--------|----|
|![V3 aluminum](v3-aluminum.png?lightbox)|![V3 corner bead](v3-corner-bead.png?lightbox)|![V3 cardboard front](v3-cardboard-front.png?lightbox)|![V3 cardboard rear](v3-cardboard-rear.png?lightbox)|

### Seedship V2 (Wood) [2018]

|Notes:| I never actually used this design. It was clear fairly rapidly that it would be too heavy, WAY too much work to put together, and was too big.|
|--------|----|
|![V2 finished](v2-finished.png?lightbox)|![V2 in progress](v2-in-progress.png?lightbox)|

### Seedship V1 (PFC - MVP) [12/2017]

|Notes:|This was MIT's Personal Food Computer Minimum Viable Product. When I found this, I bought the materials needed within a week. Ultimately, I found the system was WAY basic, not aeroponic, and that programming was actually done in cron scripts. Not ideal, but it grew something!|
|--------|----|
|![V1 closed](2017-pfc-closed.png?lightbox)|![V1 open](2017-pfc-open.png?lightbox)|![V1 growing](2017-pfc-growing.png?lightbox)|
