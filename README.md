# 1.Design-implement-and-simulation-of-Inverting-noninverting-and-Differential-amplifier

**AIM:**
To design , implement and simulate  an inverting, non- inverting and differential amplifiers

**APPARATUS  and SOFTWARE REQUIRED:**
S.No	Name of the Apparatus	Range	Quantity
1.	Function Generator	3 MHz	1
2.	DSO	30 MHz	1
3.	Dual RPS	(0 – 30) V	1
4.	Op-Amp	µA741	1
5.	Bread Board		1
6.	Resistors	1K,10K	2
7.	Connecting wires and probes	As required	
8.  LT SPICE software

**THEORY:**
Op-amp in open-loop configuration has a very few application because of its enormous open-loop gain. Controlled gain can be can be achieved by taking a part of output signal to the input with the help of feedback. This is called as Closed- Loop Configuration. The three basic types of closed-loop amplifier configuration are:
1.	Inverting amplifier.
2.	Non-inverting amplifier.
3.	Differential amplifier.
The entire configuration can be operated with either AC or DC input.

**INVERTING AMPLIFIER:**
This is the most widely used op-amp. Here, the output voltage Vo is feedback to the inverting input terminal through the Rf – R1 network. The negative sign in gain indicates the phase shift of 180ο.
The circuit closed-loop voltage gain is Avcl= -RF / R1

**NON - INVERTING AMPLIFIER:**
If signal is applied to the non-inverting input terminal of op-amp without inverting the input signal such a circuit is called non-inverting amplifier. Here the output is feedback to the inverting input terminal. The phase shift of input signal does not occur in non-inverting terminal.
The circuit closed-loop voltage gain is ACL = 1 + ( RF / R1)

**DIFFERENTIAL AMPLIFIER**
A circuit that amplifies that amplifies the difference between two input signals is called as differential amplifier. It is useful in instrumentation amplifier. If the two input signals are the same, the output should be zero. Differential amplifier with a single op-amp has the exact gain of an inverting amplifier and it is given as
𝐴	= 	𝑉𝑜/(V2-V1) = −𝑅𝑓/R1

**DESIGN:**

**Inverting amplifier:**
    Gain is     A = -Rf/R1
        Take  A = 10
        Rf =10 R1
        Choose R1 = 1kΩ, Rf=10kΩ
        
**Non inverting amplifier:**
    Gain is    A = 1+ Rf/R1
      Take A = 2
      Rf = R1
      Choose Rf = 10kΩ, R1=10kΩ
      
**Differential amplifier**
  Gain is 𝐴=	𝑉𝑜/(𝑉1− V2)= − 𝑅𝑓/𝑅1
Take  A = 10
 Rf =10 R1
Choose R1 = 1kΩ, Rf=10kΩ

**PROCEDURE:**
**Inverting and Non-inverting amplifier:**
1.	Select R1 as a constant value and choose a value of Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Apply the constant amplitude input voltage to the circuit.
4.	Measure the output voltage amplitude for different value of V1 from DSO.
5.	Calculate the practical Voltage for different value of V1& compare it with theoretical output.
6.	Practical gain & theoretical voltage should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
   
** Differential amplifier:**
1.	Select the value of R1, R2, R3 & Rf such that R1=R2 and R3=Rf.
2.	Connect the circuit as per as the circuit diagram.
3.	Provide constant input voltage Vin1 to Non-inverting terminal of op-amp through R1 & constant input voltage Vin2 to inverting terminal of op-amp through R2.
4.	Measure the output voltage using DSO.
5.	Calculate the theoretical Vo and compare it with practical Vo.
6.	Practical output & theoretical calculation should be approximately equal.
7.	Plot the graph of the input wave versus output wave for any one practical case.
 
**PIN DIAGRAM:**
<img width="1537" height="799" alt="image" src="https://github.com/user-attachments/assets/caae294b-2f31-44fe-aa18-02a647c869b3" />

**INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1585" height="863" alt="image" src="https://github.com/user-attachments/assets/85da3a8e-3811-464f-a7c2-d471fac54c6d" />


  **MODEL GRAPH:**
<img width="1528" height="1080" alt="image" src="https://github.com/user-attachments/assets/5aa96272-1df0-436e-a862-9361601d753d" />


  **TABULATION:**
 <img width="1519" height="597" alt="image" src="https://github.com/user-attachments/assets/324b43e7-1255-45ca-be3c-7e0a84ddffae" />


**MODEL CALCULATION:**

**NON INVERTING AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1516" height="902" alt="image" src="https://github.com/user-attachments/assets/b7fa7f75-6c82-4b63-a19c-7abd3891085d" />


  **MODEL GRAPH:**
<img width="1529" height="1037" alt="image" src="https://github.com/user-attachments/assets/c5d719da-17d2-439d-a9a2-95f4cad64c29" />


  **TABULATION:**
<img width="1461" height="736" alt="image" src="https://github.com/user-attachments/assets/83555a18-b16c-4518-9717-5ef7c8b0e55e" />

  **DIFFERENTIAL AMPLIFIER:**
  **CIRCUIT DIAGRAM**
<img width="1599" height="1198" alt="image" src="https://github.com/user-attachments/assets/18d28268-a521-461c-bded-f93697cef849" />


  **MODEL GRAPH:**
<img width="1500" height="1007" alt="image" src="https://github.com/user-attachments/assets/44a9d9b0-29cb-4027-96d7-2fe509a0e1d5" />


  **TABULATION:**
  <img width="1428" height="779" alt="image" src="https://github.com/user-attachments/assets/3c2adf81-5d13-4330-a78f-70e80837a6dd" />

  <img width="1131" height="1600" alt="image" src="https://github.com/user-attachments/assets/fc958616-c5f4-4ff0-afa3-2eb90deecbf0" />

**LT-SPICE Tool:PROCEDURE:**
•	Double click on LT-Spice icon.
•	New schematic window open.
•	Pick and paste the required component from the library and draw the circuit diagram .
•	Complete the connection.
•	Save the file by giving file name.
•	Click on the run option ->click advanced open ->select Ac analysis->enter the amplitude time delay stop time value.
•	Click on the run option ->simulation window opens->place the probe ->output graph is obtained.
 
  **LT SPICE**
  **CIRCUIT and Waveform**
<img width="1600" height="817" alt="image" src="https://github.com/user-attachments/assets/fe6afa05-af87-4e84-98dc-5d8704c4f0c4" />

   <img width="1600" height="827" alt="image" src="https://github.com/user-attachments/assets/e7344719-7d8b-4e70-beba-656d79c1c25a" />



   <img width="1600" height="808" alt="image" src="https://github.com/user-attachments/assets/ce91e76b-b5c1-40b7-a192-6c3baf640d05" />


**RESULT:**
Thus the Inverting, Non-Inverting and Differential Amplifiers are designed and simulated performance was successfully tested using op-amp IC 741 and LT SPICE.
 






