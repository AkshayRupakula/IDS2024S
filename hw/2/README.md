# Homework 2:
1. **Pdf attached in IDS2024S/hw/2**
   * 1950s: FORTRAN (1957), LISP (1958), Algol 58 (1958)  
   * 1960s: BASIC (1964)  
   * 1970s: C (1972)  
   * 1980s: C++ (1983), Python (1989)  
   * 1990s: Java (1995)  
   * 2000s: C# (2000)  
   * 1990s (revised standard): Fortran 90 (1991)  
 
2. **ENIAC** = Electronic Numerical Integrator and Computer  
3. Everything is represented by integers in computers because computers use binary (base-2) number system, where all data is encoded using only two states: **0 and 1**. Integers are easily represented and manipulated in binary, making them a fundamental building block for encoding more complex data types and instructions efficiently.  
4. The fastest part of computer memory is the **Cache Memory**.  
5. The slowest storage device typically integrated with computers is the Hard **Disk Drive (HDD)**.
6. The smallest unit of information in computer science is the **bit**.
7. a. The closest programming language to machine code is **Assembly language**.  
   b. Assembly language needs to be translated into machine code to be executed by the computer, but this process is not usually referred to as "interpretation." Instead, it is assembled or compiled by an assembler. The assembler converts assembly language instructions into equivalent machine code so that the CPU they comprehend and execute it.  
8. a. The oldest high-level programming language that is still in active daily use is **FORTRAN (FORmula TRANslation)**.  
   b. **FORTRAN** was created in 1957, which makes it approximately 7 decades old.
9. a. A second-generation programming language refers to **Assembly language**.
   b. The language-generation classification for the mentioned languages is as follows:
      * FORTRAN: First-generation high-level programming language.
      * C: Third-generation programming language (3GL).
      * C++: Third-generation programming language (3GL), with object-oriented programming capabilities.
      * MATLAB: Fourth-generation programming language (4GL), focused on numerical computing.
      * Python: Third-generation programming language (3GL), used for its readability and support for multiple programming paradigms.
      * R: Third-generation programming language (3GL), used for statistical computing and graphics.
10. * **C**: Created in the **1970s**, specifically around **1972**.
    * **C++**: Created in the **1980s**, its first commercial implementation was available around **1985**.
    * **MATLAB**: Released in the **1980s**, specifically **1984**.
    * **Python**: Created in the late **1980s** and officially released to the public in **1991**
11. An ancestor programming language of C is **B**.
12. An ancestor programming language of C++ is **C**.
13. MATHLAB = **ForTran** and Python = **ABC Programming language**
14. The fastest part of the memory hierarchy in modern computers is the **CPU Registers**.
15. The smallest memory unit in the memory hierarchy of modern computers is the **bit**.
16. Accessing data in CPU registers can be roughly **5 to 100 times faster** than accessing data in RAM. The access times for CPU registers is 0.5 to 1 nanoseconds whereas, access times for RAM is 5 to 100 nanoseconds for DRAM.
17. Access to RAM is **100 to 1000 times faster** than accessing data on SSDs in modern computers. RAM access times are in the order of nanoseconds, while SSD access times are typically in the order of microseconds.
18. Access to RAM in modern computers is significantly faster than accessing data on HDD hard drives,which is about **10,000 to 100,000 times faster**. RAM access times are in the order of nanoseconds, while HDD access times can be in the order of milliseconds.
19. Transistors are the main component of the microchips used in computers. Computers operate on a binary system, which uses only two digits: 0 and 1. In a computer microchip, transistors act as switches, letting current through to represent the binary digit 1, or 0 when the switch is off.
20. The reasons we cannot we add more transistors to computers to make them faster are:
* Heat Dissipation and Cooling Challenge  
* Increased Power Consumption  
* Diminished Performace over Time  
* Physical and Quantum Limits  
* Higher Costs  
* Architectural Complexity  
21. The three tasks accomplished in the CPU Cycle are: **Fetch, Decode and, Execute**.  
22. Yes, a powerful computer with more CPU cycles can be slower than a computer with fewer CPU cycles in certain scenarios. Raw clock speed and the number of cycles per second are not the sole determinants of computational speed; architectural efficiency, software nature, memory system performance, cooling efficiency, and instruction set optimizations also play critical roles.  
23. In modern computers, the primary bottleneck of speed has shifted more towards memory access rather than CPU clocks. This shift is due to several reasons:
      * CPU speeds have increased dramatically, memory speeds have not kept pace.
      * Even though modern RAM technologies (like DDR5) are faster than their predecessors, the latency, or the time it takes for memory to start delivering data after a request, has      not improved at the same rate as high-performance CPUs.
      * CPUs use caches to mitigate memory speed issues. However, when the required data is not found in the cache, the CPU must fetch data from the slower main memory, causing       delays.
      * Increasing the clock speed of CPUs leads to exponential increases in power consumption and heat production, which are practical limits to how fast CPUs can run.
24. * Moore's Law predicts the exponential increase in transistor count on integrated circuits over time.
    * Dennard Scaling describes how devices could be made smaller without increasing power density, facilitating increases in performance and energy efficiency.
    * MOSFET Scaling focuses on the technical process of shrinking transistor sizes to achieve higher density and potentially better performance, which is essential for maintaining the pace of Moore's Law but has faced physical limitations similar to the breakdown of Dennard Scaling.
25. * 64 grains for the last (64th) square.
    * 2,080 grains in total to fill all the chessboard squares incrementally as described.
    * Approximately 0.297 pounds of rice for this task, given that a pound of rice is roughly 7,000 grains.  
26. * You would need 9,223,372,036,854,775,808 grains for the last (64th) square.
    * The total grains required for the entire chessboard would be 18,446,744,073,709,551,615 grains.
    * This translates to approximately 2,635,249,153,387,079 pounds of rice for the entire task.
    * Given the current annual world production of rice is roughly 2,000,000,000,000 pounds, it would take approximately 1,317.62 years to produce the required amount of rice grains to place on this chessboard in the described fashion.
27. The three fundamental components of a Turing-complete language are:
* Conditional branching: (e.g., if-else statements).
* Variables and state manipulation: (e.g., using variables).
* Loops or recursion: The capability to perform repetitive tasks either through loops (for, while) or recursive function calls, allowing the language to execute an operation multiple times with different parameters or until a condition is met.
28. 
* Exponential Behavior: the rate of growth increases over time. On a linear scale plot, this results in a curve that starts slowly and then rises sharply, becoming steeper and steeper as the value on the x-axis increases. If you plot an exponential function on a log-linear scale (logarithmic y-axis and linear x-axis), it appears as a straight line, indicating constant growth on a logarithmic scale.

* Power-Law Behavior: grows at a rate that decreases over time relative to its size. On a linear scale plot, power-law behavior is represented by a curve that starts steep and gradually flattens out as the value on the x-axis increases. When plotted on a log-log scale (both axes are logarithmic), a power-law function appears as a straight line, indicating a proportional relationship between the logarithm of the variables.
