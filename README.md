# covi
vi-like editor for Radio Shack Color Computer and TRS-80 Model 4

covi is a simple text editor for the Color Computer "Coco" and the TRS-80 Model 4, written in C and assembly language.

Both these platforms have editors of one sort or another, but trying to re-learn the key combinations for each system can be annoying.   Since vi was originally designed for systems (PDP-11) that would now be considered very constrained, it is an ideal editor to "conceptually" port to these classic machines.

While the platforms are very different, using conditional compilation there is no reason why the same general codebase can't be used.

The intention is not to replicate all of vi's features; especially because we want to keep the compiled code as small as possible.  Instead, the idea is to provide an editor that will provide a subset of the key features in vi so that the user does not have to remember a completely different command set each time they go to use their classic machine.

As well, the editor should provide some advanced support for BASIC programming on the Coco to help facilitate better ease-of-use while coding and maintaining old Coco code.

Features planned:

* Basic vi-like editing
* RSDOS / TRSDOS executable
* Support for more than 64k memory on Coco 3
* Terminate and Stay-Resident like interface on Coco 3.
* Support for basic vt100 commands, allowing access via null modem
* Ability to convert tokenized basic to/from ASCII

Key vi features
* basic editing
* cut / paste 
* basic search
* one level undo

