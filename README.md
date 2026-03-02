# Computer Performance Benchmarking
---

## Project Overview
This project evaluates and compares the performance of four different computer systems using a combination of professional benchmarking freeware and custom-developed assembly language (ASM) code. The primary goal is to observe how various CPU architectures handle different workloads, ranging from low-load office tasks to high-load stress tests. For this project, I collaborated with Angela Ngu Xin Yi, Evelyn Ang, Tan Xin Tian, Teoh Xin Yee, and Toh Shee Thong on this project.

## Course Information
- **Course**: Computer Organization and Architecture (SECR1033)  
- **Section**: 2  
- **Institution**: Universiti Teknologi Malaysia (UTM)  
- **Lecturer**: Dr. Mohd Fo'ad bin Rohani  

## Benchmarking Tools
The following tools were utilized to measure system performance:

- **CPU-Z**: Extracted detailed hardware specifications, including clock speed, cache data, and motherboard information.  
- **Geekbench**: Conducted single-core and multi-core stress tests to evaluate processing power.  
- **Windows Task Manager**: Monitored real-time CPU and memory performance under varying system loads.  
- **MiniTool Partition Wizard Free 12.8**: Evaluated disk read/write performance across different transfer sizes.  
- **Assembly (ASM) Program**: A custom program developed in Visual Studio 2019 to solve a polynomial equation (`y = ax^3 + bx^2 + cx + d`) and measure execution time across multiple loop iterations.  

## Tested Hardware Specifications
Benchmarking was conducted on four Windows-based laptops:

| Feature | Computer A | Computer B | Computer C | Computer D |
| :--- | :--- | :--- | :--- | :--- |
| **Processor** | Intel Core i5-1235U | Intel Core i5-1035G1 | Intel Core i5-1135G7 | Intel Core i7-12650H |
| **Architecture** | Alder Lake | Ice Lake | Tiger Lake-U | Alder Lake |
| **Cores/Threads** | 10C / 12T | 4C / 8T | 4C / 8T | 10C / 16T |
| **RAM** | 8 GB DDR4 | 8 GB DDR4 | 8 GB DDR4 | 16 GB DDR4 |
| **L3 Cache** | 12 MB | 6 MB | 8 MB | 24 MB |

## Key Findings
- **Overall Performance**: **Computer D (Intel Core i7-12650H)** was the strongest overall due to its high core count, 16 threads, and 24 MB L3 cache, making it ideal for intensive multitasking and programming.  
- **Single-Core Strength**: **Computer A (Intel Core i5-1235U)** demonstrated the highest clock speed, winning 7 out of 16 Geekbench single-core tests, making it highly efficient for single-threaded tasks.  
- **Memory Efficiency**: Computer D's 16 GB RAM provided significantly higher memory bandwidth than the 8 GB single-channel setups of other systems.  
- **Disk Performance**: Computer D led in disk benchmarking thanks to PCIe 4.0 support, which doubles the bandwidth of PCIe 3.0 in older models.  
