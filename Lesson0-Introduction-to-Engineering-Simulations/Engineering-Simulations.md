# **A basic overview of Engineering Simulations**

In Engineering, problems are solved through any of the following methods:
- Analytical Method
- Numerical Method
- Experimental Method

Analytical methods are quite popular and provide 100% accurate solution. However, this approach is only applicable to **simple geometry**.
Experimental methods on the other hand tend to be time consuming and extremely costly. Numerical methods are thus suitably used for relatively _complex geometry_ with reduced cost and time requirements. 


## The Finite Element Method
Finite Element Method (FEM)/ Finite Element Analysis (FEA) is a numerical method for solving systems of differential equations arising in engineering modelling. It is useful for problems with _complicated geometry, loadings, and material properties_. 
In Finite Element Analysis, there is interest in:
- Understanding the behaviors of complex objects. 
- Predicting performance and behavior of the design; for safety margin and to identify weaknesses. 
- Identify optimal design

## Procedure for Finite Element Analysis
1. **Preprocessing**
  - Discretization and elemnent selection
  - Selection of approximate function
  - Generation of nodal coordinates
  - Definition of physical constraints (_boundary conditions_) and loadings. 
2. **Processing**
  - Generation of element matrix
  - Assemble to global stiffness matrix
  - Impose boundary conditions
  - Nodal displacements
3. **Post Processing**
  - Results intepretation
  - Plotting
  
  


