# QULBIT-Thesis-Project

QULBIT is the foundation of a new type of decision support system that deals with uncertainty using the formalisms of quantum mechanics. The main advantage of this framework is that it can capture human paradoxical and irrational decisions during the inference process, which can be very useful not only for cognitive systems, but also for decision-making systems that deal with human data. The quantum-like approach also enables the expression of a prediction using quantum interference effects. I will be working on this project to optimize and solve existing roadblocks with the current code with help of my supervisor Catarina Pinto Moreira.

Meeting Minutes 10/09/2021:

Discussion:

	- Plan of attack for the rest of the semester.
	
	- What needs to be done in order to finish.
	
	- Planned regular meetings for every Friday.
	
	- Shared resources for the thesis.
	
Tasks:

	- Create a GitHub repository and share it.
	
	- Research QLBN papers and familiarise with content again.
	
	- Dissect jupyter notebook and understand computations.
	
Reflection:

Meeting Minutes 17/09/2021:

Discussion:

	- GitHub repository set up and requirements.
	
	- Setting up of ReadME.md file.
	
	- Documenting meeting minutes in ReadME.md file.
	
	- Revise theory and mathematics of QULBIT notebook (JPM, Density Matrix/Operators, Superpositions, etc).
	
Tasks:

	- Calculate minimum and maximum interference of a Diabetes dataset.
	
	- Put through a linear solver.
	
	- Load shafir.trevsky dataset.
	
	- Do classical approach (Compute FJD, marginilisation).
	
	- Compute superposition, density and partial trace.
	
Reflection:


Meeting Minutes 08/10/2021:

Discussion:

Tasks:

	- Create a function that can 0 zero out the interferences.
	
	- Max diabetes network set to max of cosine = cos(0)
	
	- Min diabetes network set max of cosine = cos(theta)=1
	
	- Compare the two parameters.
	
	- Experiment 1:
	
		Set all interference terms to the maximum: cos( theta ) = 1
		
		Theta = 0
		
		Load the diabetes dataset
		
		Learn the BN of this dataset
		
		Compute the density matrix
		
		Compute the marginal for Pr( Diabetes = True )
		
	- Experiment 2:
	
		Set all interference terms to the maximum: cos( theta ) = 1
		
		Theta = 0
		
		Load the diabetes dataset
		
		Learn the BN of this dataset
		
		Compute the density matrix
		
		Compute the marginal for Pr( Diabetes = True )
		
		Exactly the same but with the interference corresponding to the minimum
		
		Cos ( theta ) = - 1
		
	- Check file_disc.csv for diabetes dataset.

	- Goal: QProb( Diabetes = t ) = [ prob_min , prob_max], QProb( Diabetes = t | BMI > 30 )
	
	- Try parallelize code to work.

Reflection: 
