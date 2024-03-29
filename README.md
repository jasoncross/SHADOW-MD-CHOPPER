# SHADOW-MD-CHOPPER
 SHADOW MD Implementation for C1-10P Droid
 Based on https://astromech.net/forums/showthread.php?21984-SHADOW-Marcduino-Update-Thread

Note:  This is still very much a work in progress.  Use at your own risk.

Assumes the following hardware:
* Arduino Mega with USB shield and bluetooth
* Marcduino
* FlthyHP
* MP3 Trigger
* Dual PS3 Nav Controllers

Changes from initial SHADOW-MD:

* Auto-dome rewritten.  It now does randomization of turn timing, degrees and speed, does random sounds with turning, and can use a reed switch and magnet to know where "home" is for the dome facing forward.
* Up, Left and Right buttons trigger random sounds from "groups" for the following to make mixing into "conversations" easier.
	* Up = General Sounds
	* Left = Chat Sounds
	* Right = Response (Short) Sounds
* Above sound triggers track last sound played to ensure not getting the same sound played twice in a row.

Thanks to Darren Blum for the original SHADOW project, Vint43 for the MD variant, Christopher Hunter for many of the sounds I have remixed and included, CuriousMarc for his MarcDuninos, FlthyMcnasty for his HPs, and many other R2 and Chopper builders for the ongoing support!
