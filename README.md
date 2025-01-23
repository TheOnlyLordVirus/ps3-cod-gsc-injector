# ps3-cod-gsc-injector
Multi-Cod eboot support for injection of GSC's.

The gsc injector code was compiled using the ps3 sdk, the bytes from the compiled gsc injector code were then inserted to a region of nullbytes in the Call of Duty eboot.bin executable. Finnally the entry point to the game contains a trampoline to starting address of the compiled gsc injector.
