How to obtain tidy data with "run_analysis.R" in R
Run R as Administrator.
Already installed "tidyr" and "dplyr" packages.
Set up your designated directory.
    setwd("/SampleDirectory")
Execute "run_analysis.R" with its absolute path
    source("absolutepath/run_analysis.R")
View tidy data
    tidydata <- read.table("tidydata.txt",header = TRUE)
	View(tidydata)
