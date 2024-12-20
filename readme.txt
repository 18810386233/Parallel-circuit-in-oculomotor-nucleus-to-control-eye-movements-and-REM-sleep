
## Requirements

The scripts were tested on window. Before running, a established python environment should be prepared as follow:
--Python = 3.8
--Numpy
--pandas
--statsmodels
--matplotlib
--Networkx
--scipy
--jupyter

The version of package was not assigned, so that you can adjust the version of packages according to conda configuration in your computer.
*We provide a 'environment.yml' file that specifies all the necessary packages for setting up the environment. To install the environment, follow these steps:

       Run the command:
	-conda env create -f environment.yml

       Activate the newly created environment:
	-conda activate my_environment

       You can use the 'conda env list' to check the installed package.

*Alternatively, if you prefer to manually install the required packages, you can use:
	`pip install` or 'conda install'.


##Scripts

The compressed zip file includes the source data, the execution scripts, and the expected output utilized in this work.

Here is the description of the code:
-Fig1. Transition_activity.ipynb 
        Code used for analyzing the fiber photometry data.
        The expected outputs were demonstarte within the jupyter code.

-Fig3. Probability of REM stimulation.ipynb
        Code used for analyzing the polygraphic recorded data and evaluating the sleep architecture after optogenetic stimulation.
        The expected outputs were demonstarte within the jupyter code.

-Fig3. Sleep architecture during opticalStimulation.ipynb
        Code used for ploting  the probability of diferent vigliance states when optogenetic stimulation were performed during REM sleep.
        The expected outputs were demonstarte within the jupyter code.

-Fig4. Eye movements analysis.ipynb
        Code used for analyzing the endoscopic data to define the eye movements related neurons
        The expected outputs were demonstarte within the jupyter code.

-Fig4. Network_analysis1.ipynb and Fig4. Network_analysis2.ipynb
        Code used for performing network analysis of eye movements neurons and sleep active neurons
        The expected outputs were demonstarte within the jupyter code.

*The 'tool' folder contains custom-written scripts used in the '.ipynb' files.

##Implementation

After completing the environment setup, you can run the data in the corresponding folder by executing the '.ipynb' in that folder and visualize the expected output.
or
you can open the  '.ipynb' file in jupyter notebook to track the historical running record.

With a download speed of 2 MB/s, setting up the environment is expected to take approximately 10 minutes.

If you have any further questions, please feel free to contact me.