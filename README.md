Eagle-Library
=============
Library of various eagle components. feel free to pull request!

######Consistencey Rules

- use the latest version (7.3.0)
- do not modify the settings
 - .1" line grids
 - .01" subgrid
 - you can modify these temporarily, but do not commit the `<settings>`, `<layer/>` or `<grid/>` block of any files
- Device names for sepcific parts should be the name of the IC eg. `LM317` or `TXB0104`
- Device names for generic parts should be simple eg. `resistor` or `ceramic capacitor`
- Footprints should be the name of the footprint eg. `SOIC-8` or `PTH .4` (for a .4 inch separated PTH resistor)
- all origins should be on the *very center* of the footprint. For irregularly shaped componts centers will be decided on a case-by-case basis.

---------------
######Licensing

Licensed under the [Creative Commons ShareAlike 4.0 International][1].

Some parts reused from the [Sparkfun Eagle Libraries][2].

[1]: https://creativecommons.org/licenses/by-sa/4.0/
[2]: https://github.com/sparkfun/SparkFun-Eagle-Libraries
