Project Layout:

# Folder setup: - 
  ## For active projects (may or may not have a git
    00-Data           : Data files, can have subfolders: 01-Simulated and 02-Empirical
    01-Documentation  : Papers/ ReadMe files/ Diagrams/ figures/ maths neccessary to understand the project
                        01-ForBiologist     : Non technical details and biological motivation, justification and big picture stuff.
                        02-ForUser          : Non-bioinformatician who just want to use the package/code for analyses
                        03-ForDeveloper     : Bioinformatician looking to modify the codes 
                        04-ForTheoretician  : For theoretical biologist who wish to understand the mathematics and background
    02-Script         : Scripts written (for python, perl, bash, R) 
    03-TempFile       : Folder for files that are usually TAGNH and can be deleted 
    04-Run            : Active directory for Hipergator runs
    05-Figure         : Figures generated

  ## For finished projects for distribution (Should have a Git reposistory)
    00-Data           : Sample data to use for running
    01-Tutorial       : Rmd files for how to guides on 01-Installation, 02-Analysis
    02-Code           : Based on platform and language:C/C++
                        data  : has data
                        lib   : has libraries
                        src   : has source code
                        info  : has readme info
    03-Paper          : Overleaf document/ latex document for paper stuff. -can be subdivided into 01-Figures, 02-Tables etc


###### Note: I don't keep a Git repository for active projects- because more often than not, they fail (...sigh!), and I don't want to clean up my Git often. It is a personal preference, and if you want to back up your project you, should definitely have one and also...you know....for version control. I usually add a time stamp to my script output files so they don't get overwritten and I can delete the previous runs. Again, not the ideal way to do this but it works for me. If you are working in a big lab where multiple people are working on the same project, I would highly recommend Git repository for every project.



