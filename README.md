# classroom_analysis
Data-driven teaching

This holds some analysis I've done as a teacher to make the best decisions for my students. Data is simulated/obfuscated to maintain student privacy.

## Class_projects.ipynb:
This Jupyter notebook contains some exploratory data analysis I did to determine if the format that students chose for a project affected their grade in a significant way. While grading, I had the impression that students who chose one format were consistently scoring less than students who chose another format. To determine if it was necessary to curve their grades in a way to account for this, I ran permutation tests to see if there was in fact a significant difference in the grades based on format choice. There was not.

## Public_version_GradeTracker.ipynb
This notebook was made to read in a spreadsheet exported from my gradebook and analyze the scores to automatically detect and flag students who might need an intervention because they: are trending downwards compared to previous tests, scored much worse than they normally do, or scored much worse than the class average.
This notebook may be used with the Sample_scoresheet.csv as input.
This notebook was written in Google Colab, but everything after the upload cell was not displaying on GitHub, so I turned it into a Jupyter notebook. Lines required to turn it back into a Google Colab notebook that can upload .csv files are there, commented out.
