# Mathematical Modeling and Design of a Reinforced Concrete Beam according to Eurocode 2

**SoftUni – Math Concepts for Developers**  
Final Project

## Project Description

This project implements the complete design process of a simply supported reinforced concrete rectangular beam according to Eurocode 2 (EN 1992-1-1) and the Bulgarian National Annex (BDS EN 1992-1-1).

The notebook covers:

- Static analysis of a simply supported beam with uniformly distributed load
- Demonstration of the differential relationship $\frac{dM}{dx} = V$ using numerical differentiation
- Flexural design (singly reinforced section)
- Shear design (with θ_min = 30° according to the Bulgarian NA)
- Deflection control using the span-to-depth ratio method
- Parametric study on the influence of beam height
- Clear summary of all results

## Scope and Limitations

- Only **singly reinforced** sections are considered (`K ≤ K'`). Cases requiring compression reinforcement are out of scope.
- The static scheme is limited to a simply supported beam with UDL.
- Torsion is not included.

## How to Run

1. Open `RC_Beam_Design_EC2.ipynb` in Jupyter Notebook / JupyterLab / PyCharm.
2. Run all cells in order.
3. Modify the input data section to explore different geometries, materials or loads.


## References

- EN 1992-1-1:2004 – Eurocode 2: Design of concrete structures
- БДС EN 1992-1-1:2005/NA – National Annex (Bulgaria)
- Original Mathcad calculation (see `/reference` folder)
