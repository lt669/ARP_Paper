Notes for Gavin:

All files and folders are on Google Drive however I've been using github to save and file share both the latex document and the matlab sripts so feel free to grab them from there. If any changes need making this is where ill push them to as I will not have access to my work Google Drive anymore:

Latex Document: https://github.com/lt669/ARP_Paper.git
MATLAB: https://github.com/lt669/ARP_MATLAB.git

Google Drive:
	ARP: Collated Data
		- ARP_Paper: Latex Document
		- ARP_MATLAB: Analysis and Plotting Scripts

%==========----------
% ARP_Paper: LaTeX file structure
%==========----------
- ARP_Paper: Files required to compile current latex document
	- Main document:
		ARP_Project.tex
	- Other files:
		This file is used to compile the entire latex document. The rest of the .tex files for writing can be found in the [tex] folder. Images are in the [images] folder.
- Hash Thesis: tex file with images used for Hash' thesis
- Results: Excel files used by matlab to import data
	- Hash_Results: Raw data from Hash' test in excel
	- Results: Raw data from new test in excel

%==========----------
% NOTES
%==========----------

	 -Notes
	 	- Alot of the literature review regarding MMAs was taken from Hash' Thesis
	 	- Ambisonic microphone section heaevly paraphrased
	 - Left to do
	 	- Introduction (sorry I just didnt have time to get round to this)
	 	- A more conclusive summary
	 	- Cut out dribble to make an acceptable Journal size
	 - Questions
		 - Do we want to provide a list of encoded angles for the mic arrays as Hash did?
		 - Should Mirek/Hyunkook authors?


%==========----------
% ARP_MATLAB
%==========----------

NOTE: All of the scripts writen to anaylse the data were written to share variables, therefore there are some scripts that need to be run before others for them to work. For this, some 'master scripts' have been writen. This will be explained in the file structure below:

- [folder] Results Decode
	- [folder] plots [scripts for plotting data]
		- plot_spatAtt_All.m <--- This is a master script that can be used to plot graphs of spatial attribute data
		- plot_timbralAtt_All.m <--- This is a master script that can be used to plot graphs of timbral attribute data
		- [folder] sa: contains scripts used for plotting spatial attributes
		- [folder] ta: contains scripts used for plotting timbral attributes
	- [folder] stats [scripts for calculating stats]
- [folder] Graphs: Screen shots of graphs used for the paper
	- sa (Spatial Attribute graphs)
	- ta (Timbral Attribute graphs)
