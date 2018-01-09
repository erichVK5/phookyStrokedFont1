# phookyStrokedFont1
A pcb-rnd and gEDA PCB layout compatible font based on https://github.com/phooky's work

The work is licenced under the MIT licence.

The font itself can be generated in the file

  default_font

by using the python utility on a suitable ROM

  ./font_to_pcb.py > default_font

For use in gEDA PCB, it must replace /usr/share/pcb/default_font

For use in pcb-rnd, the font can be loaded as an additional font via the font selector menu, or CTRL-Shift-F

The font_to_pcb.py utility was written for use with ROMS in the https://github.com/phooky/Apple-410/ repository, and can be modified fairly easily by those wishing to implement other stroked a.k.a. centreline defined font formats, i.e. Hershey format for eggbots etc...
