This is the Git repository we used for our project.

To access the files we used and edited, navigate through:

Class Content --> final assignment --> file of your choice.

Our part of the project consists of three files, added to the original "final project" folder. Each file is dedicated to a specific analysis model.

"PRIM.ipynb" was used to conduct scenario discovery using PRIM. 
"Sensitivity Analysis.ipynb" was used to conduct sensitivity analysis using Sobol.
"Robustness.ipynb" was used for conduct robustness calculations using multi-scenario MORDM. 
Each file can be ran independently, since we decided to run the dike model for each one. All three files are annotated with markdown cells for clarity.

Edits were made to "problem_formulation.py", after line 275. We chose problem formulation 3, but decided to implement an if statement to better fit our case. 
Four csv files were generated as part of our analysis:
For PRIM: experiments.csv and outcomes.csv
For MORDM: cat_comparison.csv and comparison_df.csv
