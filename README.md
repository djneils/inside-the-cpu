# Inside the CPU

An animated diagram of a Von Neumann CPU for teaching registers, buses and the fetch–decode–execute cycle (OCR A Level Computer Science, H446). Values move between the PC, MAR, MDR, CIR, accumulator and RAM one step at a time.

## Features

### The diagram
- ALU, control unit, accumulator, PC, MAR, MDR and CIR, with the address, data and control buses
16 locations of RAM showing instructions and data
- Each stage of the cycle (PC → MAR, PC++, RAM → MDR, MDR → CIR, decode, execute) animated in turn
- A trace table that fills in as the program runs

### Programs
- Ready-made programs: add two numbers, input and double, a missing HLT, count down, bigger of two, three times table
- Write your own assembly (labels and `DAT` supported) and load it into RAM, or type straight into RAM cells
- Assembly or binary view of memory

### Extra tabs
- **Build the CPU**: a guided walkthrough that adds each component and bus to the diagram one at a time, with a definition of each
- **Inside the RAM**: how addresses pick out locations, with a find-the-location activity

### In the classroom
- **Next step**, **Step back**, **Whole cycle** and **Run** with speed control (space bar steps)
- Questions mode that pauses to ask the class what happens next
- **Board mode** for a large, uncluttered view on a whiteboard

## How to Use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari). Nothing to install, no login.
2. Choose a program and press **Load into RAM**
3. Press **Next step** (or the space bar) to move through fetch, decode and execute
4. Turn **Questions** on to have the class predict each step

## Use Cases

- Teaching the FDE cycle and the role of each register
- Linking LMC programs to what happens in hardware
- Revision before assessments on the processor

## Tech

- A single HTML file: HTML, CSS and plain JavaScript
- No libraries, no build step, no backend
- Uses the browser's local storage to remember your settings
- Light and dark themes

---

## License

Copyright © Neil Southin. Free for personal use. Schools, colleges, and organisations wishing to use this in classrooms or on a VLE must get in touch first — see [LICENSE.md](LICENSE.md) for full details or email **southinn@colchsfc.ac.uk**.
