# Optimizing Capacitated Multi-Modal, Multi-Period, Multi-Vaccine Distribution Network with Perishability and Multi-Revaccination

## Introduction
The global vaccination supply chain has grown increasingly complex, especially after recent health crises. Efficient vaccine distribution is essential for timely immunization, reducing wastage, and managing constrained resources. This challenge becomes even more demanding when dealing with perishable vaccines, multiple transportation modes, regional demand fluctuations, and the requirement for revaccination due to time-sensitive doses or new disease variants.

This study presents a mixed-integer optimization model for a capacitated, multi-modal, multi-period, multi-vaccine distribution network. The model is tailored to address real-world challenges such as perishability and multi-revaccination strategies, incorporating critical aspects like capacity constraints, transportation and storage availability, multi-modal transportation, and vaccine perishability, while optimizing for cost-effectiveness and timely delivery over multiple periods.

## Problem Description
Our goal is to formulate a problem model that efficiently allocates different vaccine types across a distribution network, considering re-vaccination needs and the perishability of each batch within a defined time horizon. 

The problem components include:

- **Periods**: A set of discrete periods \(P\).
- **Manufacturers**: A set of vaccine manufacturers \(M\) with a manufacturing capacity \(M_Cap_i\).
- **Importing Nodes**: A set of import nodes (suppliers from other countries) \(S\) with an import capacity \(S_Cap_i\) in each period.

Thus, vaccines are transported from source nodes in the set \(M\) ∪ \(S\).

Additional components include:

- **Vaccine Types**: Multiple vaccine types, indexed by \(T\), available at any source node.
- **Demand Nodes**: A population requiring vaccines centered at demand nodes \(N\), with population \(D_j\) and demand \(D_{j,p}\) in each period. Variable demand based on revaccination needs for specific vaccine types is denoted as \(D_{var,j,t,p}\).
- **Storage Capacity**: Each demand node has access to refrigerators \(F\) with capacities \(Cap_{R,j,f}\), where each center can choose one or more refrigerators.
- **Mobile Refrigeration Units (MRUs)**: MRUs \(R\) are available across all modes of transportation, with each unit having a capacity \(P_{Cap,r}\).
- etc

## Contact
For any inquiries or feedback, please contact [Pritam P](mailto:pritampohankar112@gmail.com).
