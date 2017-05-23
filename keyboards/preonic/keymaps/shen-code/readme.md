# The `shen-code` layout

This used the Preonic default as a starting point. This is for use in  macOS, with emacs as the main code editor.
 
## Philosophy:
 
Don't get too weird. Don't want to struggle too much to change between this and a normal keyboard. Thus, use QWERTY, and keep as much relative positioning as possible. 
 
## Layout

As much as possible is done with the base layer (and shift) and the `lower` layer without shift. We'd like to potentially get rid off of the `raise` layer. The adjust layer is rarely used, so can probably stay.
 
````
Base

 ,-----------------------------------------------------------------------------------.
 |   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  |  \   |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 | Tab  |   Q  |   W  |   E  |   R  |   T  |   Y  |   U  |   I  |   O  |   P  | Bksp |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 | Esc  |   A  |   S  |   D  |   F  |   G  |   H  |   J  |   K  |   L  |   ;  |  "   |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 | Shift|   Z  |   X  |   C  |   V  |   B  |   N  |   M  |   ,  |   .  |   /  |Shift |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 | Raise| Ctrl | Alt  | Super|Lower |    Space    | Alt  | Ctrl | Down |  Up  |Enter |
 `-----------------------------------------------------------------------------------'

Lower

 ,-----------------------------------------------------------------------------------.
 |      |      |      |      |      |      |      |      |      |      |      | Lock |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |      |      |  Up  |      |      |      |      |      |      |      |      |      |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |      | Left | Down |Right |      |      |      |   _  |   +  |   {  |   }  |      |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |      |      |      |      |      |      |   -  |   =  |   [  |   ]  |      |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      | Mute | Vol- | Vol+ | Play |
 `-----------------------------------------------------------------------------------'
 
````

The layout uses two shift keys for alternate hand use. These are also configured for Space Cadet mode (where pressing them without an additional key gives brackets). The enter key is on the bottom right hand corner, where it's easily palmed.

The `Lower` layer contains the missing symbols for coding, in a similar layout to where they'd normally appear. Since they are already on a layer, no shift is needed (though that still works for the bottom row of symbols).

The volume control and media keys are kind of useful.

Compared to the default layout, there's no DVORAK or COLEMK. I don't have any plans for using those.

Lock is implemented as a macro. `Ctrl-Shift-Power`.

````


Raise

 ,-----------------------------------------------------------------------------------.
 |   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  | Bksp |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |   `  |   1  |   2  |   3  |   4  |   5  |   6  |   7  |   8  |   9  |   0  | Del  |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 | Del  |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |   -  |   =  |   [  |   ]  |  \   |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |  F7  |  F8  |  F9  |  F10 |  F11 |  F12 |ISO # |ISO / |      |      |      |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      | Mute | Vol- | Vol+ | Play |
 `-----------------------------------------------------------------------------------'


Adjust (Lower + Raise)

 ,-----------------------------------------------------------------------------------.
 |  F1  |  F2  |  F3  |  F4  |  F5  |  F6  |  F7  |  F8  |  F9  |  F10 |  F11 |  F12 |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      | Reset|      |      |      |      |      |      |      |      |      |  Del |
 |------+------+------+------+------+-------------+------+------+------+------+------|
 |      |      |      |Aud on|AudOff|AGnorm|AGswap|Qwerty|Colemk|Dvorak|      |      |
 |------+------+------+------+------+------|------+------+------+------+------+------|
 |      |Voice-|Voice+|Mus on|MusOff|MidiOn|MidOff|      |      |      |      |      |
 |------+------+------+------+------+------+------+------+------+------+------+------|
 |      |      |      |      |      |             |      |      |      |      |      |
 `-----------------------------------------------------------------------------------'

````

Other changes so far:

 - Changed the bottom left key to "Eject", so the Control Shift Eject "lock" combo works. Probably not what I want to leave it on
 - Moved the Right arrow to just below the backspace, mainly because that key is underused by default (delete).
 
 Current thinking is to get the NB keys where they need to be, then start moving the less important ones into position.
 
Changes to consider:

 - Have the \ and | on the top layer, but on the top right corner, where the Backspace is. These aren't used insanely much, so having them out of the way but printed is probably not the worst. This key also varies location on common keyboards.
 - Correspondingly, move the Backspace down into where "Right" is.
 - If the lower layer cursor keys work well, then probaby no use wasting space with the cursors on the top layer. Consider having a second control or meta key?
 - Bottom left: good palming key. Can put it to better use?
 - If Raise laywer is not used a lot, then reclaim that good thumb key?
 - Consider moving lower layer symbols up one roll. Easier to reach up than down? Is that true?
 - Line the F keys to the numerics? i.e. start at 1, and have F11 and F12 go to Q and W.
 
Think most of the gains will come from better use of bottom row. But need to code a bit more for that to come through. 
