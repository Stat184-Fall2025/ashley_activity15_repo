# Project Plan

## Goal(s)
- Create a fully reproducible quarto document (QMD) rendered as a PDF
- Have clear and consice descriptions and interpretations, good formatted code chunks, labeled figures and tables, alt text, and properly wrangled data.
- Ensure the code in the document can run on anyone's computer using only public data and accessible packages that are clearly explained.

## Needs
- Correct and well formatted YAML including title, author, date, format, etc.
- Organized section headings
- Body text that describes each visualization, the context, and results
- Clean code chunks in the code appendix, not in the body
- fig-cap and fig-alt for all figures
- Code comments that help organize and describe code
- Code comment stating the coding style guide
- Complete QMD file able to be rendered as a PDF file
  
- Wrangling and analysis for:
  - Armed Forces Data (Air Force Commissioned Officers)
  - Baby Names time-series visualization
  - Box Problem Volume plot and optimization calculation
  
## Steps
1. Revise YAML header with correct formatting
2. Check that section headings from previous assignment are clear and align with instructions
3. Check that all descriptions and writing are clear and correct
4. Insert code chunks with #| echo: false in the body and #| fig-cap: and #| fig-alt: for plots
5. Make sure all plots / tables / figures have the correct and unique labels
6. Add code comment for chosen style guide (Tidyverse Style Guide) and adjust code accordingly
7. Ensure all code (data wrangling, functions, visualizations) are correct and run without error for all 3 sections
8. Ensure code appendix shows all code, correctly commented and labeled
9. Render PDF and check formatting

# Repository Plan

## Goal(s)
- Use github to practice and show proper version control
- Practice using issues, branches, commits, and pull requests
- Keep the repository well organized, readable, and fully reproducable
- Include all required files (QMD, PDF, README, PLAN)

## Needs
- Public github repository for Activity #15
- At least 2 issues with labels and a detailed description
- dev (development) branch separate from main to work on revisions
- Multiple commits with meaningful messages to work on revisions
- At least one pull request to merge revisions from dev into main
- README file with project purpose, data sources, repo organization, and contact info
- PLAN file (this file)
- Final QMD and rendered PDF files
  
## Steps
1. Create public github repository titled "ashley_activity15_repo"
2. Create dev branch for all working edits and revisions
3. Create at least 2 issues based on plan
4. Add labels to the appropriate issues
5. On the dev branch, create README.md and PLAN.md
6. On the dev branch, add initial QMD file from Activity #14
7. Commit changes of adding files
8. Revise the QMD with multiple meaningful commits, and reference issues
9. Write commit with format "If applied, this commit will..."
10. Once QMD is complete, open a pull request and merge into main
11. Render final PDF and add to repository
12. Close any remaining issues
