# uLisp_nRF52840
uLisp for the nRF52840

This uLisp source file is essentially the same as the version 2.4 uLisp posted at www.ulisp.com for the BBC:microbit, except that some of the elements have been reordered and some extra forward references have been added so that it compiles under PlatformIO for the nRF52840.  Also, the uLisp workspace has been expanded to 16,000 cells.

To take full advantage of the nRF52840's 256KB RAM memory, you will need to use the attached linker file, nrf52_xxaa.ld.  Simply copy it over the file of the same name before doing the build using PlatformIO.  After doing so, you will have 16x the uLisp cells available on a BBC:microbit, and 4x the uLisp cells available on an nRF52832.
