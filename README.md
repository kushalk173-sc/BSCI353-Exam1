# Neurophysiology Study Guide

This guide covers fundamental concepts in neurophysiology, including the structure of neurons, the generation of electrical signals, and the roles of various cell types in the nervous system. 🧠

---

## Short-Answer Quiz

1.  What is the **Neuron Doctrine**, and how does it contrast with the **Reticular Theory** proposed by Camillo Golgi?
2.  Define the **resting membrane potential** and identify the ion primarily responsible for establishing it in a typical mammalian neuron.
3.  According to **Ohm's Law**, what is the relationship between current, voltage, and conductance?
4.  Explain the concept of **electrochemical equilibrium** and the two opposing forces that are balanced to achieve it.
5.  What experimental technique did Hodgkin and Huxley use to study voltage-dependent permeability, and why was the **squid giant axon** an ideal model system for this research?
6.  Describe the roles of **voltage-gated Na+ and K+ channels** during the rising and falling phases of an action potential.
7.  What is **Na+ channel inactivation**, and why is it essential for the unidirectional propagation of an action potential?
8.  How does **myelination** by oligodendrocytes or Schwann cells increase the speed of action potential propagation?
9.  Distinguish between the goals and measurements of **voltage-clamp** versus **current-clamp** recording techniques.
10. What are the three main types of differentiated **glial cells** in the central nervous system, and what is a primary function of each?

---

## Quiz Answer Key

1.  The **Neuron Doctrine**, championed by Santiago Ramón y Cajal, posits that the nervous system is composed of **discrete, individual cells** called neurons, which are the fundamental structural and functional units. This contrasts with the **Reticular Theory**, which held that nerve cells were connected in a continuous, directly interconnected protoplasmic network or **reticulum**.
2.  The **resting membrane potential** is the difference in voltage between the inside and the outside of a cell at rest, typically around **-65 mV** in neurons. In a typical mammalian neuron, this potential is largely established by **potassium (K+)** ions, as the membrane at rest is most permeable to K+, causing the potential to be close to the K+ equilibrium potential ($E_K$).
3.  **Ohm's Law** states that current is the product of voltage and conductance ($I = gV$). This means that for a given voltage, more current will flow if the conductance is higher (e.g., more open ion channels), and for a given conductance, more current will flow if the voltage (driving force) is greater. Conductance is the inverse of resistance ($g = 1/R$).
4.  **Electrochemical equilibrium** is a state where there is no net movement of an ion across the cell membrane. It represents a balance between two opposing forces: the **chemical gradient** (diffusion), which drives ions from an area of high concentration to low concentration, and the **electrical gradient** (voltage), which moves ions based on their charge.
5.  Hodgkin and Huxley used the **voltage-clamp technique**. The **squid giant axon** was an ideal model because its large size made it possible to insert electrodes to both measure the intracellular voltage and inject the current necessary to hold, or "clamp," the membrane potential at a desired level while measuring the resulting ionic currents.
6.  During the **rising phase** (depolarization), voltage-gated **Na+ channels** open rapidly, leading to a massive influx of Na+ ions that drives the membrane potential toward the Na+ equilibrium potential ($E_{Na}$). During the **falling phase** (repolarization), the Na+ channels **inactivate**, and the slower-to-open voltage-gated **K+ channels** become fully permeable, allowing K+ ions to flow out of the cell and bring the membrane potential back down.
7.  **Na+ channel inactivation** is a process, distinct from closing, where the channel becomes non-conductive even if the membrane is depolarized. This process is crucial for **unidirectional propagation** because it creates a **refractory period** behind the advancing action potential, preventing it from reversing direction.
8.  **Myelin** is a lipid-rich wrapping that dramatically increases the membrane resistance of the axon. This forces the current to flow farther down the axon's interior, speeding up the passive spread of depolarization to the next **node of Ranvier**, where the voltage-gated channels are concentrated. This process is known as **saltatory conduction**.
9.  In a **voltage-clamp** recording, the experimenter *controls the membrane voltage* and *measures the ionic current* required to maintain that voltage. In a **current-clamp** recording, the experimenter *controls the current* injected into the cell and *measures the resulting changes in membrane voltage*.
10. The three main types are **astrocytes**, **oligodendrocytes**, and **microglial cells**. Astrocytes maintain the chemical environment; Oligodendrocytes lay down myelin in the CNS; Microglial cells act as scavengers.

---

## Essay Questions

