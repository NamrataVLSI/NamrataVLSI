# Namrata Yadav

**M.S. Computer Engineering — Analog & Mixed-Signal IC Design**
San Diego State University · San Diego, California

### 🔗 Portfolio → **[namratavlsi.github.io](https://namratavlsi.github.io)**

📧 namratayadav.cal@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/namrata-yadav)

---

## About

I design transistor-level analog and mixed-signal CMOS circuits and take them through full-custom
layout, physical verification, and post-layout characterization.

Much of my work is diagnostic — finding why a circuit deviates from expectation and tracing it back
to sizing, parasitics, mismatch, process variation, layout-dependent effects, or connectivity.

I also work on hardware–software co-design, bridging transistor-level CMOS implementations with
Python-based spiking neural network models to study how circuit non-idealities affect system-level
performance.

**Recent focus:** device reliability and aging analysis (NBTI, HCI) in Cadence ADE, and
characterization across PVT corners and Monte Carlo mismatch.

## Seeking full-time roles in

Analog / mixed-signal IC layout · Custom physical design · Failure analysis · Device
characterization and debug · Physical design

---

## Repositories

| Repository | What's in it | Tools |
| --- | --- | --- |
| **[Analog-IC-Design-and-Layout-](https://github.com/NamrataVLSI/Analog-IC-Design-and-Layout-)** | Ten analog CMOS blocks — bandgap reference, LDO, single-stage OTA, two-stage op-amp, comparator, current mirrors, differential pair, level shifter, Schmitt trigger, bias circuits. Each with a design report and a layout & verification report. | Cadence Virtuoso, Spectre, PVS, GPDK45 |
| **[Mixed-Signal-Design](https://github.com/NamrataVLSI/Mixed-Signal-Design)** | Charge-pump PLL built block by block — PFD, charge pump, loop filter, VCO, divider, clock buffer, top-level integration — plus 8:1 serializer / 1:8 deserializer. SAR ADC and DAC planned. | Cadence Virtuoso, Spectre, GPDK45 |
| **[Digital-Custom-IC](https://github.com/NamrataVLSI/Digital-Custom-IC)** | 11-track standard-cell library, transmission-gate logic, combinational and sequential circuits, counters, and a 6T SRAM bitcell and array. | Synopsys Custom Compiler, IC Validator, StarRC, SAED 28/32 nm |
| **[Neuromorphic-and-System-Level](https://github.com/NamrataVLSI)** | CMOS leaky integrate-and-fire neuron: transistor-level design, F–I characterization, membrane time-constant extraction, and a circuit-calibrated SNN model evaluated on MNIST. | Cadence Virtuoso, Spectre, Python, SpikingJelly |
| **[NamrataVLSI.github.io](https://github.com/NamrataVLSI/NamrataVLSI.github.io)** | Source for my portfolio site. | HTML, CSS |

---

## Technical skills

**Analog & mixed-signal design**
Transistor-level CMOS design · Device sizing · Biasing and operating point · Current mirrors ·
Differential pairs · OTA · Two-stage op-amp · Comparator · Bandgap reference · LDO · Level shifter ·
Schmitt trigger · PLL (PFD, charge pump, loop filter, VCO, divider) · Serializer / deserializer

**Analysis & characterization**
DC / transient / AC · Loop stability and phase margin · PSRR · PVT corners · Monte Carlo mismatch ·
Temperature characterization · Reliability aging (MOSRA) · Device characterization — VTH, gm, ID,
Early voltage, channel-length modulation, subthreshold slope, weak and strong inversion

**Custom layout**
Full-custom CMOS and FinFET layout · Hierarchical floorplanning · Common-centroid · Interdigitation ·
Device matching · Dummy devices · Diffusion sharing · Guard rings · Substrate taps · Deep N-well
isolation · Latch-up prevention · Layout-dependent effects (WPE, STI stress, poly spacing) ·
Parasitic-aware routing · Power planning · EM / IR awareness · Metal density · Euler path
optimization · Cell abutment · Pin-access planning

**Verification & signoff**
DRC · LVS · ERC · Antenna checks · PEX · Post-layout simulation · Pre-/post-layout correlation

**Physical design**
RTL-to-GDS · Synthesis · Floorplanning · Placement · CTS · Routing · STA · SDC · Setup/hold ·
WNS/TNS · Timing closure · PPA analysis

**Tools** — Cadence Virtuoso Studio, Layout XL, Spectre, ADE Explorer/Assembler/Maestro, ViVA, PVS ·
Synopsys Custom Compiler, PrimeSim, IC Validator, StarRC, Design Compiler, IC Compiler II, PrimeTime,
PrimeWave · SAED 28/32 nm, GPDK45, NCSU CDK

**Programming** — Python · MATLAB · Verilog · TCL · Bash · UNIX/Linux · LaTeX

---

## My design flow

```
Specification → Circuit architecture → Transistor-level schematic → Device sizing & biasing
      → Pre-layout simulation → Full-custom layout → DRC → LVS → ERC → PEX
      → Post-layout simulation → PVT, Monte Carlo & aging analysis
```

---

## Currently working on

- Re-sizing and rebuilding the CMOS LIF neuron in GPDK45 (the first version used the NCSU 0.35 µm CDK)
- Reliability and aging analysis flows in Cadence ADE
- SAR ADC and DAC blocks for the mixed-signal repository

## Currently learning

Advanced analog layout techniques · SKILL scripting for layout automation · FinFET layout ·
High-speed mixed-signal design

---

Every project here documents the full engineering workflow — design intent, simulation, layout
methodology, verification results, and what the layout decisions cost the circuit.
