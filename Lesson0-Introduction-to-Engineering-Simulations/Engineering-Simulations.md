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
  

### Example of FEA: Truss Element
Consider an elastic bar subjected to axial forces only

![Image of a horizontal bar](https://user-images.githubusercontent.com/74782784/212895031-3f93c82a-db5d-4d74-86ae-01c78259c16e.png)

In accordance with Hooke's law, the displacement of the bar is related to the force applied by the equation
### [K]{U} = {F}

Where
```
**[K]** = Stiffness or Property Matrix
**{U}** = Nodal displacement Vector i.e. Behavior
**{F}** = Nodal force vector i.e. Action
```




![Screenshot 2023-01-17 144327](https://user-images.githubusercontent.com/74782784/212897145-33aff8bc-a44d-4feb-9d8a-f42fd1b221dc.png)

If there are more than 1 element in the system, the element equations are assembled to form a _global system_. Afterwards, **boundary conditions** are incoporated and the system of equations solved for Unknown nodal displacements. 

