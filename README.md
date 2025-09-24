# ROM Hands-On Workshop - Working Repo

(Please note - This is working repository and is not customer ready, if there is ROM Workshop request from one of your accounts, please reach out to us. This is not tested on MATLAB online yet).  

# AI Workshop for Reduced Order Modeling 
## Agenda

High-fidelity models, such as those based on FEA (Finite Element Analysis), CFD (Computational Fluid Dynamics), and CAE (Computer-Aided Engineering) models can take hours or even days to simulate. These full-order high-fidelity models, while being useful for detailed component design, are too slow and therefore impractical for system-level simulation, control design, and Hardware-in-the-Loop testing. For example, a finite element analysis model that is useful for detailed component design will be too slow to include in system-level simulations for verifying your control system or to perform system analyses that require many simulation runs. A high-fidelity model for analyzing NOx emissions will be too slow to run in real time in your embedded system. Does this mean you have to start from scratch to create faster approximations of your high-fidelity models? This is where reduced-order modeling (ROM) comes to the rescue. ROM is a set of computational techniques that helps you reuse your high-fidelity models to create faster-running, lower-fidelity approximations. 

In today’s hands-on workshop, you will learn how to create AI-based reduced order models using the new Simulink add-on for Reduced Order Modeling to replace high-fidelity models. 

This interactive hands-on session will include the following: 

* Familiarizing yourself with the Reduced Order Modeler app with an introductory example of creating ROM of a battery system, starting with performing design of experiments, generating input-output data, training AI models, and integrating the trained AI models into Simulink.  
(Internal reference only) - here is a recording with the walkthrough of the introductory example using the ROM app: [Recording](https://mathworks-my.sharepoint.com/:v:/p/kmahadev/EfX4G6BDi0tFr2-fYji7BWoBo1wT4APxbJ6voQGEmm_x0Q?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=3klXw5)
* (second exercise) - Explore how to import existing time-domain data generated from your high-fidelity CAE, FEA, or CFD models, into the ROM app to create AI-based reduced order models.
    * **For AeroDef accounts** - Reuse this example - [Reduced Order Model of a Jet Engine Turbine Blade from Data](https://www.mathworks.com/matlabcentral/mlc-downloads/downloads/0cee96ac-b9e3-4632-9809-a7fd7d78d2b0/1741373202/previews/doc/examples/html/turbineblade_data_example.html)
    * **For Auto accounts** - (In progress) Reuse data from system identification example - [Neural State-Space Model of SI Engine Torque Dynamics](https://www.mathworks.com/help/ident/ug/nonlinear-state-space-model-of-si-engine-torque-dynamics.html)
    * **For IA&M accounts** - (In Progress) Reuse data from [Deep Learning-Based Reduced Order Models for Electric Motors](https://www.mathworks.com/videos/deep-learning-based-reduced-order-models-for-electric-motors-1715775848025.html)
* **Optional Modules:**  
* ( option 1 for potential third exercise) - Explore how to create an AI-based surrogate model (static reduced order model (ROM)) of an electric vehicle thermal management system. (this would highlight the provisions to transform output signals logged from the high-fidelity model to compute the final quantity of interest, in the example that would be the total energy consumed for a particular drive cycle). Can reuse this example - [Reduced Order Model of a BEV Thermal Management System](https://www.mathworks.com/matlabcentral/mlc-downloads/downloads/0cee96ac-b9e3-4632-9809-a7fd7d78d2b0/1741373202/previews/doc/examples/html/BEV_example.html)
* (option 2 for potential third exercise) - Explore how to create an AI-based ROM and use the trained ROM for designing a controller and for performing Hardware-in-the-Lopp (HIL) testing. (This can be a way to highlight the use cases of bringing in a trained AI model into Simulink for downstream use cases such as control design, HIL testing, virtual sensor modeling (would require highlighting our code geneation capabilities)) Can resue files from this repo - [Reduced Order Model of a Jet Engine Turbine Blade](https://insidelabs-git.mathworks.com/AE-Content/demos/jet-engine-blade-reduced-order-model)

### Ramp-Up ###

This is a 2-hour, interactive session.

Potential Workshop Timings (2hr):

15m - Set up and Intro  
45m - Exercise 1 - ROM App and workflow with Battery System  
10m - Potential workflows and optional workflow  
10m - Exercise 2 - Importing data from 3P tools for ROM  
15m - Exercise 3 - Static ROM or ROM for HIL Testing  
15m - Exercise 4 - Deployment, code optimization, testing AI models  
10m - Conclusion and next steps (Training/Deep Engagement and Consulting)  

MathWorks instructors and teaching assistants (TAs) will be available throughout the session to guide you. If the event is being held onsite, 


References to other AI workshops - https://insidelabs-git.mathworks.com/AE-Content/workshops/ai-workshops-reimagined-collection

## Relevant Industries
* AeroDef 
* Automotive
* IA&M
* CESSI

## Relevant Products
* MATLAB
* Simulink Add-On for Reduced Order Modeling
* Statistics and Machine Learning Toolbox
* Deep Learning Toolbox
* System Identification Toolbox
* Simulink
* Simulink Coder
* Embedded Coder
* MATLAB Coder Interface for Deep Learning Libraries
Copyright 2022, The MathWorks, Inc.

## Contact
* Kishen Mahadevan (Product Marketing)
* Mahaveer Satra (Application Engineering)
* Shyam Keshavmurthy (Application Engineering)
* Oscar Molina Ortiz (Application Engineering)
* Terri Xiao (Application Engineering)