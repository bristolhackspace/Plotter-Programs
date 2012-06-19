This page will contain the source-code for the various programs that we run to make interesting output from the plotter. The plotter itself is a Roland DXY-990 flat-bed 8-pen plotter with a maximum paper size of A3. It has both serial (RS-232) and parallel (IEEE 1284) interfaces, but we generally use the parallel one for convenience.

Although the plotter will accept up to eight pens, our current software utilises at most four. Most of our plotter programs, in fact, are designed for a single pen. Fine lines are best drawn with the V-ball pens, while thicker lines are made with the Staedtler Tri-Plus pens.

Ordinary copier paper is used, in either A4 or A3 size. It is held down on the plotter's flat drawing surface by electrostatic attraction. The electrostatic cling is switched on and off by the “paper hold” button on the plotter's control panel. Loading and unloading of paper is manual.

All the code is written in C apart from 'spiro', which is in C++. It runs on Linux, but could probably be ported to other systems without difficulty.

* Spiro - uses four pens to simulate a Spirograph
* Tree - draws a fractal tree recursively
* Dala2 - draws a mandala-like circular pattern
* Op - draws the “op-art” pattern of concentric quadrilaterals
* Hilb - draws the Hilbert curve using four pen colours