# Watercooling for 3d printer based on Vz235 build and Mellow motor, drivers and extruder aluminium watercooling blocks. Warning page is under construction!

Experiences from building up watercooled 3d printer or how to make rigth choices for your build. Information based on internet "research" and communication with PC watercooling community, Alphacool and EKWB company info lines.

**Long story short** 

- one big loop
- D5/VPP655 (maybe Apex pump as cheaper D5 compatible variant)
- 2.4/4mm tubing (easy routing around printer)(polyurethane (10m) and optional silicone/pvc(2m) softer for printhead)
- 3x12cm aluminium radiator for easy top mounting (price 2eur more than 1x12 rad)
- brass nickel plated fittings (optional stainless steel 304)(idealy aluminium but I was not able to find any in this world) 
- clear coolant premix

##  Reasoning for this advice should be found next if you wanna dig deeper.

1. Mellow items for watercooling our 3D pritner https://github.com/lukascechovic/watercooling/tree/main/mellow_items
2. Fittings https://github.com/lukascechovic/watercooling/tree/main/fittings
3. Tubing https://github.com/lukascechovic/watercooling/tree/main/tubing
4. Loop topology https://github.com/lukascechovic/watercooling/tree/main/loop_topology
5. Macros to solve multiple states controlling same pin (pump and radiator fans) https://github.com/lukascechovic/watercooling/tree/main/macros
6. Stl files of pump, radiator, tubing mounts https://github.com/lukascechovic/watercooling/tree/main/cad_stl_files
7. Official statements from infolines EKWB and Alphacool https://github.com/lukascechovic/watercooling/tree/main/research%20info%20gathered

## Underline

1. **Why choose D5 pump?** It is PC watercooling industry standart. Even EKWB product video comparing D5 to other smaller DCC pump started with joke "just take D5". And yes, taking anything other than D5 is compromise. Pricewise there is nearly no difference as in smaller pump you pay for small form factor. Big one is that D5 is running at 24V so PC comunity cannot use full potential of this pump. But we can! 24V is our standart voltage :-) .

2. **Starting with budget Mellow watercooling kit?** If you dont wanna spend more than 70 euro just take Mellow watercooling kit and you will be happy and somehow youll find the way to ignore pump vibrations. But if we are building printer worth 2000 euros in items, are we wealthy enough to buy cheap things? Mellow water-cooling kit was 70 euro learning experience for me. I wish to be able skip that step.

3. **Price?**
 - 70 euro - Mellow watercooling kit
 - up to 160 euro - profi items ex. Alphacool D5-VPP655 set with reservoir, with 3x12 rad up to 160 euro (you can cut price with choosing Apex variant of the pump)
 

5. **Reservoir** just take any size you like. With bigger one its easier to start loop. Our loop has around 300 ml of fluid with all possible blocks and 3x12 radiator so its no big deal even with smallest reservoir.

6.**Head pressure** This parameter was harder one to evaluate as usually smaller pumps as DCC have bigger head pressure than D5 pumps. Head pressure is how the pump is able to overcome flow restrictions. But its also dependant from flow. If we watch only extremes from pump graphs the small DCC could seems better with higher head pressure than D5, but flow of the D5 is many times bigger than DCC with just small head pressure loss.


## TODO:

*issue : Starting with budget Mellow watercooling kit?*

*issue : Pump*

*issue: Head pressure*

*issue : Price*

*add screws parameters

*Chatgpt please make this text readable


