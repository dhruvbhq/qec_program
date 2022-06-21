# qec_program
This is my solution to the ~20 lines programming task for QIntern 2022. See the file submission_qiskit.ipynb. This short example implements Shor's 9 qubit error correcting code along with error decoding and correction circuit in Qiskit. The fidelity of ideal input state is calculated with the state obtained after encoding and decoding suject to different discrete errors.

The circuit implemented is the one in the figure and it uses the encoding qubits themselves to decode and correct the 1-qubit error, without extra ancillas or classically-controlled gates.

![image](https://user-images.githubusercontent.com/61590679/174850939-b01ec282-c927-4e70-80e4-1b18658f4d91.png)
