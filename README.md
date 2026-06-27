# My Codeworks â€” HDLBits Solutions

Personal solutions to all HDLBits problems, solved in Verilog HDL. HDLBits is a collection of digital logic design exercises covering combinational logic, sequential logic, finite state machines, and arithmetic circuits.

> ðŸ”— HDLBits Platform: [hdlbits.01xz.net](https://hdlbits.01xz.net)

> **Note:** All solution files currently lack `.v` extensions (e.g. `Andgate`, `Dff`). Adding `.v` to each filename will enable GitHub syntax highlighting. This will be done progressively.

---

## Problems Solved

### Combinational Logic

| Problem | File | Concept |
|---------|------|---------|
| AND gate | `Andgate` | Basic gate |
| â€” | â€” | Add more as solved |

### Sequential Logic â€” Flip-Flops & Latches

| Problem | File | Concept |
|---------|------|---------|
| D Flip-Flop | `Dff` | Basic DFF |
| D Flip-Flop with enable (16-bit) | `Dff16e` | DFF with enable |
| 8-bit DFF with async reset | `Dff8ar` | Async reset |
| 8-bit DFF with sync reset | `Dff8p` | Sync reset (check file list) |
| D Latch | `DLatch` | Level-sensitive latch |
| â€” | â€” | Add more as solved |

---

## Repository Structure (Proposed)

As the solution count grows, reorganise into topic folders:

```
my-codeworks-HDLBits/
â”œâ”€â”€ README.md
â”œâ”€â”€ combinational/
â”‚   â”œâ”€â”€ andgate.v
â”‚   â”œâ”€â”€ norgate.v
â”‚   â””â”€â”€ ...
â”œâ”€â”€ sequential/
â”‚   â”œâ”€â”€ dff.v
â”‚   â”œâ”€â”€ dff16e.v
â”‚   â”œâ”€â”€ dff8ar.v
â”‚   â””â”€â”€ ...
â”œâ”€â”€ fsm/
â”‚   â””â”€â”€ ...
â””â”€â”€ arithmetic/
    â””â”€â”€ ...
```

> Currently all files are in the repo root without `.v` extension. Reorganization is in progress.

---

## Progress Tracker

- [x] Basic Gates (AND, OR, NOT, XOR, XNOR...)
- [x] D Flip-Flops (basic, with enable, with reset)
- [x] D Latch
- [ ] Shift Registers
- [ ] Counters
- [ ] FSMs (Mealy, Moore)
- [ ] Arithmetic (Adders, Multipliers)
- [ ] Verification problems

---

## How to Run Any Solution

```bash
# Using Icarus Verilog (install with: sudo apt install iverilog)
iverilog -o sim solution_file.v testbench.v
vvp sim

# View waveform with GTKWave
gtkwave dump.vcd
```

---

## What to Add Next

- [ ] Add `.v` extension to all existing files
- [ ] Complete the problems list in the table above
- [ ] Reorganize into `combinational/`, `sequential/`, `fsm/`, `arithmetic/` folders
- [ ] Add brief comment in each file explaining the problem being solved
- [ ] Set GitHub topics: `verilog` `hdlbits` `digital-logic` `combinational` `sequential` `fpga` `practice`

---

## License

MIT License
