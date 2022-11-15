# papaja demonstration

Workshop materials to demonstrate papaja ([Aust & Barth, 2022](https://github.com/crsh/papaja)) package for creating reproducible manuscripts. 

Click Code > Download ZIP to save all files. 

## Workshop slides

In the top-level of the directory is the slides for the workshop. You can open the slides using the papaja_slides.html file. This should open in your web browser as a .html file. 

If you want to explore how I made the slides, you can look at the quarto presentation file. It should knit providing all these files are in the same working directory including Screenshots as a folder.

## Mock example

To demonstrate the capability of papaja, I made a mock example to provide some context and show how each component works. You can view the results of this in the .pdf file for the knitted manuscript. This is what you can end up with. 

Check out the .Rmd file if you want to play around with the example. It should knit if all these files are in the same working directory, including the Figures folder. 

- r-references.bib is updated every time you knit the document via a papaja helper function

- references.bib is a BibTeX file I exported from Zotero for the references I used 

- apa7.csl is a CSL file to specify if you want to knit using APA style referencing

- vancouver.csl is a CSL file to specify if you want to knit using Vancouver style referencing
 
