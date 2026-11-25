# Changelog

## 1.0.1.1 (25 November 2026)

- **Multiplayer fix:** players who join a game now see the products in the chemical store on the induction hopper screen. Before, the screen tried to read the stored pallets on the player's own computer, where the game keeps only part of their data, and wrote a script error to the log each time it refreshed (`setXMLInt: Argument 2 has wrong type` from `ChaferInduction.lua` `readObjects`). The server now sends the stock to each player. The server and every player need 1.0.1.1.

## 1.0.1.0 (20 November 2026)

- **New shop options:** a Slurry Pipe System coupling, so the sprayer fills through SPS pipes (needs FS25_SlurryPipeSystem), and See & Spray, with cameras along the boom that spot-spray the weeds (needs Precision Farming). Both are off unless you choose them.
- **Washout:** WASHOUT on the induction hopper screen empties the spray tank through a new dump valve under the tank. The engine revs up for the pump; press it twice to start and once to stop. The sprayer can't be switched on while it runs.
- **Boom:** smoother suspension and steadier levelling. The boom no longer wobbles.
- **Tank:** brushed stainless steel, as on the real machine.
- **Paint:** glossier, like the real machine. The yellow is at full gloss under a clear coat, including the cab's yellow trim, and the dark grey and black paint are glossier too.
- **Flickering surfaces fixed:** at the bottom of the steps, on the cab platform, behind both front wheels, and the fill level bar on the RinsePro screen.
- **Steps:** grated treads like the real ones, with a hydraulic actuator at the step hinge.
- **Workstation:** the lid lifts on gas struts, with sound, fixed to brackets on the lid and the body. The clipboard lists your farm's fields and their sizes in clear capitals, on any map; more fields than fit turn over in pages.
- **Exhaust:** the flap on the stack lifts with the engine load.
- **Frame:** front boom rest rebuilt with welded joints; rear mudguard tubes rounded off.
- **Spray shed:** the 'Spraying in progress' A-board on the front apron is gone.

## 1.0.0.0 (17 November 2026)

First release.

- **Chafer Interceptor 2.0:** self-propelled sprayer with a 5,000 l tank, 24, 30 or 36 m G-Series boom, 240 hp Deutz engine, working cab screens, and an induction hopper with its own fill screen and field calculator.
- **Spray Shed with Chemical Store:** room for the sprayer with its boom folded, and a chemical store for 3 pallets.
- **Water Tank 15,000 l with Hose:** refills from the mains; its 15 m hose couples itself and fills at 600 l per minute.
- **Chemical carton pallets:** herbicide and liquid fertiliser.
