# Register-B-
A digital 8-bit register built using D flip-flops and tri-state buffers, designed to interact with a shared bus in an 8-bit computer system. Includes read/write control, clock, and reset. Developed as part of a VLSI design project with layout and timing analysis

## 👨‍💻 Team Members
- Aasha Chanpa – 202304001
- Astha Patel – 202304032
- Divy Vasava – 202304028
- Hiral Parmar – 202304004

## 📌 Description
An 8-bit register implemented using D flip-flops (master-slave) with tri-state buffer output. Designed for integration into an 8-bit computer system. Includes input enable, output enable, and reset control.

## 📁 Project Structure
- `src/` – Verilog modules (D latch, D flip-flop, tri-buffer, etc.)
- `simulation/` – Testbenches and waveform files
- `layout/` – Layout diagrams and delays
- `docs/` – Report (Register_B.pdf)

## 🛠 Features
- Rising-edge D flip-flop using latch pairs
- Tri-state output with read control
- Resettable synchronous operation
- Simulated Delay:
  - Pre-layout: 0.34 ns
  - Post-layout: 0.81 ns

## 🖼 Diagrams
_Add images of your schematic, layout, etc._

## ✅ Tools Used
- Verilog HDL
- Digital/EDA Simulation Tool (e.g., ModelSim, Xilinx, etc.)
- Layout tools (Magic, OpenLane, etc.)

## 📃 Report
See full report in `docs/Register_B.pdf`

## 📄 License
MIT (or specify one)
