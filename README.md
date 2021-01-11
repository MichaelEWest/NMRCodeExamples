### NMRCodeExamples ###
These are a few examples of my simulations and coding experience from graduate school.  They were all written to be compared to experimental results.  The detailed ackground theory was learned from scratch, and the ability to implement it in code form was also learned from scratch.  There are three parts.

# 1PulseAcquireExample: 
A simple demonstration of an NMR spectrum generator.  It is quantum mechanical in nature, and is described with matrix manipulation/linear algebra. The relative intensities of the transitions change as a function of temperature (T), and being able to predict these changes with this model has proven useful for furthering scientific discovery.

I reccommend re-running the simulation at varying temperatures from 0.001 Kelvin to 1 Kelvin, demonstrating how the relative intensities respond to it changing.
Additionally, one can manipulate the "tip angle" of the experiment, where the relative intensities also respond.

# 2QuadrupolarEchoExample:
A more involved demonstration of an NMR spectrum generator.  Like the first example, it is based in matrix manipulation/linear algebra to describe a quantum mechanical system.  It was created to help model and explain signal distortions that are experienced experimentally.  It is quite a bit more abstract, so it employs a graphical representation that I devised and implemented to help demonstrate the evolution of the complex elements of the ematrix.

Feel free to manipulate the "manipulatable" variables to see how it affects the evolvolution of the system.

# 3IterativeFileGeneration:
This is an example of how I iteratively generated input files for a specialized simulation software package (called SIMPSON).  It iteratively creates all possible configurations of 3 Cd-113 sites and 4 Te-125 nuclear sites within a "chunk" of a CdTe crystal. In the process, it also calculates all nuclear-nuclear couplings for each configuration, and writes it into a .txt file for later automated submission to SIMPSON. 

This generates 24.7 MB of data in the form of 14,520 .txt files in the specified folder.  (It's relatively quick!)
