Fork based on https://github.com/Entroper/FF1Disassembly

Disch did all the work with dissasembling Final Fantasy 1 for the NES.
This is a refresh and reorganization of the orginal repository, with
the following changes:

* The nesheader.bin file has been replaced by nes2header.inc macros

* All binary files have been moved to the "bin" folder

* All binary files are now included though the use of .incbin

* All .asm files have been moved to the "src" folder

* nes.cfg has been updated to put all output in the "build" folder

* Minor junk files have been deleted