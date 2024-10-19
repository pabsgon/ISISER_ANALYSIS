SYS REQUIREMENTS
1. Jupyter Notes installed. 
2. The path to this root folder (where these files are) needs to be saved in a ENV VAR called ISISER_ANALYSIS. Steps:
  a. Press Win + R 
  b. Type sysdm.cpl + INTRO
  c. Tab Advanced > Click on Env. Vars.
  d. Press NEW > Type ISISER_ANALYSIS and the path next to it.
  e. Press ok in all windows.
3. The file ISISER_ANALYSIS Jupyter Notebook.lnk in this folder points to Jupyter Notebook exe file. The target of this shortcut file should be PATH_TO\anaconda3\python.exe PATH_TO\anaconda3\cwp.py PATH_TO\anaconda3 CPATH_TO\anaconda3\python.exe PATH_TO\anaconda3\Scripts\jupyter-notebook-script.py "%ISISER_ANALYSIS%/"
E.g.: 
"C:\Users\pablo\anaconda3\python.exe C:\Users\pablo\anaconda3\cwp.py C:\Users\pablo\anaconda3 C:\Users\pablo\anaconda3\python.exe C:\Users\pablo\anaconda3\Scripts\jupyter-notebook-script.py "%ISISER_ANALYSIS%/"

HOW TO
Once the system has been set up (see SYS REQS):
1. Click on Win + R
2. Type "Jupy". The shortcut "ISISER_ANALYSIS Jupyter Notebook.lnk" should become available.
3. Click on it. Wait until the Jupyter Notes home pops up in browser, showing all the notebooks.

DESCRIPTION
ANALYSIS_ISISER contains Jupyter Notes files that implemented several analysis. 
1. FINAL_IRT_ANALYSIS. Item Response Theory Analysis required for obtaining a metric of 1) the difficulty of the questions and the ability of the students, aiming to select the experimental questions and balance the experimental groups, respectively.
2. FINAL_DISSENT&ALIGNMENT_ANALYSIS
3. FINAL_ALIGNMENT_ANALYSIS
4. FINAL_MiniTests_Comparisons
