# DraftONE: Custom Core-XY 3D printer
this is the planning document for my custom 3D printer im making :D
# concepts  
(i.e. what do I want to get from this 3d printer.)

- 1: Print well and fast
- 2: Be Modular
- 3: dual extruder (lowk helps with supports)
- 4: toolchanger multiple filaments
- 5: the gimmick: CNC router
- 6: (More technical but) large buildspace


# How Do I achieve This?
can be split into 4 concepts: 

# The Gantry
    - Linear rails versus round shaft+linear bearing
        - Linear rails: Pros vs Cons
            - Pros:
                - zero backlash
                - lots of mounting points
                - component used on commercial CNC's and 3D printer
                - lots of brands available

            - Cons:
                - ts lowk expensive
                - ordering from secondary vendors means delivery time 
                - more components
                - harder to repair

        - Shaft/Bearing: Pros vs Cons
            - Pros:
                - hella cheap plus mcmaster instant delivery
                - standard smaller components vs rails
            
            - Cons:
                - backlash (wobbly wiggly wobbly wiggly wobbly wiggly huooooo huaoooh huaoooooohhhh swoopidat)
                - very small contact point between linear bearing balls and shafts
                - cannot handle as much laods
                - fewer mounting choices



* FINAL VERDICT: Linear Rails * 

    - Structure: Extrusion frame vs custom enclosure
        - Extrusion Frame:
            - strong base structure
            - low price, can be bought as a bunch of stock shaft (one large length) for cheap then cut down (i gotta find where) or just using standard structure.

        - Custom enclosure/frame:
            - just as strong if not stronger
            - BIG PRICE SKYROCKET
            - OMG THE MANUFACTURING GONNA BE HELL ON TS
            - could also be attached outside of an extrusion frame if we absolutely need an enclosure for printing.


# The movement system
 * Motor Used: Stepper Motors *
    - nema Stepper motors
        - sp many options: we gotta pick one that does the absolute best in terms of speed and torque
            - Nema 17
                - most printers use this
                - commonplace with driveboards and allat
                - not too expensive

            - Nema 23
                - torque beast 
                - would work soooo well if we actually follow through with the CNC idea
                - absolutely massive
                - lowk might be expensive gotta see


    * Verdict: nema 23 if i actually go through with the cnc thing, but yeah should be easy to translate to 17 later on *

# The Extrusion system
* The Idea * 
- Semi-custom extruder assembly:
    - CUSTOM Extruder
    - CUSTOM Cooling
    - COTS Cold End
    - COTS Hot End

- Brands for cold-end and hot-end:
    - Phaetus Rapido 2
        - thru research it seems to be p good, but bro its sooooooo expensive
        - CAN print pps cf (but im never gonna need that)
        - oh shit this is insanely fast gah damn

    - e3D v6
        - yoooo ts nicer
        - DLC coating for cf stringing
        - Revo Hotend Ecosystem - repairable and modular?

    - Bambu Hardened steel
        - as a bambu user, I feel like this might be a good fit
            - uses 0.4 hardened steel ans 0.6 hardened steel alot, works so well and I cant complain
        - hotend ecosystem with 4 nozzles/hotend to choose froom
        - keeping same hotend design means easy to swap around
        - do they work on custom printers? gotta check (apparently they do)



- extruder:
    - two nema 17's on the actual tool head, connected to sockets on the hotend extruders to power each extruder
    - nema17 over nema23 because i dont need torque for that
    - each extruder has its own bowden tube assembly
    - geared, can i use steel gears over 3dp gears? yes i can

- Cooling /heating system:
    - intake/outtake fan for airflow
    - heating element and thermistor integrated into bambu hotend


# The Router (tentative)
- Spindle
    ER11 spindle? i researched its very god
        - so uhh it costs 600 bucks from haas soz
        - please rattmmotor i need this

- Collet
- Endmill
- Cooling
- Vacuum
- Lubrication
        
# The Electronics