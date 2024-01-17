# VORON 1.55 parts

These are the parts designed by Maks Zolin originally intended as the 1.55 version of the Voron CoreXY 3d printer. The only difference from 1.5 as far as I know is that it is using idler pulleys with "built-in" bearings and 3mm axles for the front idlers and the XY joints. These were part of the main Voron repository but were later removed. The 1.5 version uses flanged bearings, and the point of the 1.55 version was to use toothed pulleys which at least in theory should cause less wear on the belt teeth.

I do not know for certain why these were deleted, but some forum posts say it was due to issues with the idler pulleys failing. I have used a Voron 1.55 for years, and have no problem with these. I did not make them, but I want to make sure they are available for anyone needing to print spare parts, as they are otherwise somewhat hard to find.

These files were originally in https://github.com/mzbotreprap/VORON. That repo no longer exists, and the rest of the Voron 1.5 printer is at https://github.com/VoronDesign/Voron-1/tree/Voron1.5. These files can still be [found in the history](https://github.com/VoronDesign/Voron-1/commit/cbf4754e31501974d1229aeb7917f48051d4315f) of that repository.

This repo only includes the 1.55-specific files I had as well as a [mod by Andrew Q](https://github.com/VoronDesign/Voron-1/commit/3bf5ab462a174384c966a1b2b2ca92ff8139bfb0) for a belt clip better matching the diameter of the pulleys.

### BOM
The [BOM section](https://github.com/VoronDesign/Voron-1/commit/b8139637b988362360b5214a0fe8de1c6260d197) listed for this:
| Description  | Qty  |
|--------------|------|
| 16T Toothed Idler  | 6 |
| "16T" (10mm) Smooth Idler  | 2 |
| M3 Hex Socket Screw 30mm  | 6 |

### Assembly

The A/B idlers use two toothed idlers each, with M3 screws through them threading into the lower part of the bracket.

The XY carriages use one smooth and one toothed idler each. The two sides have them in different order, to match the belt path. I have not found the build docs (not sure if they were ever in the git repo), but I used a thin M3 washer between the two pulleys for clearance.