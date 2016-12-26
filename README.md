# em-snowball
Level9 interpreter to javascript (with emscripten)

Test to port [Level 9 interpreter](https://github.com/DavidKinder/Level9/) to javascript (through Emscripten)

## Done
* Simple transpiled the C code to javascript with emcc
* Modified C to load SNOWBALL.DAT as default (embeded .DAT, .HRC and .CGA)

## Notes
* «Works» only on Firefox (tested on FF50.1.0)
* Type command and enter, then cancel, to make it work (main loop related?)
* On Chromium/e it doesn't show the text. Input shoud work.
* On web-app text uotput is shown in console
* If cancel is pressed twice it enters into an infinite loop "What now? / Nothing happens"

## To Do
* Modify main loop
* Create a proper UI
* Check if graphics works / are implemented
* Check if save / restore works
