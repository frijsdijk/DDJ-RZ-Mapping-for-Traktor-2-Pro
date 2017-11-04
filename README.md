# DDJ-RZ-Mapping-for-Traktor-2-Pro

Starting with Deck A (4 descks supported), top/left: 

DECKS

EFFECTS SECTION

- FX PANEL -> NOT USED
- FX KNOB 1 -> DRY/WET (FX Unit 1)
- FX KNOB 2 -> PARAMETER 1 (FX Unit 1)
- FX KNOB 3 -> PARAMETER 2 (FX Unit 1)
- Release FX Encoder -> PARAMETER 3 (FX Unit 1)

- FX Button 1 -> FX UNIT 1 ON/OFF
- FX Button 2 -> Whatever selected effect provides
- FX Button 3 -> Whatever selected effect provides
- Left Beat -> Whatever selected effect provides
- Right Beat -> NOT USED
* Effects Panel on Deck B/D is FX Unit 2.

- Browse Encoder Knob -> Works as expected (PUSH is unused at the moment)
- Load Button -> Loads track into corresponding deck (and unloads track in preview deck if there is one)
- Back Button -> Loads and starts selected track into preview deck (press again to unload)
(Use the Cross Fader to seek through the preview track) - I have no other use for the X-Fader
* Shift Combo's NOT USED 

- (Shift) Slip Reverse -> NOT USED
- Slip -> Toggle FLUX mode
- Vinyl (shift Slip -> Toggle Vinyl Mode (Native function)

- GRID Adjust -> Grid Adjust/Tap (if auto analyze gets the down beat wrong, you can correct it with this button - tap 4 beats starting with the downbeat as it should be to correct it)
- SLIDE -> NOT USED
* Shift Combo's -> NOT USED

- Deck Buttons -> Works as expected (Native function)
- Jog -> Works as expected. Some latency, and the display doesn't work yet
- Master Tempo -> Key Lock
- Shift Master Temp -> Key Lock (Preserve Pitch)
- Tempo Slider -> Works as expected, but up/down indicators don't work yet

- Sync -> Works as expected
- Shift Sync -> Works as expected
- Quantize -> Toggle Quantize (Global)
- Sequencer -> NOT USED

- Cue/Play -> Works as expected

PERFORMANCE BUTTONS

- Hot Cue Button -> Select Hot Mode
- Shift Hot Cue Button -> Select Beat Jump Mode (Top Row: +4, +8, +16, +32 | Bottom Row: -32, -16, -8, -4)
- Hot Cue Buttons -> Set/Select Hot Cue
- Shift Hot Cue -> Delete Hot Cue
- Pad FX, Slicer, Sampler modes -> NOT USED
- Capture -> NOT USED

Loop Section:
- Auto Beat Loop -> Set/enable Loop
- Shift Auto Beat Loop -> Activate Auto Loop (will latch on to first loop cue point in track)
- 1/2x Button -> Loop/2
- 2x Button -> Loop*2
(shift combo's not yet implemented)
- In/Out Button -> Start/End Loop Points	

- Parameter1 Buttons -> NOT USED

MIXER SECTION

- Mic Section -> Not touched, untested, no idea how this reacts now (might just work because native)
- Sampler Section -> Not touched, untested, no idea how this reacts now (might just work because native)
- Sound Color FX -> Can not use (native function, no MIDI signals)
- Headphone Section -> Works as expected

MIXER CHANNELS

- All functions work as expected, with the exception of the CUE buttons - pressing the CUE button will enable the FILTER knob. Use SHIFT CUE to enable pre-listen on headphone. 
- Cross Fader is only used for seeking in the PREVIEW TRACK (see Browse/Load section)
Note: when starting Traktor, the hardware faders will not force their position in Traktor. Touch them to do that (haven't found a way to force this yet).

Master/Booth Bnobs -> Work as expected (Native Function)
Filter on Main -> Can not be used

OSC Sampler -> Works as expected (Native Function) (no idea yet how we can change the samples as in RB)

---

To IMPORT into Traktor:

Click Settings, Controller Manager, Add, Import TSI, Import Other, browse to file and load it.
It should show as "DDJ-RZ - Generic MIDI", In-Port & Out-port: DDJ-RZ (DDJ-RZ), Device Target: Focus

ONLY tested on Mac. Traktor Version 2.11.1 (28)
