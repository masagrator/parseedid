# parseedid
Simple code for parsing EDID with CEA-861 extension

Was designed only to retrieve highest progressive refresh rate, but you can modify source code to retrieve more informations.

Compile with DEBUG flag for verbose output.

Example how to compile:
```
g++ -O3 -static -DDEBUG parseedid.cpp -o parseedid
```
