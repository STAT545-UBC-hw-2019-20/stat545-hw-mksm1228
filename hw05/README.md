# **STAT545A Homework Assignment 05 README**

This final assignment was due on Oct 17, 2019 at 23:59. It currently contains the .rmd file, .png files, the .csv files for the Input and Output exercise, and this README.md file. Please [click here](https://stat545-ubc-hw-2019-20.github.io/stat545-hw-mksm1228/hw05/hw05-factor.html) for the html version of the homework assignment. 

The goals for this assignment were to:

- Write some data to file and load it back into R.
- Explain the value of the here::here package
- Improve a figure (or make one from scratch), using new knowledge, e.g., control the color scheme, use factor levels, smoother mechanics.
- Reorder a factor in a principled way based on the data and demonstrate the effect in arranged data and in figures.
- Implement visualization design principles.

There were 5 exercises in total and the tasks chosen for each exercise will be posted below:

### **Exercise 1: Explain the value of the here::here package**

-------------------------------------------------------------

In your own words, summarize the value of the here::here package in 250 words or fewer.

### **Exercise 2: Factor management**

------------------------------------------------------------

**Drop Oceania.** Filter the Gapminder data to remove observations associated with the continent of Oceania. Additionally, remove unused factor levels. Provide concrete information on the data before and after removing these rows and Oceania; address the number of rows and the levels of the affected factors.

**Reorder the levels of country or continent.** Use the forcats package to change the order of the factor levels, based on summarized information of one of the quantitative variables. Consider experimenting with a summary statistic beyond the most basic choice of the mean/median. Use the forcats package in the tidyverse for this, rather than the baseR function as.factor.

### **Exercise 3: File input/output (I/O)**

------------------------------------------------------------

- ```write_csv()/read_csv()``` (and/or TSV friends),
- ```saveRDS()/readRDS()```,
- ```dput()/dget()```.

You are expected to create something new, probably by filtering or grouped-summarization of your dataset (for e.g., Singer, Gapminder, or another dataset), export it to disk and then reload it back in using one of the packages above. You should use here::here() for reading in and writing out.

With the imported data, play around with factor levels and use factors to order your data with one of your factors (i.e. non-alphabetically). For the I/O method(s) you chose, comment on whether or not your newly created file survived the round trip of writing to file then reading back in.

### **Exercise 4: Visualization design**

------------------------------------------------------------

**Task:** Create a side-by-side plot and juxtapose your first attempt (show the original figure as-is) with a revised attempt after some time spent working on it and implementing principles of effective plotting principles. Comment and reflect on the differences.

### **Exercise 5: Writing figures to file**

------------------------------------------------------------

**Task:** Use ggsave() to explicitly save a plot to file. Include the exported plot as part of your repository and assignment.

Then, use ```![Alt text](/path/to/img.png)``` to load and embed that file into your report. You can play around with various options, such as:

- Arguments of ```ggsave()```, such as width, height, resolution or text scaling.
- Various graphics devices, e.g. a vector vs. raster format.
- Explicit provision of the plot object ```p``` via ```ggsave(..., plot = p)```. Show a situation in which this actually matters.