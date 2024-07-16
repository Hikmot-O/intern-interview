# Shuttlers Web App: Loyal Customer Analysis

## Overview

Let’s say we have the Shuttlers web app and we keep track of what pages customers are viewing, for things like business metrics.
Every time somebody comes to the web app, we write a record to a log file consisting of Timestamp, PageId, CustomerId. At the end of the day we have a big log file with many entries in that format. And for every day we have a new file.
Now, given two log files (log file from day 1 and log file from day 2) we want to generate a list of ‘loyal customers’ that meet the criteria of: (a) they came on both days, and (b) they visited at least two unique pages.
