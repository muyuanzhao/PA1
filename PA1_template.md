---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document: 
    keep_md: true
---

This project makes use of data from a personal activity monitoring device.
This device collects data at 5 minute intervals through out the day. The data
consists of two months of data from an anonymous individual collected during
the months of October and November, 2012 and include the number of steps
taken in 5 minute intervals each day

## Loading and preprocessing the data
The dataset was downloaded from this [Activity monitoring data][1] link
The variables included in this dataset are:

. steps: Number of steps taking in a 5-minute interval (missing values are coded as NA)

. date: The date on which the measurement was taken in YYYY-MM-DD format

. interval: Identifier for the 5-minute interval in which measurement was taken

[1]: https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2Factivity.zip

## What is mean total number of steps taken per day?
The mean total number is 37.38 steps


## What is the average daily activity pattern?
The average is 37.38


## Imputing missing values
There are 2304 missing values


## Are there differences in activity patterns between weekdays and weekends?
Yes, the plot shows there are less activity in weekends
