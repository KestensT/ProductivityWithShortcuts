# Outline

## [Chapter 1 - Basics](chapter1.md)
* `ctrl+c`, `ctrl+v`
* Keep your hands on your keyboard
* How to look up any actions' shortcut `ctrl+shift+a`, `double shift`
* IntelliJ's _Productivity Guide_
* Undo, Redo with `ctrl+z` and `ctrl+shift+z`
* Indenting, formatting with `tab`, `shift+tab` and `ctrl+alt+l`

## [Chapter 2 - Navigation](chapter2.md)
* Word-skipping `ctrl+arrows`
* Begin/End of Line `home`, `end`
* Begin/End of File `ctrl+home`, `ctrl+end`
* CamelHumps (+ how to toggle)
* Jumping methods (`alt+up,down`)
* Jump to error `F2`
* Jump to last edit position `ctrl+shift+backspace`
* Jump into/Drill Down/Show Usage `ctrl(+alt)+b`
* History and its importance `ctrl+alt+left,right`
* Show in Project `alt+F1`
* Jump to line `ctrl+g` (example with paste from stacktrace)
* Navigate to method `ctrl+F12` (example with paste from stacktrace and quick check equals impl)
* `alt+F7` vs. `ctrl+alt+h`

## [Chapter 3 - Selection](chapter3.md)
* Move + Select `ctrl+shift+arrows`
* Expand Selection `ctrl+w`
* Using Selection to help Navigation (e.g. _Fluent API_)
* Wrapping (IntelliJ feature)

## [Chapter 4 - Line Editing](chapter4.md)
* Yank `ctrl+y`
* Duplicate line `ctrl+d`
* Moving lines with and without constraints `ctrl+shift+up,down` vs. `alt+shift+up,down`
* Start new line `ctrl+enter`
* Join lines `ctrl+shift+j`

## [Chapter 5 - Embedded Windows](chapter5.md)
* Opening/Closing (Toggling) `alt+number` `ctrl+F4`
* Switching tabs `alt+left,right`
* Why resizing is for dummies `ctrl+shift+F12`
* Navigation from Embedded Windows `ctrl+enter` vs. `F4`

## [Chapter 6 - IntelliJ's Suggestions](chapter6.md)
* IntelliJ's Auto-correct `ctrl+shift+enter`
* Autocomplete `ctrl+space` vs. `ctrl+shift+space`
* _QuickFix_ (:bulb:) `alt+enter`
* Creating _stuff_ `alt+ins`
* Deleting _stuff_ `alt+del`
* View JavaDoc `ctrl+q`
* View parameters `ctrl+p`

## [Chapter 7 - Finding/Buffer](chapter7.md)
* Find word and add to buffer `ctrl+F3`
* Find next occurrence from buffer `F3`

## [Chapter 8 - Multiple Cursors](chapter8.md)
* Toggle Column Mode `alt+shift+ins`
* `alt+j`, `alt+shift+j` and `ctrl+alt+shift+j`

We'll see a lot of different cases, such as but not limited to:
* TestBuilders
* Testing Enum lists
* Making a csv list from XML

## [Chapter 9 - Endgame](chapter9.md)
We'll make a full exercise where you'll:

1. Create a new class that resides in a new package and has to interact with another existing class
2. Create a new test for that class
3. Create a new TestBuilder for the existing class
4. Perform a _red, green, refactor_
5. (Optional) commit and push