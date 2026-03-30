# 5.VERIFICATION-OF-NORTON-S-THEOREM

**AIM:**

To verify Norton’s theorem practically and theoretically for the given DC circuit.

**APPARATUS REQUIRED:**

1.	Regulated Power supply ( RPS)	(0-30 V)	1
2.	Voltmeter	(0-30 V) MC	1
3.	Ammeter	( 0 - 10 mA) MC	1
4.	Resistors	470 Ω 560 Ω 1 K Ω	2 1 1
5.	Bread board	---	1
6.	Multimeter	---	1

**THEORY:**

**NORTON’S THEOREM:**

Norton’s theorem states that, ‘a linear two-terminal circuit can be replaced by an equivalent circuit consisting of a current source, IN (=Isc) in parallel with a resistor RN (= RTh), where IN (=Isc) is the short-circuit current through the load terminals and RN is the equivalent resistance at the load terminals when the independent sources are turned off.Norton’s Current, IN or Isc:
It is the short-circuit current through the load terminals. i.e., IN = Isc

Norton’s Resistance, RN:It is the look-back resistance across the load terminals when all the sources are replaced by their internal resistances. An ideal voltage source is replaced by short- circuiting as its internal resistance is zero. An ideal current source is replaced by open- circuiting as its internal resistance is infinity.
 
**CIRCUIT DIAGRAM: VERIFICATION OF NORTON’S THEOREM**

**To measure IL**
<img width="1600" height="715" alt="image" src="https://github.com/user-attachments/assets/286f0431-3774-4d90-a251-7bbd39791c82" />


**To measure RTh or RN**
<img width="1449" height="587" alt="image" src="https://github.com/user-attachments/assets/130b064f-01a2-48bc-b30e-83462b9f505e" />



**To measure IN or Isc**
<img width="1474" height="461" alt="image" src="https://github.com/user-attachments/assets/f25bb864-4d82-4836-afa9-9a82e50cd273" />

 
**Thevenin’s equivalent circuit**
<img width="1600" height="626" alt="image" src="https://github.com/user-attachments/assets/6f0ef1dc-a70d-4659-b7bb-98c9a7ff2a1d" />


**Norton’s equivalent circuit**
<img width="1600" height="696" alt="image" src="https://github.com/user-attachments/assets/5f7c2f7a-fb13-48fe-bef9-492d3042ed29" />


**PROCEDURE:**

1.	Make the connections as per the Circuit Diagram:1

2.	Vary the RPS and set an input voltage of 10V.

3.	Note down the voltmeter reading (Vi) and ammeter reading (IL) in Tabular Column 1.

4.	Switch off the supply and make connections for Circuit Diagram 2.

5.	Measure the Thevenin’s resistance RTh= Norton’s resistance RN .

6.	Switch off the supply and make connections for Circuit Diagram:3.

7.	Set an input voltage of 10V in the RPS and note down the voltmeter readings Vi and VTh(=Voc) in Tabular Column:3

8.	Switch off the supply and make connections for Circuit Diagram 4.

9.	Set an input voltage of 10V in the RPS and note down the voltmeter reading Vi and Ammeter reading IN (= Isc) in Tabular Column 4.

10.	Draw the Thevenin’s equivalent circuit and Nortons’s equivalent circuit as shown in circuit diagrams 5 & 6 respectively.

11.	Calculate the IL value using the formula

   	Thevenin’s Theorem IL = VTh/ ( RTh+ R L)

   	Norton’s Theorem IL = IN * RN / ( RN + RL )

12.	Theoretically verify the Norton’s theorem.

**TABULAR COLUMN: 1**
To measure I L
<img width="1600" height="580" alt="image" src="https://github.com/user-attachments/assets/df197efa-d12b-471f-bef7-d3ba160555eb" />

Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN

Vi (volts)	RTh (Ω)
<img width="1600" height="737" alt="image" src="https://github.com/user-attachments/assets/c7206d6e-f2d0-44c5-90c6-9664e931707f" />


**TABULAR COLUMN:3**

To measure IN or Isc
<img width="1474" height="461" alt="image" src="https://github.com/user-attachments/assets/e9e1cb49-458a-434b-91fc-800da885fdb9" />

Vi (volts)	IN (amps)
	
**MODEL CALCULATION:**

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**
<img width="1600" height="1280" alt="image" src="https://github.com/user-attachments/assets/3583a24e-3a37-43ad-9d5e-0d5a0d5c1db0" />

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 <img width="1600" height="1441" alt="image" src="https://github.com/user-attachments/assets/925487e1-51ba-4f64-9878-746bd1b38578" />

**MARK SPLITUP:**
<img width="1600" height="1114" alt="image" src="https://github.com/user-attachments/assets/54aa70a1-aedc-4305-9655-ebaf7cf6e30e" />


**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
