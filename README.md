# Quantum Computing Mentorship Program Task

> Here are descriptions for the task:
>
> In the Bin Packing Problem (BPP), given a collection of items, the goal is to efficiently pack the items into the minimum number of bins, where each item has an associated weight, and the bins have a maximum weight. The problem can be found in different industries. For example, the supply chain management industry requires loading multiple packages onto a truck, plane, or vessel. In this task, you will solve the BPP using quantum computing.
>
1. From Integer Linear Programming (ILP) to Quadratic Unconstrained Binary Optimization (QUBO).
  
  - Define the ILP formulation of the BPP. You can use Docplex or similar frameworks to do it.
  - Create a function to transform the ILP model into a QUBO
  - Test your function with specific instances (size small, medium, and big) 
2. Create a Brute Force solver for the QUBO problem and solve the specific instances. 
  
3. To solve the QUBO, use quantum annealing simulators. You can use the Dwave Ocean Framework. Here is an example.

4. Use a Quantum Variational approach to solve the QUBO. 
  - Create multiple Ansantz for tests. 
  - Build a function with input being the QUBO and Ansantz. Using a hybrid approach solved the QUBO. 
  
5. Use QAOA to solve the QUBO. Create from scratch a QAOA function. 
  
6. Compare and analyze the results. 
  What is the difference between QAOA, Quantum Annealing, and Quantum Variational approaches with different Ansatz? 
  How do the results compare with the brute force approach? 


