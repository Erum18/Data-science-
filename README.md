
+---
+ title: "HelloWorld"
+ author: "Ivanbate"
+ data: "16/11/2020"
+ output: "html_document
+---
+
+ ```{r setup, include=FALSE}
+ knitr ::opts_chunk$set(echo=TRUE)  
+```  
+
+ ## R Markdown
+
+ # This is a Markdown file
+
+ - **my file**
+ - *Hello*
+ - # Hello World
+ - ## Hello World
+ - ### Hello World
+ - ~~ups~~ 
+
+ This is a R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS word documents. For more details on using R Markdown see  <http://rmarkdown.rstudio.com> 
+
+ when you click the **knit** button a document will be generate that includes both content as well as the output of any embedded R code chunks within the document. You can embed a R code chunk like this:
+
+ ```{r cars}
+ summary(cars)
+ ```
+
+ ## Including Plots
+
+ You can also embed plots, for example: 
+
+ ``` {r pressure, echo=FALSE}
+ plot(pressure)
+ ```
+
+ Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
