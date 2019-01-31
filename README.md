# Working with both Proprietary and Open Source Software (3089)
In 2018, Ernestynne delivered one of the top-rated presentations at the SAS® Users New Zealand conference. The presentation talked about a future of working with both open-source and proprietary software. It covered the benefits and provided some examples of combining both. The future is now here. This 90-minute Hands-On Workshop drills down into examples that were briefly touched on during that presentation. Attendees get a taste of working with R in SAS® Enterprise Miner™ and some general best practice tips. There is an introduction to the Scripting Wrapper for Analytics Transfer (SWAT) package, which enables you to interface with SAS® Viya® in open-source languages like R. This presentation briefly covers avoiding some traps that you can fall into when working with the SWAT package. The techniques learned here can be extended to enable you to work with Python in SAS®. The emphasis of this Hands-On Workshop is how to combine SAS with open-source tools, rather than teaching attendees how to code in R.

### To get in touch
Ernestynne Walsh
+64272812147
ernestynne@nicholsonconsulting.co.nz

### File Structure of `walsh/how/`
| Subdirectory  | Filename        | Description
| ------------- | -------------   |--------------
| .             | intro-pres.pptx | slide deck to introduce the course content
| .             | LICENSE.md      | licensing info for the data, code base and other content
| .             | README.md       | markdown file explaining installation requirements
|./data         |                 | dataset to be converted into a *.sas7bdat file using autoexec.sas
|./exercises    |                 | 
|./results      |                 | 
|./solutions    |                 | 
|./startup      |                 | 

### Requirements
**Images**
EDU_EM_FS94M4 and EDU_Viya33Analytics
They have software such as RStudio, Access to SAS Viya and Enterprise Miner with R installed on the server

**R packages**
The following packages and their dependencies are required
```
install.packages(c("rpart","r-swat"))
```

**Other**
Internet access would be ideal so that attendees can look at the online data dictionary
