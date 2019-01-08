R Programming Test
==================

Automatic recognition of outage in production

There is a machine learning based system in production. It outputs a probablity score. An outage in one of the modules of the system resulted in deviation of the output score.

Write an R function which recognizes the start and end time of the outage with precision up to 1 hour.

Input: time series based data where each number (i.e. score value) is associated with a time point - data.csv.
Output: 
(1) start and end time of the outage; OR 
(2) time serie where significant deviation in output score is represented by outliers (see figure1.png - the outage started around 6pm on 2018-01-10 and ended around 12pm on 2018-01-10); OR
(3) something else that helps to AUTOMATICALLY recognize the deviation in the output score.


