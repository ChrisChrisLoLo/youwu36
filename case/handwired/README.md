# Handwired Case
These are the files you need to make your own handwired youwu36

## Bill of materials
You will need the following materials outside of the printed/machined parts
- 12x M2 nuts (I used nylon ones)
- 6x M2 5mm-6mm M2 screws (I used metal ones)
- Super Glue
- An M2 jewlery screwdriver
  - Note that some screwdrivers might not be long enough to fit in the case. Try to use the screwdrivers with the long black heads.
- Foam Gaskets
  - These should work with KBD D65 gaskets, but what I used was a 1/16 inch thick adhesive neoprene foam sheet since it was what I had
- Rubber Feet
  - Try to get ones that are 1.5mm tall. I found that anything taller makes the case height awkward.
- Hot Glue
  - Used to glue the microcontroller to the case

## How to print via FDM
You will be able to print everything on an Ender 3 or bigger.
I recommend you printing with supports and brims enabled. The supports are needed for the bottom of the case, and the brim generally helps against warping.

I used cubic infill, and I do recommend setting the infill to atleast 50%. Anything lower and I find that you can get some internal "hollowness" noises.

A resolution of 0.16mm worked for me, I wouldn't go thicker than 0.20mm.

I mostly used stock Cura settings aside from this: most tolerances should be built into the model itself.

## Assembly
Once you have all the parts, you will want to do the following:
- Glue the M2 nuts into the top of the case using superglue. Be sure to press the nuts all the way down
- If you have D65 gaskets, place them on the top and bottom of the case and you're done. If you're using a 1/16 inch thick sheet of adhesive foam, cut them out into thin strips, and place them into the top and bottom. There should be 2 layers of adhesive foam stacked on each other to form a gasket approximately 3mm in thickness.
- Pop in switches into the plate, handwire, and place the plate on the bottomm piece. Follow any handwiring guide to grok the circuitry.
- Place the top piece on and screw in.
- Now you're done!

## Features
My favourite part about this case is how soft and quiet the typing feel is. I think the flex of the plate gives for a fun typing experience, and I'd like to think that it emulates some of the more expensive group buy boards for a fraction of the price.

I also like how the BOM should be fairly reasonable for anyone to acquire. No special parts like M2 hot inserts should be required. Hopefully you can get all these parts in a single Amazon run.

## Disclaimer
Because those reading this are potentially spending time and money into making this, I want to be transparent of the flaws of the case. While I do think the case is in good enough shape to release, here are some nitpicks I have that you might want to consider:

- The plate is pretty flexy with PLA. I'm okay with it, but it might be too flexible for your liking, so you may want to thicken the plate. 
- The plate has bigger switch holes than what is layed out in the MX specification. For FDM, I'm very happy with it, since otherwise I need to sand out the plate to get switches to fit in. I don't know if the plate will be too loose for SLA printing though.
- There's a little bit of a gap between the top and the bottom pieces. For me, this is not noticable enough to be too concerned over. If you absolutely want it gone, you may need to tweak the step files a bit to your liking.

## Step file
I have included a step file including all the parts and sub parts of the case. Feel free to modify it to your hearts content if any of the above points won't work for your use case.