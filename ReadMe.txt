
http://remotescripts.blogspot.com

-----------------------------
FCB1020 revision 3 for Live 9
-----------------------------

This set of Python scripts provides APC40 emulation and combination mode for the FCB1010 MIDI foot controller. Compatible with Live 9, on PC or mac. Can also be used as a generic APC emulation script, compatible with most MIDI controllers.

To use, drop the FCB1020 folder into Ableton's MIDI Remote Scripts directory, and select FCB1020 from the MIDI Preferences dialog. Choose appropriate MIDI Input port, and set Output to None.

To dump sysex, set Input port to None, then select appropriate Output port. To prepare FCB1010 to receive sysex dump (for stock firmware), press and hold the "Down" pedal while powering on, press the "Up" pedal twice, then press "7". Dump sysex, then press and hold "Down" pedal until countdown ends.

Switch Track Input to "On" when using Drum Rack mappings. Consider switching Takeover Mode to "Value Scaling" for smoother foot pedal operation. 

Custom mappings can be made by editing the file MIDI_map.py with any text editor; see within MIDI_map.py for further instructions.

An FCB1010 map layout in PDF format, with editable text fields, is included for reference. See MIDI_map.py for a complete list of functions which are available for MIDI mapping. Default mappings are shown on included JPG files.


----------------
Revision History
----------------

2013-03-16
* FCB1020 revision 3 - Live 9 compatibility fix (not backwards compatible with Live 8.x)

2012-01-06
* FCB1020 revision 2 - Live 8.2 compatibility fix

2010-09-08
* FCB1020 revision 1 - added customization option to handle controllers which use MIDI CC messages for buttons/pads

2010-09-07 
* Initial FCB1020 release

Visit http://remotescripts.blogspot.com for the latest updates and more information


----------
DISCLAIMER
----------

THESE FILES ARE PROVIDED AS-IS, WITHOUT ANY WARRANTY, EXPRESSED OR IMPLIED, INCLUDING BUT NOT LIMITED TO FITNESS FOR ANY PARTICULAR PURPOSE.