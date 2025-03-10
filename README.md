# USB Sequential Shifter

**Under active development, might not be complete depending when you read this.**

Converting an off-the-shelf vertical hydraulic handbrake for real race/drift cars, into a USB sequential shifter for racing sims.

## Ingredients

- Vertical hydraulic handbrake (from ebay/amazon/aliexpress/etc, as long as it looks similar to mine)
- 2 x KW11-3Z switches (or similar)
- Arduino Pro Micro
- Micro-USB to Micro-USB extension (optional, makes it tidier)
- 150mm M8 threaded rod
- M8 washers x 4
- M8 bolts x 4
- 2 x springs (check notes below)
- 3D printed parts from this repo

## Instructions

Print the following parts from this repo:
- 1 x "Spring Plate"
- 2 x "Switch Bracket"
- 1 x "Spring Presser"
- 1 x "Spring Sleeve"

Pre-solder some wires onto the switches with enough slack to get to wherever you want the Pro Micro to be mounted, optionall add some JST connectors to make it easier to service.

Assemble the threaded rod with 1 bolt at the end, then a washer, then a spring, then a washer... and then insert the threaded rod into the spring plate as you wont be able to get it through later.

Once it's halfway through the spring plate, on the inside end add another washer, then spring, then bolt.

Leave a bit of space, then add a bolt, the printed "Spring Presser" plate, then another bolt. The threaded rod stack is now complete and you can thread the inside end into the shifter itself.

Put the 2 "Switch Bracket" pieces on top, on either side of the "Spring Presser". Place them roughly, and then adjust the spring bolts and switch brackets while you test the shifter, until you're happy with all the locations.

Use a drill bit or centre punch to mark where the screw holes on the sides of the "Spring Bracket", then remove the brackets and drill 3mm holes through the shifter chassis.

You can now use 3mm bolts to attach the switch brackets to the shifter chassis, and then use a flexible screw-driver to screw the switches into their brackets. It's awkward but doable.

Attach your Pro Micro wherever you want it, using the optional "Pro Micro Mount" print or just with hot glue, and then connect the wires to pins 1 and 2.

## Notes

I recommend printing all 3D printed parts in PETG with at least 4 external perimeters, and 4 top/bottom layers.

For the springs, mine are random bits I cut from a salvaged spring that I cut into pieces ~16mm external, ~13mm internal, and ~35mm long. You can use any springs that fit over the threaded rod and "feel right" to  you.

After assembling the whole stack of parts on the threaded rod, tightening the bolts that hold the springs in place will compress the spring and adjust the "stiffness" of the shifter.
