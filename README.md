Project Title: Digital Trainer Kit — 2-input logic trainer with selectable gates and 7-segment display (For SRM Institute of Science and Technology, Digital Electronics Lab)

Objective: To design and implement a compact digital trainer kit that allows students to experiment with basic combinational logic and observe results on a 7-segment display. The kit shall provide two input switches, an 8×1 selection mechanism to choose common logic functions (AND, OR, NOT, NAND, NOR, XOR, XNOR, Reserved), and hardware-only decoding to display the selected function’s output as a visible digit (0 or 1) on a seven-segment display. The kit is intended for hands-on learning, demonstration, and lab experiments in the SRM IST Digital Electronics course.

Functionality: The digital trainer kit takes two inputs (A, B) and, using selection lines (SEL), generates the output of different logic gates (AND, OR, NOT, NAND, NOR, XOR, XNOR). The selected output (Y) is shown on a 7-segment display, where 0 displays as digit 0 and 1 displays as digit 1.

Pin Description: VCC – +5V supply GND – Ground A, B – Input switches SEL[2:0] – Gate selection lines Y – Output of selected logic function SEG_A to SEG_G – Seven segment display pins COM – Common cathode of display (to GND)