1.  Trace the complete sequence of events that constitutes a single action potential. Your explanation should detail the precise, time-dependent behavior of voltage-gated sodium and potassium channels and how these factors shape the distinct phases of the action potential waveform.
2.  Compare and contrast the three major methods for visualizing neurons: the Golgi stain, immunolabeling, and genetic labeling (e.g., using GFP).
3.  Using the principles of the Goldman Equation, explain why the resting membrane potential of a neuron is primarily determined by potassium permeability but is not identical to the potassium equilibrium potential.
4.  Describe the biophysical mechanisms that confer ion selectivity and voltage sensitivity to ion channels. How does the structure of the "selectivity filter" in a potassium channel allow it to pass K+ ions while excluding smaller Na+ ions?
5.  Explain how the properties of ion channels contribute to the diversity of neuronal firing patterns, giving examples of specific channel types.

---

## Exam #1 Review Q&A

This section addresses the topics from the review guide, organized by concept.

### Electrical & Chemical Fundamentals

**Q: How do electrical forces and chemical gradients create an equilibrium potential?**
A: An **electrochemical gradient** has two components: a chemical force (the concentration gradient) pushing ions from high to low concentration, and an electrical force (the membrane voltage) attracting or repelling ions. The **equilibrium potential** ($E_x$) is the specific voltage where these two forces perfectly balance each other out, resulting in no net movement of that ion. The **Nernst equation** calculates this value based on ion concentrations inside and outside the cell. For example, since there is much more K+ inside a neuron than outside, the equilibrium potential for K+ ($E_K$) is negative (~ -80 mV), representing the negative voltage needed to prevent K+ from leaving.

**Q: How does the Goldman equation explain the resting membrane potential?**
A: The **Goldman equation** expands on the Nernst equation by considering the relative **permeabilities** (or conductances) of multiple ions simultaneously. A neuron's resting membrane potential (~ -65 mV) is primarily set by K+ because the membrane at rest is most permeable to K+. However, a small, continuous leak of Na+ into the cell makes the potential slightly more positive than the K+ equilibrium potential ($E_K$).

**Q: What is the purpose of active transporters like the Na+/K+ pump?**
A: Active transporters use energy (ATP) to move ions **against** their concentration gradients. The **Na+/K+ pump** is crucial because it pumps 3 Na+ ions out for every 2 K+ ions it pumps in. This action maintains the high external Na+ and high internal K+ concentrations that are essential for establishing the resting potential and powering action potentials. If the pump fails (e.g., due to lack of ATP), these gradients would dissipate, and the membrane potential would approach 0 mV, rendering the neuron unable to fire.

### The Action Potential

**Q: What are the steps of an action potential, including channel states and ion flow?**
A:
1.  **Rising Phase (Depolarization):** When a neuron reaches threshold (~ -50 mV), voltage-gated **Na+ channels open rapidly**. A massive influx of Na+ ions causes the membrane potential to shoot up towards $E_{Na}$ (~ +60 mV).
2.  **Falling Phase (Repolarization):** At the peak, voltage-gated **Na+ channels inactivate** (they become blocked and non-conductive), stopping the Na+ influx. Simultaneously, the slower voltage-gated **K+ channels fully open**. K+ ions rush out of the cell, causing the membrane potential to drop back down. 
3.  **After-Hyperpolarization:** The K+ channels are slow to close. The continued efflux of K+ causes the membrane potential to briefly dip below the resting potential, approaching $E_K$.
4.  **Refractory Period:** During repolarization and hyperpolarization, the inactivated Na+ channels cannot be reopened, preventing the action potential from firing again immediately or traveling backward.

**Q: What are the key differences between voltage-gated Na+ and K+ channels?**
A:
* **Kinetics:** Na+ channels activate (open) and inactivate **very quickly**. K+ channels activate and deactivate (close) much **more slowly**.
* **Inactivation:** Na+ channels have a distinct **inactivated state** that automatically occurs shortly after opening. The K+ channels involved in repolarization do not inactivate; they simply deactivate when the membrane potential becomes negative again.

### Experimental Techniques

**Q: What is the difference between voltage-clamp and current-clamp recordings?**
A: They are two different ways to measure a neuron's electrical activity:
* **Voltage-Clamp:** The goal is to study **ionic currents**. The experimenter **sets (clamps) the membrane voltage** to a specific level and measures the **current** the amplifier must inject to keep the voltage constant. This measured current is equal and opposite to the current flowing through the ion channels.
* **Current-Clamp:** The goal is to study **membrane potential changes** (like action potentials). The experimenter **injects a known amount of current** and measures the resulting **change in voltage**. This mimics what happens when a neuron receives synaptic input.

