README – Grover’s Algorithm on a 4-Qubit Dataset
TÖL031M – Quantum Computing and Quantum Cryptography
University of Iceland – Fall 2025

1. Dependencies
The project was developed and tested with:
- Python 3.10+
- Qiskit 1.2.4
- qiskit-aer
- matplotlib
- Jupyter Lab

To install dependencies:
    pip install qiskit qiskit-aer matplotlib


2. Files Included
- TOL031M_Final_Project_4_Qubits.ipynb   (main notebook)
- people_16.csv                          (dataset of 16 entries)
- Final_Report_Grover_4Qubits.pdf        (final report)
- README.txt                             (this file)


3. Setup Instructions
1. Make sure Python and all dependencies are installed.
2. Place the notebook and people_16.csv in the same directory.
3. Start Jupyter Lab:
       jupyter lab
4. Open and run the notebook from top to bottom with:
       Run → Run All Cells

No external internet or additional datasets are required.


4. How to Reproduce the Results
1. The notebook loads the dataset people_16.csv (16 rows).
2. A classical linear search is executed:
   - Finds target index
   - Prints comparisons and runtime
3. A 4-qubit Grover circuit is constructed:
   - Oracle using MCXGate
   - 4-qubit diffuser
   - 3 Grover iterations (optimal for N = 16)
4. Two simulations are performed:
   - Ideal quantum simulation using AerSimulator
   - Noisy simulation using depolarizing noise
5. Outputs generated:
   - 4-qubit circuit diagram
   - Ideal histogram of measurement results
   - Noisy histogram
   - Classical vs quantum timing comparison

Running the notebook exactly as provided will reproduce all images and results.


5. Authors
Iftejar Miah Viki
Gísli Már Guðmundsson
