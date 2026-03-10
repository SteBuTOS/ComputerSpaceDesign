Credits where credits due: 

This is a fork of pong74ls phenomenal work on the Comper Space circuits.

I intend, to add some very minor additions. Planned add-ons:

Work in progress:
- Cinch Jones Beau to IDC type adapter
- (Experimental) Interposer PCB for Sync-Board to fix the issue with scores beyond "9"
  Extends the scores for Rocket and Saucer to a max of 99 counts with prober 2 digits display.

#Update: the Interposer PCB for two digits scores (0-99) is no longer experimental. After 4 board revisions I have a working prototype. The interposer PCB is compatible with all revision 1 Sync-boards (including the original boards from 1971). There will be some more testing and finetuning necessary before the Gerber files will be published on this GitHub repository. In addition a Youtube video will be prepared with a short demo and some background information. The Interposer PCB will make the connection to the Sync-board via male pin-headers to 8 IC sockets on the Sync-board.

Already added:
- Handheld controller (reduced size, for testing environment; folder Add-ons)
- Back Plane PCB (folder Add-ons)
- Test harness PCB (compatible with back plane PCB only)
- Relay Replacement (based on 2N25 optocoupler, folder Add-ons)
- Started a Wiki for CS (work in progress: https://github.com/SteBuTOS/ComputerSpaceDesign/wiki )

STL-Files for 3D-printing housing are available here:

https://www.printables.com/model/1200359-computer-space-arcade-cabinet

https://www.printables.com/model/1046309-computer-space-arcade-coin-return

https://www.printables.com/model/1520860-computer-space-handheld-controller


pong74ls masters readme starts here:
------------------------------------

NOTE: These are the full design files, gerber outputs and the scans of the stripped down PCBs I used to verify the schematics.

The schematics were made using Proteus Design Suite version 8.1 SP1 [Build 17358]. Hopefully newer versions can be used to view them.

Schematics diagrams, part layout and bill of materials for Nutting Computer Space, single player version.



These files were redrawn from scans of the original schematics.  Errors in the original drawing were corrected based upon examining an original set of game boards from a unit with serial #9392.  Your board layout or part values may differ slightly as there may have been some undocumented changes to the design throughout the production run of this game.



The following general changes were made to the schematics:

1) Used logical/functional symbols for parts instead of straight pin layout.

2) Attempted to obey consistent schematic layout rules: inputs on left, outputs to the right, VCC on top/left and ground connections on the bottom.

3) Added part numbers (some borrowed from original layout) for all components to allow for easier tracing of signals.

Version 1A Update:

-Added Sync/Star Board Model 2 schematic. The parts and connections on this board have not been verified since I do not own a Model 2 board.

-Added the RotateLeftSW and RotateRightSW signal labels to the Memory Board.

-Some minor tweaks to the positions of symbols

You may email me at pong.74ls@gmail.com with any corrections or omissions and I will update the files as necessary.
