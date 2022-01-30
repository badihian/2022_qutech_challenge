# Entangled-Guys
IQuHack-2022 Qutech-QEC.

# Title: Preserving Entanglement Using Repetition Quantum Error Code

Members: Neel Kanth Kundu (HKUST), Parth Hemant Darekar (USC) , Neema Badihian (USC)

Aim: Preserve EPR correlations when one of the qubit is stored in a faulty quantum memory

Solution: Since Starmon-5 has only 5 qubits, we use 3 Qubit QECC to encode one of the qubit of the EPR pair and study the EPR correlations at the end.

Code: Run QEC_EPR jupyter notebook


Quantum Circuit:
![image](https://user-images.githubusercontent.com/62837473/151700864-42be56e3-1249-4483-a402-771412424aa2.png)


Results:
1) No Error in Memory:
 QASM Simulator Result: ![image](https://user-images.githubusercontent.com/62837473/151700913-3d7d0fd9-bf03-43a4-ae02-0c76e5d62393.png)
 QuTech Starmon-5 HW Result:
 ![image](https://user-images.githubusercontent.com/62837473/151700953-82ed4ca4-dba6-4cb5-ab75-6000e45e60bb.png)

2) Pauli-X Error in Memory: ![image](https://user-images.githubusercontent.com/62837473/151701337-ba7ff2f5-380a-4e55-b69d-e585533cbc1b.png)
 QASM Simulator Result: ![image](https://user-images.githubusercontent.com/62837473/151701027-53fd01ef-a272-4e66-86f2-0620fb3504e3.png)
 QuTech Starmon-5 HW Result: ![image](https://user-images.githubusercontent.com/62837473/151701263-0556b516-9deb-4361-ad88-8bdf3400fb7b.png)

 
3) Pauli-Y Error: ![image](https://user-images.githubusercontent.com/62837473/151701140-5235ff6a-e460-48a4-b3c7-524cfc43c822.png)
 QASM Simulator Result: ![image](https://user-images.githubusercontent.com/62837473/151701864-65f0071b-aa63-4c70-af53-413f6da77f08.png)
 QuTech Starmon-5 Result: ![image](https://user-images.githubusercontent.com/62837473/151701628-00670db3-ac95-45c0-9a64-322327ea29f7.png)

 
4) Pauli-Z Error: ![image](https://user-images.githubusercontent.com/62837473/151701418-a62d4a98-c357-4bd1-b8cf-ad55ca0edfdd.png)
   QASM Simulator Result: ![image](https://user-images.githubusercontent.com/62837473/151701792-9f6b6685-69fd-4ca1-bbae-9ea636af6b8e.png)
   QuTech Starmon-5 Result: ![image](https://user-images.githubusercontent.com/62837473/151701491-bfdb6133-ec8a-450f-adc8-dea132adcbbd.png)
   
Conclusion: Repetition Code is able to preserve EPR correlations in a faulty memory
Future Work: Implement Repetition QEC for both the EPR qubits that requires total 6 Physical Qubits

References:
[1] https://quantumcomputinguk.org/tutorials/quantum-error-correction-bit-flip-code-in-qiskit
[2] https://learn.qiskit.org/course/quantum-hardware/introduction-to-quantum-error-correction-via-the-repetition-code

# Personal Experience
1) Got to learn hand on Quantum Comuting using real Starmon-5 hardware
2) Networking experience where we made connections with other quantum professionals
3) Interactions with recruiters helped to know about the job opportunities and type of projects in different Quantum computing companies
4) Had fun coming up with a specific problem and then coding it on real hardware


