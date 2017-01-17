# LibNBT

A library for reading and writing binary NBT format.

This library also includes a parser for Mojangson, and can convert NBT to Mojangson via the .toString() methods.

Some extensions to Mojangson where made in order to make it sane:

* Byte arrays are lists of numbers surrounded by < and >
* Int arrays are lists of numbers surrounded by « and »
* Java string escapes are supported in quoted strings.
* Numbers can be suffixed with [bB], [sS], [lL], [fF], [dD] to denote them as
  byte, short, long, float and double respectively.

TODO: Write up a clean description of the Mojangson format used.
