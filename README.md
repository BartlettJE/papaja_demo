# papaja demonstration

Workshop materials to demonstrate papaja ([Aust & Barth, 2022](https://github.com/crsh/papaja)) package for creating reproducible manuscripts. 

Click Code > Download ZIP to save all files. 

## Workshop slides

In the top-level of the directory are the slides for the workshop. You can render the slides with the quarto presentation file. It should knit providing all these files are in the same working directory including Screenshots as a folder.

You were supposed to be able to open the slides using the papaja_slides.html file and it appear in your web browser, but it looks like it loses the formatting. So, I have also saved the rendered slides as a PDF, so you can see them in all their glory. 

## Mock example

To demonstrate the capability of papaja, I made a mock example to provide some context and show how each component works. You can view the results of this in the .pdf file for the knitted manuscript. This is what you can end up with. 

Check out the .Rmd file if you want to play around with the example. It should knit if all these files are in the same working directory, including the Figures folder. 

- r-references.bib is updated every time you knit the document via a papaja helper function

- references.bib is a BibTeX file I exported from Zotero for the references I used 

- apa7.csl is a CSL file to specify if you want to knit using APA style referencing

- vancouver.csl is a CSL file to specify if you want to knit using Vancouver style referencing
 
 ----
 
 <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
