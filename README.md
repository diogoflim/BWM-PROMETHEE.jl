# BWM-PROMETHEE-ASSIGNMENT.jl

This repo presents a BWM-PROMETHEE II function implemented in Julia.

JuMP and GLPK were used to apply the BWM linear optimization model. 

The procedure was applied to analyze shipping companies in a bidding process for different routes. The generated net flows were then used as input for an General Assignment model.

An example can be executed in the file: main.jl while the functions are available in src/Methods.jl


**Collaborators:**
- Diogo Ferreira de Lima Silva
- Laís Sant'anna Fonseca

**Some references for the MCDA procedures:**

- PROMETHEE Methods
    - - Brans, Jean-Pierre, and Yves De Smet. "PROMETHEE methods." Multiple criteria decision analysis: state of the art surveys (2016): 187-219.
    - - Behzadian, Majid, Reza Baradaran Kazemzadeh, Amir Albadvi, and Mohammad Aghdasi. "PROMETHEE: A comprehensive literature review on methodologies and applications." European journal of Operational research 200, no. 1 (2010): 198-215.

- BWM
    - - Rezaei, Jafar. "Best-worst multi-criteria decision-making method: Some properties and a linear model." Omega 64 (2016): 126-130.
    - - Rezaei, Jafar. "Best-worst multi-criteria decision-making method." Omega 53 (2015): 49-57.
