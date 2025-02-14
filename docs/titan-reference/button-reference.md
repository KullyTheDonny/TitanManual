---
id: button-reference
title: Button reference
sidebar_label: Button reference
---

This section lists all the physical buttons and tells you what they do. The **links** take you to the section of the manual where the function is explained in more detail. Some consoles may not have all these buttons.

``<n>`` means to type in a numeric value on the keypad.

\<View\> \<Colour\> indicates to press a sequence of buttons.

\<Avo\> + \<Clear\> with a plus symbol means to hold down the first button while pressing the second button.

{Select} means to press a playback select button.

---

 ## \<@\> 
 (by numeric keypad) Allows numeric entry of attribute values on selected fixtures. Can also be used with \<Fixture\> or \<Group\> buttons to change selection state. For the \<@\> buttons next to the wheels see [Wheel @](#wheel-).

 Examples: \
 \<Fixture\> 1 \<And\> 5 \<And\> 7 \<@\> 75 \<Enter\> (Set fixtures 1,5,7 to 75%) \
 \<Group\> 5 \<@\> \<@\> (Set all fixtures in group 5 to full)

  Buttons | Action
 --------|--------
 \<@\> ``<n>`` \<Enter\> | Set intensity of currently selected fixtures to ``<n>`` in the programmer. (``<n>`` normally 0-99, optionally can be single digit 0-9, see [Formatting](../system-settings/user-settings.md#formatting))
 \<@\> \<@\> | Set intensity of currently selected fixtures to full in the programmer.

 --- 
## \<@A\> \<@B\> \<@C\>
For the \<@\> buttons next to the wheels see [Wheel @](#wheel-).

 --- 
## \<Align\> 
 (D9 only) Allows copying of attributes between fixtures. On consoles other than D9 this function is accessed using \<ML Menu\>. See [Align Fixtures](../controlling-fixtures/changing-fixture-attributes.md/#align-fixtures).

 --- 
## \<All\> 
 Used to start and end pattern selection (such as odd/even) within a range of selected fixtures. See [Selecting fixtures using a pattern](../controlling-fixtures.md/#selecting-fixtures-using-a-pattern). (On D9 labelled \<Pattern/All\>)

 --- 
## \<And\> 
 Used when selecting multiple items using the numeric keypad, can be combined with \<Through\> and \<Not\>. See [Selecting fixtures and dimmers by number](../controlling-fixtures.md/#selecting-fixtures-and-dimmers-by-number-channel). Some consoles do not have this button, an \[And\] softkey is also provided.

 Example:  \<Fixture\> 1 \<And\> 5 \<And\> 7

 Also when entering time or timecode values the \<And\> and \<Through\> buttons move the cursor between hours/minutes/seconds/frames.

 --- 
## \<Assign\> 
 (D9 and ST only) Allows you to reassign attributes controlled by the trackball and (on D9 only) intensity wheel. See [Trackball](../controlling-fixtures/changing-fixture-attributes.md#trackball-diamond-9-and-sapphire-touch-only).

 --- 
## \<Avo\> 
 Acts as a "Shift" button when held down, giving access to different functions. Or a quick press shows a softkey menu with other functions.

  Buttons | Action
 --------|--------
 \<Avo\> + \<All\> | Set zero intensity into programmer for unselected fixtures (same as \<Rem Dim\>), see [Turn off unselected fixtures](../controlling-fixtures.md#turn-off-unselected-fixtures-remainder-dim). Also used when setting Attribute Times to deselect all fixtures, see [Attribute Fade Times](../cue-lists/cue-list-timing.md#individual-attribute-fade-times).
 \<Avo\> + \<Back\> | Undo, see [Undo/Redo](../titan-basics/other-parts-of-the-touch-screen.md/#undoredo).
 \<Avo\> + \<Close\> | Close all workspace windows, see [Workspace windows](../titan-basics/workspace-windows.md#changing-window-size-and-appearance).
 \<Avo\> + \<Copy\> | Same as pressing \<Move\> (for consoles which don't have a Move button, but works on all consoles)
 \<Avo\> + \<Disk\> | Enter System menu to set up the console, see [System Menu](../system-settings/the-system-menu.md).
 \<Avo\> + \<Exit\> | Exit menu structure back to the top level.
 \<Avo\> + \<Fix +\> | Jump the pattern forward (or back with \<Fix -\>) in pattern select mode.
 \<Avo\> + \<Flash On\> | Flash out (turn off) selected fixtures while held.
 \<Avo\> + \<Group\> {Select} | Record group to handle, see [Record a group](../controlling-fixtures/fixture-groups.md#record-a-group).
 \<Avo\> + \<Highlight\> | Record the highlight state, see [Highlight](../controlling-fixtures.md/#highlighting-the-selected-fixture-with-prevnext)
 \<Avo\> + \<Macro\> {Select} | Record macro to handle, see [Key Macro buttons](../titan-basics/front-panel-buttons.md/#key-macro-buttons).
 \<Avo\> + \<Min/Max\> | Select a different workspace window to be the active window, see [Workspace windows](../titan-basics/workspace-windows.
 \<Avo\> + \<Open/View\> {Workspace button} | Record workspace layout, see [Saving workspace layouts](../titan-basics/workspace-windows.md#saving-workspace-layouts).
 \<Avo\> + \<Release\> | Release all playbacks by priority (same as double press \<Release\>). See [Release](../cues/cue-playback.md#release).
 \<Avo\> + \<Shape\> | 
 \<Avo\> + \<Size/Position\> | Move the active workspace window to the next screen, see [Workspace windows](../titan-basics/workspace-windows.md#changing-window-size-and-appearance).
 \<Avo\> + \<Time\> | Preview Attribute fade time, see [Attribute Times](../controlling-fixtures/changing-fixture-attributes.md#setting-fixtureattribute-times).
 \<Avo\> + \<Undo\> or \<Avo\> + \<@\> | Redo, see [Undo/Redo](../titan-basics/other-parts-of-the-touch-screen.md/#undoredo).
 \<Avo\> + \[Blind\] | Toggle Blind mode, same as pressing \<Blind\>.
 \<Avo\> + \[Edit current key profile\] | Reallocate the function of the Select and Flash buttons, see [Key Profiles](../system-settings/key-profiles.md).
 \<Avo\> + \[Lock\] | Temporarily lock console controls, see [Locking the console](../titan-basics/front-panel-buttons.md#locking-the-console).
 \<Avo\> + \[User Settings\] | Enter the User Settings menu, see [User Settings](../system-settings/user-settings.md).
 \<Avo\> + {Scene Master} | Enter or exit preset mode when Scene Master assigned to Macro/Executor button or touch button, see [Scene Master](../running-the-show/playback-controls.md#scene-master).
 \<Avo\> + {Master} | Releases the master to its default state (no effect on output), see [Releasing a Master](../cues/cue-playback.md#releasing-a-master).
 \<Avo\> + {Playback} | Kill playback, see [Release](../cues/cue-playback.md#release).
 \<Avo\> + Turn wheel | Wheel Turbo mode, 1 revolution goes through entire attribute range
 \<Avo\> + 2/4/6/8 | Cursor up, left, right, down


 --- 
## \<Back\> 
Backspace key for numeric entry or command line inputs.

 --- 
## \<Beam\> 
 Selects the Beam attribute group so the wheels will control Zoom, focus etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels). 

 --- 
## \<Blind\> 
 Switches the console into Blind mode which allows you to make programming changes using the visualiser (or in your head) while not affecting the stage output. See [Blind mode](../running-the-show/playback-controls.md#blind-mode).

 --- 
## \<Block\> 
 (D9 only) Not used yet.

 --- 
## \<Chan Grid\> 
 (Arena only) Opens the Channel Grid workspace window. See [The Channel Grid Window](../controlling-fixtures/viewing-and-editing-fixture-values.md/#the-channel-grid-window).

 --- 
## \<Clear\> 
 Clears the contents of the programmer and deselects fixtures. See [Clearing the fixture selection and the programmer](../controlling-fixtures.md#clearing-the-fixture-selection-and-the-programmer).

 Buttons | Action
 --------|--------
 \<Clear\> | Single press clears the programmer and deselects fixtures. (Optional 2-press sequence, see [Clear Action Precedence](../system-settings/user-settings.md#clear)) 
 ``<n>`` \<Clear\> | Clears the programmer with a fade out time of ``<n>``
\<Clear\> + \<All\> | Deselect all fixtures but keep changes in programmer
\<Clear\> + \[Set Mask\] | Clears only the attribute groups specified in the mask
\<Clear\> + \[Clear Selected Fixtures\] | Only clears the programmer for fixtures which are currently selected
\<Clear\> + \[Individual Attributes\] | Clear individual attributes from programmer (use softkeys to select)
\<Clear\> + \[Clear All Programmers\] | Clears programmers from other users and from the Titan Remote
\<Clear\> + \[Clear Options\] | Show user settings for Clear, see [User settings - Clear](../system-settings/user-settings.md/#clear)

 --- 
## \<Close\> 
 Close the currently active workspace window.

 Example: (Tap window to make it active) \<Close\>

 --- 
## \<Colour\> 
 Selects the Colour attribute group so the wheels will control colour, RGB, CMY etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Commit\> 
 (D9 only) Commits the Scene Master change, as if you'd pushed the master to the end of its travel. See [Scene Master](../running-the-show/playback-controls.md/#scene-master).

 --- 
## \<Connect\> 
(Labelled Connect/Cue on some consoles) Connects the sequence controls (Go button etc) to a playback. Also used to select cues when recording or playing cue lists.

See [Connecting a Chase for control](../chases/chase-playback.md/#connecting-a-chase-for-control), [Running a Cue List](../cue-lists/cue-list-playback.md#running-a-cue-list), [Theatre programming](../cue-lists/theatre-programming.md)

 --- 
## \<Copy\> 
 Used to make copies of items (fixtures, playbacks etc). Use \<Latch\> to keep the copy function active for copying multiple items. Press twice to make linked copy.

 Example: \<Copy\> {Source Playback} {Destination Playback}

 Buttons | Action
 --------|--------
 \<Avo\> + \<Copy\> | Same as pressing \<Move\> (for consoles which don't have a Move button, but works on all consoles)
 \<Copy\> \<Copy\> | Selects Linked Copy, same as pressing \<Copy\> \[Link\]
 
 --- 
## \<Cue\> 
 Used when selecting cues in Cue Lists. Labelled Connect on some consoles, see [Connect](#Connect).

 --- 
## \<Cue +\> 
 (D9 only) Moves the next cue in the connected cue list on by one - same as \<Next Step\>.

 --- 
## \<Cue -\> 
 (D9 only) Moves the next cue in the connected cue list back by one - same as \<Prev Step\>.

 --- 
## \<Custom (wheels)\> 
 (D9 only - button to right of wheels) Not used yet.

 --- 
## \<Delete\> 
 Used to delete items. You usually need to press the item to be deleted a second time to confirm the delete, or press \<Enter\> to confirm. Use \<Latch\> to keep the Delete function active for deleting multiple items.

 Example: \<Delete\> {Playback} {Playback}

 --- 
## \<Direction\> 
 (D9 only) Used when setting direction of shapes. See [Shape Direction](../effects/shape-generator.md/#shape-direction)

 --- 
## \<Disk\> 
 Shows disk functions such as Save Show etc. If pressed when \<Avo\> held, enters System menu. See [Saving the show](../titan-basics/loading-and-saving-shows.md#saving-the-show) and [The System Menu](../system-settings/the-system-menu.md).

Buttons | Action
 --------|--------
 \<Avo\> + \<Disk\> | Enter System menu
 \<Disk\> \<Disk\> | Save the current show without asking any questions
 

 --- 
## \<Edit\> 
 Used when editing palettes. See [Changing the content of palettes](../palettes/editing-palettes.md/#changing-the-content-of-palettes).

 --- 
## \<Effect\> 
 Selects the Effect attribute group so the wheels control Prism etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Enter\> 
 Completes or accepts many commands.

 --- 
## \<Enter/B\> 
 (D9 only) Enters Scene Master preset mode. See [Scene Master](../running-the-show/playback-controls.md/#scene-master).

 --- 
## \<Exit\> 
 Leaves the current menu and goes one level back up the menu structure.

  Buttons | Action
 --------|--------
  \<Avo\> + \<Exit\> | Exit menu structure back to the top level

 --- 
## \<Exit/A\> 
 (D9 only) Exits Scene Master preset mode and goes back to Live. See [Scene Master](../running-the-show/playback-controls.md/#scene-master).

 --- 
## \<FX\> 
 (D9 only) Selects the Shape/FX menu to run shapes, key frame shapes or pixel map effects. Also used to enable/disable FX attribute group when setting masks. See [Shape menu](#Shape).

 Multiple presses followed by \<Enter\> will select the options in the Shape/FX menu - press twice then \<Enter\> to select Key Frame Shapes or three times then \<Enter\> to select Pixel Mapper.

 --- 
## \<FX (wheels)\> 
 (D9 only - button to the right of the wheels) Sets the wheels into FX mode to control shape size, speed, spread.

 --- 
## \<Fade/Delay (wheels)\> 
 (D9 only - button to right of wheels) Sets the wheels into Fade/Delay mode to control fade and delay times.

 --- 
## \<Fan\> 
 Starts Fan mode so the wheels spread out attributes rather than setting values. See [Fan Mode](../controlling-fixtures/changing-fixture-attributes.md/#fan-mode).

 --- 
## \<Fix +1\> 
 Selects the next fixture out of a range, used when programming to step through a range of fixtures one at a time. See [Stepping through selected fixtures](../controlling-fixtures.md/#stepping-through-selected-fixtures-one-at-a-time).

 --- 
## \<Fix -1\> 
 Selects the previous fixture out of a range, used when programming to step through a range of fixtures one at a time. See [Stepping through selected fixtures](../controlling-fixtures.md/#stepping-through-selected-fixtures-one-at-a-time).

 --- 
## \<Fixture\> 
 Opens the fixture/channel menu which is used when selecting fixtures from the keypad. See [Selecting fixtures and dimmers by number](../controlling-fixtures.md/#selecting-fixtures-and-dimmers-by-number-channel)

 --- 
## \<Flash On\> 
 Flashes selected fixtures while held.

 --- 
## \<Go\> 
 Runs the next cue of the connected playback, usually used when running cues from a cue list. See [Running a Cue List](../cue-lists/cue-list-playback.md/#running-a-cue-list).

 --- 
## \<Go page\> 
 Type a number to jump to Page ``<n>`` of the associated fader bank (consoles with multiple fader banks may have several of these buttons). See also \<Page +\> and \<Page -\>. See [Changing playback pages](../cues/cue-playback.md/#changing-playback-pages).
  
  Buttons | Action
 --------|--------
  \<Go page\> ``<n>`` | Switch fader bank to page n
  \<Release\> \<Go page\> | Release whole page of playbacks. See [Release Page](../cues/cue-playback.md/#releasing-a-whole-page-of-playbacks).

 --- 
## \<Gobo\> 
 Selects the Gobo attribute group so the wheels control gobo select, rotation etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Group\> 
 Opens the group menu for saving and editing fixture groups. See [Fixture Groups](../controlling-fixtures/fixture-groups.md/#using-fixture-groups). Can also be used to set levels on a group, example: \<Group\> 5 \<@\> \<@\> sets all fixtures in Group 5 to full.

 --- 
## \<Hi light\> 
 Starts or ends Hi-light mode which visually shows the selected fixture(s) on stage by increasing intensity or setting a contrasting colour. Often used with \<Fix +1\> and \<Fix -1\> buttons. See [Stepping through selected fixtures](../controlling-fixtures.md/#stepping-through-selected-fixtures-one-at-a-time).

 --- 
## \<Include\> 
 (followed by playback Select) Loads the contents of a playback back into the programmer for further editing or re-use. See [Include Function](../cues/editing-cues.md/#using-parts-of-existing-cues---the-include-function).

 --- 
## \<Intensity\> 
 Selects the Intensity attribute group so the wheels control Dimmer, Shutter etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Keyboard\> 
 (D9 only) Shows the touch screen keyboard. On other consoles there is a button in the window title bars to open the keyboard. See [Touch Keyboard](../titan-basics/workspace-windows.md/#touch-keyboard).

 --- 
## \<Latch\> 
 (D9 only) Latches the current menu so that it remains active when you complete the action. \<Latch Menu\> on other consoles, see below.

 --- 
## \<Latch Menu\> 
 Latches the current menu so that it remains active when you complete the action. Useful for copy, move etc. Useful for copy, move etc. See [The Menu/Softkeys](../titan-basics/other-parts-of-the-touch-screen.md/#the-menusoftkeys).

 --- 
## \<Left\> 
 (D9 / ST only) Left mouse button when trackball is in mouse mode.

 --- 
## \<Legend\> 
 (D9 only) (followed by a Select button) Set legend on an item. On other consoles use the \[Set Legend\] softkey at the top level menu. See [Legends and picture legends](../titan-basics/workspace-windows.md/#legends-and-picture-legends).

 --- 
## \<Levels (wheels)\> 
 (D9 only - button to right of the wheels) set wheels to Levels mode for setting attribute levels.

 --- 
## \<Level @\> 
 (D9 only) Opens the @ menu for the Intensity wheel.

 --- 
## \<Library\> 
 (Arena only) Opens the Show Library window. See [Show Library](../titan-basics/show-library.md).

 --- 
## \<Live Time\> 
 Lets you edit timing information for the currently live cue in a cue list. See [Edit Times of a running cue list](../cue-lists/editing-cue-lists.md/#edit-times-of-a-running-cue-list).

 --- 
## \<Locate\> 
 Sets selected fixtures to a "start" position with light coming out so you can program them. See [Setting fixtures to a Start Position (Locate)](../controlling-fixtures.md#setting-fixtures-to-a-start-position-locate).

 --- 
## \<Lock Axis\> 
(D9 and ST only) Not currently used.

 --- 
## \<Macro\> 
 Opens the Macro menu, which allows you to record sequences of keypresses for playback. See [Key Macro buttons](../titan-basics/front-panel-buttons.md/#key-macro-buttons). 
 
 You can also recall macros by number, example: \<Macro\> 5 \<Enter\>

 --- 
## \<Mask FX\> 
 (D9 only) Opens the Mask FX menu which allows you to create masks to block running shapes. Also available as a softkey on the Shapes and Effects menu. See [Mask Fx](../effects/shape-generator.md/#masking-shapes-using-mask-fx).

   Buttons | Action
 --------|--------
  \<Mask FX\> \<Intensity\> | Create Mask FX for intensity (same for any attribute group button)
  \<Mask FX\> \<Mask FX\> | Create Mask FX for all attribute groups

 --- 
## \<Menu Latch\> 
 Latches the current menu so that it remains active when you complete the action. Useful for copy, move etc. Useful for copy, move etc. See [The Menu/Softkeys](../titan-basics/other-parts-of-the-touch-screen.md/#the-menusoftkeys).

 --- 
## \<Min/Max\> 
 Changes current workspace window between minimum (quarter screen) and maximum (full screen) size. See [Window Size](../titan-basics/workspace-windows.md/#changing-window-size-and-appearance).

 --- 
## \<ML Menu\> 
 At top level menu, opens the Moving Light menu where you can run fixture macros and access the \[Align\] function. Also acts as Menu Latch if pressed while in a submenu. See [The ML Menu button](../controlling-fixtures/advanced-options.md/#the-ml-menu-button). Not on D9, use \<Macro\> to run fixture macros and \<Align\> to access Align function.

 --- 
## \<Move\> 
 Used to move items to different handles. Use \<Latch\> to keep the Move function active for moving multiple items.

 Example: \<Move\> {Source Playback} {Destination Playback}

 --- 
## \<Next Step\> 
 Moves to the next cue in the connected cue list using programmed fade times. Labelled \<Next Cue\> or \<Cue +\> on some consoles. See [Running a cue list](../cue-lists/cue-list-playback.md/#running-a-cue-list).

 --- 
## \<Next Time\> 
 Lets you edit timing information for the next cue in a connected cue list. See [Edit times of a running cue list](../cue-lists/editing-cue-lists.md/#edit-times-of-a-running-cue-list).

 --- 
## \<Not\> 
 Used when selecting ranges of items. See [Selecting fixtures and dimmers by number](../controlling-fixtures.md/#selecting-fixtures-and-dimmers-by-number-channel).

 Example: \<Fixture\> 1 \<Through\> 5 \<not\> 3 selects fixtures 1, 2, 4, 5

 --- 
## \<Odd/Even\> 
 Replaced by \<All\>.  Used to start and end odd/even selection from a range of selected fixtures. See [Selecting fixtures using a pattern](../controlling-fixtures.md/#selecting-fixtures-using-a-pattern).

 --- 
## \<Off\> 
 Used to deactivate specific attribute values from fixtures or in playbacks. Attributes set to Off can later be restored to their previous values. See [Deactivate attributes using Off](../cues/editing-cues.md/#deactivate-attributes-from-cues-using-off).

 --- 
## \<Open\> 
 (D9 only) Open workspace window, like double pressing View. \
 (Quartz, Titan Mobile) Show details about item, or double press to open workspace window, see [View](#view).

 --- 
## \<Open/View\> 
(Sapphire Touch, Arena, Tiger Touch only) \
 Show details about item, or double press to open workspace window, see [View](#view).

 --- 
## \<Options\> 
 Followed by **Select** button, shows options screen for item. Usually used with playbacks but can set options for other types of item. See [Playback Options](../cues/playback-options.md/)

 --- 
## \<Page +\> 
 Move to next page in the fader bank (consoles with multiple fader banks may have several of these buttons). See also \<Go Page\>. See [Changing playback pages](../cues/cue-playback.md/#changing-playback-pages).

 --- 
## \<Page -\> 
 Move to previous page in the fader bank (consoles with multiple fader banks may have several of these buttons). See also \<Go Page\>. See [Changing playback pages](../cues/cue-playback.md/#changing-playback-pages).

 --- 
## \<Palette\> 
 Opens the Palette menu which is used when recalling palettes by number. See [Recalling palettes](../palettes/using-palettes.md/#recalling-from-the-keypad).

 --- 
## \<Patch\> 
 Opens the Patch menu. See [Patching new fixtures or dimmers](../patching/patching-new-fixtures-or-dimmers.md/).

 ---

 ## \<Pattern/All\> 
 (D9 only) Used to start and end pattern selection (such as odd/even) within a range of selected fixtures. Same as \<All\> on other consoles, see [All](#All).

 --- 
## \<Playback\> 
 (Arena) Opens the Playbacks workspace window showing touch buttons for additional playback storage. \
 (D9) If pressed after \<View\>, opens the Playbacks workspace window.

 --- 
## \<Playback (wheels)\> 
 (D9 only - button to right of wheels) Sets the wheels to playback control mode.

 --- 
## \<Position\> 
 Selects the Position attribute group so the wheels control pan, tilt etc. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Preload/Auto\> 
 (D9 only) Preload the Scene Master preset state (loads the LTP values of non-illuminated fixtures so they don't visibly move when the state is faded in). See [Scene Master](../running-the-show/playback-controls.md/#scene-master).

 --- 
## \<Prev Step\> 
 Moves to the previous cue in the connected cue list using programmed fade times. Labelled \<Prev Cue\> or \<Cue -\> on some consoles. See [Running a cue list](../cue-lists/cue-list-playback.md/#running-a-cue-list).

 --- 
## \<Record\> 
 Enter Record mode to record playbacks or palettes. See [Creating a cue](../cues/creating-a-cue.md/#creating-a-cue) and [Storing a palette](../palettes/creating-palettes.md/#storing-a-palette). Press \<Record\> multiple times to step through Record Cue / Record Chase / Record Cue List / Record Timeline options.

 Buttons | Action
 --------|--------
  \<Record\> {Select} | Record programmer state to cue
  \<Record\> {Palette window button} | Record programmer state to palette
  \<Record\> {Workspace select button} | Record current workspace state to workspace select button
  \<Record\> \<Highlight\> | Record the highlight state, see [Highlight](../controlling-fixtures.md/#highlighting-the-selected-fixture-with-prevnext)
  \<Record\> \<Locate\> | Record the locate state, see [Locate](../controlling-fixtures.md#changing-the-locate-state).

 --- 
## \<Record Step\> 
 Record the programmer into the current active cue in the connected cue list. See [Editing a cue list while recording](../cue-lists/editing-cue-lists.md/#editing-a-cue-list-while-recording)

 --- 
## \<Release\> 
 Used to override the LTP behaviour of attributes when a playback is killed. See [Release](../cues/cue-playback.md/#release). \
 Can also be used to release various other items.

 Buttons | Action
 --------|--------
  \<Release\> {Master} | Releases the master to its default state (no effect on output), see [Releasing a Master](../cues/cue-playback.md#releasing-a-master).
  \<Release\> {Playback} | Release the playbacks by priority. See [Release](../cues/cue-playback.md#release).
  \<Release\> \<Clear\> | Release attributes in the programmer. See [Release](../cues/cue-playback.md#releasing-the-programmer-contents).
  \<Release\> \<Go Page\> | Release whole page of playbacks. See [Release Page](../cues/cue-playback.md/#releasing-a-whole-page-of-playbacks).
  \<Release\> \<Release\> | Release all active playbacks by priority. See [Release](../cues/cue-playback.md#release).
  \<Record\> \<Release\> | Record the release or power on state. See [Power On State](../cues/cue-playback#programming-the-release--power-on-state).

 --- 
## \<Rem Dim\> 
 Turns off all unselected fixtures. Not fitted on all consoles, can also be accessed by \<Avo\> + \<All\>. See [Turn Off Unselected Fixtures](../controlling-fixtures.md/#turn-off-unselected-fixtures-remainder-dim)

 --- 
## \<Reset\> 
 (D9 only) Clear the preset state of the Scene Master. See [Scene Master](../running-the-show/playback-controls.md/#scene-master).

 --- 
## \<Review\> 
 Re-runs the fade times of the current live cue to allow you to see timing changes. See [Edit Times of a Running Cue List](../cue-lists/editing-cue-lists.md/#edit-times-of-a-running-cue-list)

 --- 
## \<Right\> 
 (D9 / ST only) Right mouse button when trackball in mouse mode.

 --- 
## \<Scroll\> 
 Makes the wheels scroll the focussed zone up/down.

 --- 
## \<Select If\> 
 Selects all fixtures which have intensity above zero. See [Select If](../controlling-fixtures.md/#selecting-fixtures-which-are-in-a-playback).

 --- 
## \<Set\> 
 This button has become the \<Time\> button.

 --- 
## \<Shape\> 
 Selects the Shape/FX menu to run shapes, key frame shapes or pixel map effects. See [Shapes and Effects](../effects.md).

 --- 
## \<Size/Position\> 
 Moves the currently selected workspace window around the different size and position options. If \<Avo\> held also, moves the window to the other screen.

 --- 
## \<Snap\> 
 Enables Snap mode which makes \<Prev Step\> / \<Next Step\> buttons snap through cues without using the programmed fade times in cue lists or chases. See [Running a cue list](../cue-lists/cue-list-playback.md/#running-a-cue-list). Sets the Chase Snap (if a chase is connected) or Cue List Snap (if a cue list is connected) user setting in [General user settings](../system-settings/user-settings.md/#chase-snap).

 --- 
## \<Special\> 
 Selects the Special attribute group so the wheels control fixture-specific functions like modes and macros. Also used for creating masks. See [Changing Attributes using the Wheels](../controlling-fixtures/changing-fixture-attributes.md/#changing-attributes-using-the-wheels).

 --- 
## \<Stop\> 
 Stops/freezes the current cue fades. See [Running a cue list](../cue-lists/cue-list-playback.md/#running-a-cue-list). If used when already stopped, goes back a cue.

 --- 
## \<Through\> 
 Used when selecting ranges of items. See [Selecting fixtures and dimmers by number](../controlling-fixtures.md/#selecting-fixtures-and-dimmers-by-number-channel).

 Example: \<Fixture\> 1 \<Through\> 5 \<not\> 3 selects fixtures 1, 2, 4, 5

 Also when entering time or timecode values the \<And\> and \<Through\> buttons move the cursor between hours/minutes/seconds/frames.

 --- 
## \<Time\> 
 Show the Times menu which is used to set cue timing. See [Fade times](../cues/cue-timing.md/#fade-times-and-fixture-overlap).
 Also used to set fade times directly. See [Times](../titan-reference.md/#times).

 Buttons | Action
 --------|--------
 \<Time\> ``n`` | Set ``n`` second fade into programmer, will record with the next cue to be recorded
 \<Time\> \<Fixture\> ``n`` | Set ``n`` second fade into programmer for all attributes of selected fixtures


 --- 
## \<Undo\> 
 Undo the last action (an Undo list is shown in the system prompt). See [Undo/Redo](../titan-basics/other-parts-of-the-touch-screen.md/#undoredo).

 Buttons | Action
 --------|--------
 \<Avo\> + \<Undo\> | Redo (revert the last Undo change)

 --- 
## \<Unfold\> 
 followed by playback **Select**, splits out a cue list or chase onto the playback faders so each cue/step can be edited individually. See [Editing a chase using unfold](../chases/editing-a-chase.md/#editing-a-chase-using-unfold).

 --- 
## \<Update\> 
 Updates the current cue by merging the contents of the programmer. See [Updating Stored Values and Palettes used in a Cue](../cues/editing-cues.md/#updating-stored-values-and-palettes-used-in-a-cue).

 --- 
## \<View\> 
(D9, Titan Go, Pearl Expert, Tiger Touch 1) \
 Followed by **Select** button to show details about item, or double press to open workspace window. See [Palettes](../palettes/editing-palettes.md/#viewing-and-editing-the-content-of-palettes) and [Cues](../cues/editing-cues.md/#playback-and-cue-view), or [Opening Workspace Windows](../titan-basics.md/workspace-windows/#opening-and-positioning-workspace-windows).

 Also gives shortcuts to opening workspace windows and editing workspaces:

 Buttons | Action
 --------|--------
\<View\> \<Beam\> | Open Beam palettes view
\<View\> \<Colour\> | Open Colour palettes view
\<View\> \<Connect\> | Open Playback view for connected playback
\<View\> \<Copy\> | Copy workspace select button
\<View\> \<Delete\> | Delete workspace select button
\<View\> \<Fixture\> | Open Fixtures window
\<View\> \<FX\> | Open Shape palettes view
\<View\> \<Gobo\> | Open Beam palettes view
\<View\> \<Group\> | Open Groups window
\<View\> \<Intensity\> | Open Intensity View
\<View\> \<Macros\> | Open Macros window
\<View\> \<Move\> | Move workspace select button
\<View\> \<Off\> | Open Active playbacks window
\<View\> \<Options\> | Open Attribute editor
\<View\> \<Patch\> | Open Patch view
\<View\> \<Playback\> | Open Playbacks view
\<View\> \<Position\> | Open Position Palettes view
\<View\> \<Release\> | Open Active playbacks window
\<View\> \<Shape\> | Open Shape palettes view
\<View\> ``n`` \<Enter\> | Recall workspace with ID number ``n``

 --- 
## \<Visualiser\> 
 Opens the Visualiser window. See [Capture visualiser](../capture-visualiser.md/).

 --- 
## \<Wheel @\> 
(The @ buttons next to the wheels) - Open the Wheel @ menu which lets you control the attribute which is currently allocated to the wheel.

 --- 
## \<XYZ\> 
 (D9 only - button to right of wheels) Sets the wheels to XYZ position mode for moving fixtures in Visualiser or Layout Editor.