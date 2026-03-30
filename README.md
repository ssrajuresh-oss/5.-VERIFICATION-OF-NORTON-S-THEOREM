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
<img width="1600" height="715" alt="image" src="https://github.com/user-attachments/assets/96859fb4-7d87-4a2a-923d-7a86cc51242b" />


**To measure RTh or RN**
<img width="1449" height="587" alt="image" src="https://github.com/user-attachments/assets/2bdfbcf5-1673-490e-90e0-21e2cc394d94" />



**To measure IN or Isc**
<img width="1474" height="461" alt="image" src="https://github.com/user-attachments/assets/ee7a0d67-ccd5-41aa-9c5a-250b26024ae8" />

 
**Thevenin’s equivalent circuit**
<img width="1600" height="626" alt="image" src="https://github.com/user-attachments/assets/bc7bd5cd-0759-4c87-b114-98809ddb2c0a" />


**Norton’s equivalent circuit**
<img width="1600" height="696" alt="image" src="https://github.com/user-attachments/assets/8d752f84-d5ac-45aa-9026-7c8736d0416d" />


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
<img width="1600" height="580" alt="image" src="https://github.com/user-attachments/assets/b1175b5d-d902-4006-b935-107bdcb26248" />

Vi (volts)	IL (amps)

**TABULAR COLUMN:2**

To measure RTh or RN

Vi (volts)	RTh (Ω)
<img width="1600" height="737" alt="image" src="https://github.com/user-attachments/assets/ea5eaf19-947d-45d3-bd34-78759b82797c" />


**TABULAR COLUMN:3**

To measure IN or Isc

Vi (volts)	IN (amps)
<img width="1600" height="776" alt="image" src="https://github.com/user-attachments/assets/e47a766e-9e3d-4025-a700-291099b8903e" />
	
**MODEL CALCULATION:**
<img width="1600" height="1280" alt="image" src="https://github.com/user-attachments/assets/1f405867-d214-4bf6-b007-f6f3e49c24b0" />

Practical value of IL (from tabulation 1) =2.3mA

**Verification of Norton’s theorem**
<img width="1600" height="1441" alt="image" src="https://github.com/user-attachments/assets/460686df-9931-4389-9a5b-7b28e09afc61" />

IL = IN * RN / ( RN+ RL ) = 2.43mA

Theoretical calculation of IL ,IN and RTh(RN) for the given circuit:
 
**MARK SPLITUP:**
<img width="1600" height="1114" alt="image" src="https://github.com/user-attachments/assets/7530498a-a124-4da2-a3f3-cbd4f0bae72c" />

**RESULT:**

Thus Thevenin’s and Norton’s theorem is verified practically and theoretically.
