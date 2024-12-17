# HOMO-LUMO-gap-prediction (ML)


![homo_lumo_gap01](https://github.com/user-attachments/assets/86538aed-b417-4125-9a4c-54e1447e34c5)
(https://www.chem.ucla.edu/~harding/IGOC/H/homo_lumo_gap.html)



<Building a Model to Predict HOMO-LUMO Gap from Molecular SMILES Representations>

* Training Data: HOMO-LUMO gap and oscillator strength values for 100,000 molecules
  - Filename: PubchemQC_Random_HOMO-LUMO_gap_and_OS.csv     
  - First Column: HOMO-LUMO gap (unit: eV)    
  - Second Column: Oscillator strength (no unit), closely related to the absorption coefficient.    
  - Third Column: SMILES    

* Test Data: SMILES_for_test.txt

* Method
  - 1: Using smiles
  - 2: Using descriptors 
