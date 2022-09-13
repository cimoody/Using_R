# Using_R
Notes on how to use R (b/c I need the refresher and reminders)

## Basic commands
`getwd()` returns the working directory


`rm(list = ls())` clears everything from the environment


`setwd("PATH")` sets the working directory to `PATH`


## Plotting with data `tt`
Breaking down the command `plot(tt$Date_stamp,tt$Data_mm, type="l", xlab='', ylab='(mm)', main='Rainfall at Mukdahan, Thailand')`
     
`tt` is the data

`tt$` calls the column named after the `$`

`type="l"` plots the data with lines

`xlab/ylab` is the x/y label

`main` is the main title of the plot