**Q: How do TTX and TEA help us understand ionic currents in a voltage-clamp experiment?**
A: These drugs are channel blockers that allow researchers to isolate specific currents. When you clamp a neuron at a depolarized potential (e.g., 0 mV), you see an early, transient inward current (Na+) and a late, sustained outward current (K+).
* Adding **Tetrodotoxin (TTX)** blocks the voltage-gated Na+ channels, eliminating the inward current and leaving only the **outward K+ current**.
* Adding **Tetraethylammonium (TEA)** blocks the voltage-gated K+ channels, eliminating the outward current and leaving only the **inward Na+ current**.

**Q: What does "rectification" mean for K+ channels?**
A: **Rectification** means an ion channel passes current more easily in one direction than the other. **Inward-rectifier K+ channels**, for example, are crucial for maintaining the resting potential. They allow K+ to flow *into* the cell easily when the membrane is hyperpolarized but resist the flow of K+ *out* of the cell at more depolarized potentials. This prevents the cell from losing too much K+ during repetitive firing.

### Channel Structure & Diversity

**Q: How do K+ channels selectively pass K+ ions while excluding smaller Na+ ions?**
A: The key is the **selectivity filter**, a narrow part of the channel pore lined with carbonyl oxygen atoms. For a K+ ion to pass through, it must shed its surrounding water molecules. The carbonyl oxygens are perfectly spaced to mimic this water shell, stabilizing the "naked" K+ ion. A smaller Na+ ion is too small to be properly stabilized by all the oxygens at once, making it energetically unfavorable for it to shed its water and enter the pore.

**Q: Why is myelin important, and what happens when it's lost?**
A: Myelin is an insulating sheath that dramatically speeds up action potential propagation through **saltatory conduction**. It prevents current from leaking out across the membrane, forcing the electrical signal to jump from one **Node of Ranvier** (a gap in the myelin) to the next. The loss of myelin, as seen in diseases like Multiple Sclerosis (MS), causes the current to leak out, slowing or completely blocking the propagation of action potentials, leading to severe neurological deficits.

---

## Glossary of Key Terms

| Term | Definition |
| :--- | :--- |
| **Action Potential** | A rapid, all-or-nothing electrical signal that travels along an axon. Also called a "spike." |
| **Astrocyte** | A star-shaped glial cell in the CNS that maintains the chemical environment for neurons. |
| **Axon** | The long extension from a neuron that relays action potentials to other cells. |
| **Conductance (g)** | A measure of how easily charge flows across the membrane; the inverse of resistance ($g = 1/R$). |
| **Current (I)** | The flow of electrical charge, carried by ions in neurons. |
| **Depolarization** | A change in membrane potential making the inside of the cell less negative. |
| **Electrochemical Equilibrium** | The state where the chemical and electrical gradients acting on an ion are balanced, resulting in no net ion flow. |
| **Equilibrium Potential ($E_x$)** | The membrane voltage at which a specific ion is in electrochemical equilibrium, calculated by the Nernst equation. |
| **Glia (Neuroglia)** | The "support" cells of the nervous system that do not generate action potentials. |
| **Goldman Equation** | An equation that calculates the membrane potential based on the relative permeabilities and concentrations of multiple ions. |
| **Hyperpolarization** | A change in membrane potential making the inside of the cell more negative. |
| **Myelin** | An insulating lipid-rich sheath around axons that speeds up action potential propagation. |
| **Nernst Equation** | An equation used to calculate the equilibrium potential for a single ion. |
| **Neuron Doctrine** | The principle that the nervous system is made of discrete, individual cells (neurons). |
| **Ohm's Law** | The principle that current equals the product of voltage and conductance ($I = gV$). For an ion, it is $I_x = g_x(V_m - E_x)$. |
| **Oligodendrocyte** | A glial cell in the CNS that produces myelin. |
| **Patch Clamp** | A recording technique to measure the currents flowing through single ion channels or the entire cell. |
| **Resistance (R)** | The opposition to the flow of electrical current; the inverse of conductance ($R = 1/g$). |
| **Resting Membrane Potential (RMP)**| The voltage difference across a neuron's membrane when it is not actively signaling. |
| **Reticular Theory** | The obsolete theory that the nervous system was a continuous network of interconnected cells. |
| **Schwann Cell** | The glial cell in the peripheral nervous system (PNS) that produces myelin. |
| **Synapse** | The specialized junction where information is transferred between two neurons. |
| **Tetrodotoxin (TTX)** | A potent neurotoxin from pufferfish that blocks voltage-gated sodium (Na+) channels. |
| **Voltage Clamp** | An experimental technique used to measure ion currents while holding the membrane voltage at a set level. |

