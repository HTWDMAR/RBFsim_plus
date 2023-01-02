# RBFsim<sup>+</sup>

## RBFsim<sup>+</sup> - what is it?

RBFsim<sup>+</sup> is an enhanced version of RBFsim, where it contains additional realistic scenarios for an aquifer, e.g., line source or a lake in the domain (see figure below). Also, it provides novel methods in AEM to compute the filtrate portions from a circular lake and river to a RBF pumping well.

<img src="https://github.com/HTWDMAR/RBFsim_plus/blob/main/Manual/RBFsim_plus.png" width="600" height="400">

## Steps for using code 

1.	Make sure that you have Python installed in your system.
2.	All the relevant libraries i.e., MATPLOTLIB, PANDAS, NUMPY, SCIPY and CMASHER should be called in Python.
3.	Select the interpreter as Python.
4.	Run the app from terminal by executing the app from command; ‘’Python app.py’’. 
5.	Once the App is executed it provides user with 6 option to select from Figure 1.
6.	Once the selection is made the user has to provide the input for relevant chosen option. 
7.	Option 6 can be overlooked by commenting the app.py line 147 – 151 and the inputs can be made directly at the excel input file for each functionality; Aquifer Data, Well(s) Data and Lake Source Data, where line source data has to provided directly in the script. 
8.	Once the particular function is executed, the output graphical and data files can be accessed from each functionality folder Figure 2. 

<img src="https://github.com/HTWDMAR/RBFsim_plus/blob/main/Manual/Howto-fig1.png" width="600" height="400">

<img src="https://github.com/HTWDMAR/RBFsim_plus/blob/main/Manual/Howto-fig2.png" width="600" height="400">


## Output from RBFsim<sup>+</sup>

The RBFsim<sup>+</sup> code when successfully executed will provide data files (csv) for head isolines and streamfunction. But more importantant code will result in several graphics outputs - few below:

<img src="https://github.com/HTWDMAR/RBFsim_plus/blob/main/Manual/Out-RBFsimp1.png" width="900" height="400">

<img src="https://github.com/HTWDMAR/RBFsim_plus/blob/main/Manual/Out-RBFsimp2.png" width="900" height="400">

## License and Authors
The codes in this site are CC BY 4.0 licensed. The license wording can be found [here](https://creativecommons.org/licenses/by/4.0/).
Basically, for using code from here- the original authors should be credited.


Following authors are credited for this version [![DOI](https://zenodo.org/badge/576731061.svg)](https://zenodo.org/badge/latestdoi/576731061)
of the code (names not in any order):

1. **Ghiman Dilshad** - Main code developer
2. **Dr Prabhas K Yadav** - Conceptualization and basic code development
3. **Prof. Dr. T. Grischek** - Supervisory support on contents
4. **Prof. Dr Andreas Hartmann** - Supervisory support on contents





## References

**MSc. Thesis: Dilshad, G. (2022)**


“Development of an analytic element method (AEM) based computational interface to evaluate the effect of inhomogeneities in the riverbank filtration systems”.
TU Dresden, Dresden. Supervisors: Dr. P. K. Yadav, Prof. T. Grischek and Prof. A. Hartmann

## Funding

This project was partially funded by BMBF MEWAC-FEMAR Project (grant no. 02WME1612A-C, Prof. T. Grischek)
