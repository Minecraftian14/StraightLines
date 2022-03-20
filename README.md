# Math utility for working with straight lines.

[![](https://img.shields.io/discord/872811194170347520?color=%237289da&logoColor=%23424549)](https://discord.gg/Ar6Zuj2m82)

To get started, create a line using the static method in `Line` class 

`​Line​ ​fromTwoPoints​(​float​ ​x1​, ​float​ ​y1​, ​float​ ​x2​, ​float​ ​y2​)`

This project consists of two types of implementation to represent the straight lines. 
`SlopeConstantLine` which represents a line of the form `y = mx + c`.
While the `InvertedSlopeConstantLine` represents  a line of the form `x = my + c`.

The static method automatically chooses what kind of line will be best given the case (of points).

Please check out the various methods available in [Line](https://github.com/Minecraftian14/StraightLines/blob/main/src/main/java/com/mcxiv/util/Line.java) which can be used to perform calculations based in straight lines.
