# Elastic Structural Analysis Tool (ESAT)

## Overview
The **Elastic Structural Analysis Tool (ESAT)** is a flexible software package developed in Python and MATLAB. Elastic structural analysis is done directly using the stiffness method. ESAT, from user-provided input parameters related to geometry, such as node coordinates and element connectivity, and loading conditions, such as nodal forces, boundary conditions, carries out detailed elastic analysis and produces detailed output results.

Key Features
Input Flexibility: With ESAT, you may indicate the geometric structure with which the static situation is to be considered.
Direct Stiffness Method: To form the global stiffness matrices, the direct stiffness method is used.
Equilibrium Equations: Systems of equilibrium equations are solved to determine displacements and internal forces by using the ESAT application.
- **Comparison with STAAD Pro**: The results calculated by the software can be directly compared with those obtained from commercial software like STAAD Pro in order to ascertain their accuracy and consistency.
- **Educational and Research Use**: ESAT functions as an educational tool to analyze structural principles, as well as a research tool for new algorithms.
## Usage
1. **Input Data**: The user inputs the following geometric data: coordinates of nodes, connectivity information about the elements, and the loading information: nodal forces, boundary conditions, etc.
2. **Run**: Input the Python or MATLAB script for ESAT.
3. **Report Analysis**: Study displacement vectors, element forces, and reactions.
4. **Verification**: Compare the results obtained from ESAT with those exported through STAAD Pro or other well-known softwares.

## Contributions and Suggestions
Your contributions to ESAT are welcome! Try creating a pull request or reporting issues. Your feedback improves this tool's usability and reliability.
