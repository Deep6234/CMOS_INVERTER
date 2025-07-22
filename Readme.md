# INVERTER:



An inverter, in digital electronics, is a logic gate that performs the NOT operation—it inverts the input signal. It is a fundamental building block used in digital circuits. The basic function of an inverter is to output the opposite (complementary) logic level of its input.



## CMOS Inverter:



The CMOS (Complementary Metal-Oxide-Semiconductor) inverter uses both PMOS (P-type Metal-Oxide-Semiconductor) and NMOS (N-type Metal-Oxide-Semiconductor) transistors.



**DRC(Design Rule Check)** - Every fabrication process has specific design rules regarding minimum width , spacings and overlaps for transistors or metal layers.



**LVS(Layout Versus Schematic)** - It indicates that there is a mismatch between the layout and the Schematic.





The design of a CMOS inverter, one of the most fundamental yet powerful building blocks in digital design. I successfully designed the layout of a CMOS inverter using Cadence Virtuoso and ensured it was DRC and LVS Clean. To further analyze the impact of layout parasitic, I performed AV (Assura Parasitic) Extraction, which allowed me to estimate real-world effects like capacitance and resistance introduced due to layout.



##### 🛠️ What I Did:

1. Designed the schematic of the CMOS inverter using PMOS and NMOS transistors with technology Node 90nm (gpdk090 library).
2. Created a custom symbol for hierarchical design reuse.
3. Designed the layout manually with careful alignment and routing.
4. Ran DRC (Design Rule Check) – ✅ Passed
5. Ran LVS (Layout vs Schematic) – ✅ Passed
6. Performed pre- and post-layout simulations
7. Conducted timing analysis to evaluate performance



##### Performance Analysis:

1. Pre-Layout Delay: 30.1 ps
2. Post-Layout Delay: 68.5 ps
3. Pre-Layout Power: 1.287 × 10⁻⁶ W
4. Post-Layout Power: 1.445 × 10⁻⁶ W
5. Pre-Layout PDP: 3.874 × 10⁻¹⁷ J
6. Post-Layout PDP: 9.902 × 10⁻¹⁷ J





##### Key Learnings:

1. Creating a symbol enables a modular design approach.
2. DRC and LVS ensure physical correctness and schematic integrity.
3. Simulation results provide crucial insight into design efficiency.
4. Analysis of the impact of layout parasitic on delay and power.
5. Estimation of Power-Delay Product (PDP) to assess energy efficiency.
6. This exercise strengthened my understanding of how layout parasitic influence circuit performance in the backend VLSI flow.



