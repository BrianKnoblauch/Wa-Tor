# Wa-Tor

Will contain versions for various systems.  Expect some to be text and others to be graphics depending on limitations of platform memory, speed, and my own ability to come up with code that's not horrible.  If single file it will be in the root, if multi-file it will get a subdirectory.

Atari BASIC files can be saved to/loaded from host drives via the Altirra emulator by setting up H: in System / Configure System / Peripherals / Devices.  Example, setting up as H1/H6, use H6 to automatically handle CR/LF.  Use LIST/ENTER for text instead of the tokenized/binary version that SAVE/LOAD generates.  Examples: save from Altirra to host with LIST "H6:ATARI600.BAS".  Load into Altirra with ENTER "H6:ATARI600.BAS"
