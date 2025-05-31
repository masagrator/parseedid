# parseedid
Simple code for parsing EDID with CEA-861 extension

Was designed only to retrieve highest progressive refresh rate, but you can modify source code to retrieve more informations.

Compile with DEBUG flag for verbose output.

Example how to compile for Windows from linux:
```
x86_64-w64-mingw32-g++ -O3 -static -DDEBUG parseedid.cpp -o parseedid
```
