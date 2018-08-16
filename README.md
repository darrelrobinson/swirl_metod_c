# swirl_metod_c


This course is intended to give students of Methods C at the Department of Government, Uppsala University a brief introduction to the R programming language while simultaneously providing a resource for studying the course content. 

The lessons are a small collection of existing swirl lessons (see www.swirlstats.com) that have been packaged and sorted to follow the methods course material.  

To install the course, in R:
```
if(require(swirl) == FALSE) install.packages("swirl")
library(swirl)
install_course()
```
Then use the navigator window to select the ''Metod_C.swc'' file.

Alternatively, copy and paste the following two lines directly into the console:

```
if(require(swirl) == FALSE) install.packages("swirl")
install_course_github("darrelrobinson", "swirl_metod_c", multi = TRUE)
```

And the course will install without you having to download a file and use the navigator.  

To begin using the course, sStart swirl and follow the prompts:
```
swirl()
```

