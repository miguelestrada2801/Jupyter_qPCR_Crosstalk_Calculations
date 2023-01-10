# Jupyter_qPCR_Crosstalk_Calculations
qPCR data processing to analyze crosstalk percentage into another dye signal 


# When dealing with qPCR data and working with multiple targets to detect, there's a need to evaluate cross-talk percentage from one dye into the other. Primary reason for this is to evaluate at a systems levels the performance of positional filter emission/excitation range, deconvolution process, proper identification of the target among other items. Facilitating data processing and matching of target from position of target to qPCR output data saves time and allows for more freedom to tinker with different approaches for data analysis. In this project I am presenting a technique to automate processing delta fluorescent data from qPCR output and matching it with 96 or 384 well plate positional to calculate cross-talk percentages from pseudo targets into the target in reaction. The target which we will be dividing by is in single-plex format and the psuedo targets dRn are not present in the reaction.


# The files are located in the multiplex folder.Only thing to do is copied paths from data folder and path to plan and pasted on the notebook 
  
