Al-Ahliyya Amman University: Intro to IT Portfolio
​Student: طارق محمد خميس احمد (Tariq Mohammad Khamis Ahmad)
Major: Networks and Cybersecurity
ID: 202511528
Course: Introduction to Information Technology 
​Project 1: PC Hardware Selection & System Architecture
​Objective: Gather information and justify component selections for a high-performance computer build. 
​Hardware Specifications & Justifications
​CPU: AMD Ryzen 5 9600X (6 Cores, 12 Threads)
• ​This is a highly efficient, latest-generation Zen 5 CPU.
• ​It offers excellent single-core speed vital for high-FPS gaming and provides maximum performance for its price point.
​GPU: NVIDIA GeForce RTX 5070 (12GB GDDR7)
• ​The GPU is the most critical component for gaming.
• ​It uses the latest Blackwell architecture and is perfectly matched with the R5 9600X to prevent bottlenecking.
​Motherboard: Gigabyte B850 Eagle WIFI6E
• ​A robust chipset providing DDR5 support and built-in Wi-Fi 6E.
• ​Includes a PCIe Gen 5 slot to accommodate high-end modern GPUs.
​RAM: Crucial Pro 32GB (2x16GB) DDR5-6000
• ​32GB is the modern standard for serious gaming and multitasking.
• ​The 6000 MT/s speed is the current "sweet spot" for AMD Ryzen CPUs.
​Storage: Lexar NM790 2TB NVMe SSD
• ​Mandatory for fast boot times and rapid loading of the OS and games.
• ​2TB provides ample space for a large modern game library.
​PSU: Seasonic Core V2 GX-650 (80+ Gold)
• ​Provides reliable and efficient power delivery with a fully modular design to improve airflow.
​Case & Cooling:
• ​Lian Li Lancool 207: A high-airflow case crucial for keeping modern components cool.
• ​Thermalright Phantom Spirit 120SE: A high-value air cooler ensuring the CPU boosts to its highest speeds.
​Security Considerations for this Build
​As a Cybersecurity student, I selected this hardware to support modern security protocols:
• ​TPM 2.0 (fTPM): The Ryzen 9600X supports firmware-based TPM, required for Windows 11 and BitLocker encryption.
• ​Secure Boot: Enabled via the B850 BIOS to ensure only trusted software loads during boot, protecting against rootkits.
• ​WPA3 Encryption: The motherboard’s Wi-Fi 6E allows for the latest WPA3 security standard to protect against network attacks.
​Project 2: Logic Design & Currency Conversion Algorithm
​Objective: Design a logical flow to convert Jordanian Dinars (JD) into USD, EUR, and SAR. 
​Logic Components
• ​Rates: 1 JD = 1.41 Dollar, 1.31 Euro, and 5.29 Saudi Riyal.
• ​Flowchart Structure: 
• ​Start
• ​Input: The user enters the amount in JD.
• ​Process: Calculate conversions (Dollar = JD * 1.41; Euro = JD * 1.31; Riyal = JD * 5.29).
• ​Output: Print the converted results.
• ​End
​Pseudocode
• ​START
• ​DECLARE amountJD, valDollar, valEuro, valRiyal AS FLOAT
• ​INPUT amountJD
• ​SET valDollar = amountJD * 1.41
• ​SET valEuro = amountJD * 1.31
• ​SET valRiyal = amountJD * 5.29
• ​PRINT results and END
​Project 3: Technical Implementation (Java)
​Objective: Implement the Project 2 conversion logic into a functional Java program. 
​Implementation Details
• ​Scanner Class: Used to capture user input from the console.
• ​Data Types: Used double for precision since currency values contain decimals.
• ​Calculations: Implemented the exact conversion rates defined in the project scope.
​


Code Snippet
Scanner input = new Scanner(System.in);
double jdAmount = input.nextDouble();
double usdAmount = jdAmount * 1.41;
double eurAmount = jdAmount * 1.31;
double sarAmount = jdAmount * 5.29;
input.close();



Portfolio Summary
• ​Project 1 Cost: 1,395 USD (Approximately 989.06 Jordanian Dinar).
• ​Note: Some hardware parts may not be available locally in Jordan.
