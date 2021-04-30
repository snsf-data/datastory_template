# SNSF data story template

This repository contains the R template that is used to create the an SNSF 
data story that has the same format as the data stories published on the
SNSF Data Portal (data.snf.ch). 

The effective stories and visualizations are to be written in the RMarkdown 
files `en.Rmd`, `de.Rmd`, and `fr.Rmd`. The file `master.R` is used to knit 
these language-specific story files and to generate a file with metadata that 
is required for every story. The three language files can be knitted directly, 
but only running the code in `master.R` generates the eventually needed format 
of the files that is required for a publication as a data story. 

## Contact

For questions, feel free to contact Julius Mattern at julius.mattern@snf.ch.

## License

MIT © Swiss National Science Foundation