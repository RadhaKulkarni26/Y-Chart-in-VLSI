# Y-Chart in VLSI

- While designing a VLSI circuit we follow a certain Design Flow which will start from design specifications and end at fabrication and Packaging.

- The complete VLSI design flow can be divided into **3** domains:

1] Behavioural Domain

2] Structural Domain

3] Physical Domain

- **Y Chart** or **Gajski-Kuhn Chart** is simply a pictorial representation of these three Domains in VLSI for better understanding the complete Design Flow.

- Below Diagram shows Y-Chart or Gajski-Kuhn Chart.

- When we start designing the VLSI circuit we have certain specifications and based on which we make certain **Algorithms** in Behavioural Domain.

- These Algorithms will then be sent to Structural Domain where we will have **system** assignments. Considering the assigned system, there will be a **chip floor plan** in Physical Domain using different floorplanning algorithms.

- In the **Finite state machine**, we will check how the chip floor plan will work according to the time. Timing assignment will be done w.r.t **registers** in Structural Domain.

- Then we will have **module placement** in the physical domain according to the timing assignment from the register.

- **Module Description** in Behavioral Domain will define how **Logic Gates** will work.

- Considering different current driven capabilities of different logic gates we place different logic blocks in **cell placement** of physical domain.

- Then we will define the **Boolean Equation** of logic blocks and implement it using **transistors**.

- Once we verify the complete circuit we will perform **masking** where we will provide physical links between logic blocks.




