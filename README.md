<h3 align= "center" > COLLEGE OF ENGINEERING </h3>
<h3 align= "center" > BS MECHATRONICS ENGINEERING </h3>
<h2 align= "center" > Control Systems Engineering LABORATORY 3 </h2>
<h1 align= "center" > Block Diagram Algebra </h1>

### Introduction

The purpose of this experiment is to employ MATLAB as a tool for simulating block diagram algebra, which is essential for analyzing and simplifying complex control systems. By utilizing MATLAB and Simulink, we aim to define, construct, reduce, and analyze block diagrams, ultimately visualizing their step responses and comparing the effects of different inputs. This experiment will enhance our understanding of block diagram manipulation and the practical application of control systems theory.

### Theory

**Block Diagrams**

Block diagrams are graphical representations that depict the components of a system or process and their interrelationships. Each component is represented by a block, while the connections between these components are illustrated with lines. In Control Systems Engineering, block diagrams serve as a crucial tool for visualizing the interconnections and functional relationships among various elements of a control system. This visualization aids in understanding, designing, and analyzing the behavior and performance of control systems.

**Block Diagram Algebra**

Block Diagram Algebra refers to the mathematical methods used to manipulate and simplify block diagrams. This algebra involves various operations such as addition, multiplication, and feedback manipulation to transform complex block diagrams into equivalent, simpler forms. By applying block diagram algebra, engineers can more easily analyze and understand the overall behavior of control systems. These operations are fundamental for reducing block diagrams to their simplest forms, enabling more straightforward analysis and design of control systems.

### Procedure

1. **Definition in MATLAB**: Begin by defining the given block diagrams in a MATLAB `.m` file. This involves specifying the transfer functions and system parameters.
   
2. **Construction in Simulink**: Construct the block diagrams in Simulink based on the definitions from the MATLAB file. This step requires creating a visual representation of the block diagrams using Simulink's graphical interface.

3. **Manual Reduction**: Manually reduce the block diagrams to their simplest forms using block diagram algebra. Document the steps and solutions in the README file of the repository.

4. **Construction of Reduced Diagrams**: Construct the reduced block diagrams in Simulink. This involves creating new diagrams that represent the simplified versions obtained from the manual reduction process.

5. **Simulation and Comparison**: Use Simulink to simulate and plot the step responses of both the original and reduced block diagrams. Additionally, apply a sinusoidal input source and compare the system responses to different inputs.

6. **Outputs**: Provide the following outputs as part of the experiment:
   - The transfer functions in the MATLAB `.m` file.
   - The block diagrams and step responses in the MATLAB `.slx` file.
   - A GitHub repository containing all relevant files for the laboratory activity, including the transfer functions from the block diagrams and the documented solutions in the README file.

By following this procedure, we will gain practical experience in using MATLAB and Simulink for control systems analysis and develop a deeper understanding of block diagram algebra and its applications.

### Results and Discussion

The following topics include the manual, computations, and the posted signal outputs coming from the Simulink and Matlab.

#### Number 1


![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/7598d093-4f7f-4858-9b63-e68ea98e1f6c)

Manual Computation:


![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/321173b4-ffe3-4b0c-8dc6-7ff9bf267bf1)\

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/31a4fb41-e79e-4947-9a46-61a28b6d0422)

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/479bdc40-a18c-4c0f-8b93-61c018eb17ce)


Simulink Step Response (not Reduced Functions):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/44728d77-c51f-4532-b5d7-477cb9acdfb8)


Simulink Step Response (Reduced Function):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/0b6a5a9f-7d14-4f02-8dc0-b9311a23d31f)

Simulink Sinusodial Response (not Reduced Functions):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/d10b0ae4-d238-4fe2-b007-b294f84c0026)

Simulink Sinusodial Response (Reduced Function):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/39a896d6-33bf-4371-9f7b-785f26a4a358)

#### Number 2


![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/4ccae787-fbc3-439a-890f-50940b26135c)


Manual Computation:


![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/385a7426-cb54-4ed5-be31-e4820454ee6b)\

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/af66ac75-c239-4250-93b0-354f1aa42ec3)\

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/dbc0f257-9982-4bc7-aa63-9f367de7122b)

Simulink Step Response (not Reduced Functions):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/688b2fe1-b675-4e73-b909-5dd2a94d2746)

Simulink Step Response (Reduced Function):
![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/cfb879e6-c7f9-46ab-90b7-ee5addd11dfa)

Simulink Sinusodial Response (not Reduced Functions):

![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/d3c8329f-58f0-4eeb-b952-8cf25b68337b)

Simulink Sinusodial Response (Reduced Function):
![image](https://github.com/leandawnleandawn/CSE_BlockDiagramAlgebra_MEXE_3201_Group12_2024/assets/83767299/afdaadbf-cbcc-4506-811f-d8f94427b56b)

### Conclusion

In conclusion, this experiment successfully demonstrated the use of MATLAB and Simulink as powerful tools for simulating and analyzing block diagram algebra. By defining block diagrams in MATLAB, constructing them in Simulink, and performing manual reductions, we were able to visualize and simplify complex control systems effectively. The comparison of step responses and sinusoidal inputs between original and reduced block diagrams provided valuable insights into the behavior and performance of these systems. This practical application reinforced our understanding of block diagram manipulation and its significance in Control Systems Engineering, highlighting the importance of these techniques in the design and analysis of efficient control systems.

### Proponents

Project Leader: Dianne Mae Tricia Ortega
Project Supervisor: Tristan Potestades
Project Quality Assurance: Emmanuel Gumapac
Project Programmer: Lyndon Allen Sales
