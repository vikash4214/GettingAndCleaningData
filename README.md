@@ -33,4 +33,9 @@ Steps to reproduce this project
  1. Open the R script `run_analysis.r` using a text editor.
  2. Change the parameter of the `setwd` function call to the working directory/folder (i.e., the folder where these the R script file is saved).
  3. Run the R script `run_analysis.r`. It calls the R Markdown file, `run_analysis.Rmd`, which contains the bulk of the code.
 -4. Copy the *Codebook* section from the resulting `run_analysis.md` file to a new file, `codebook.md`. This step is not automated and must be manually done using a text editor.
 +
 +
 +Outputs produced
 +----------------
 +* Tidy dataset file `DatasetHumanActivityRecognitionUsingSmartphones.txt` (tab-delimited text)
 +* Codebook file `codebook.md` (Markdown)
