# Statistics
Question:  
If we don't know the population mean (as would commonly be the case) we need to divide by n-1 in our variance calculations to get the best estimate of the true population variance and thus the standard deviation. Why we use n-1 as Degree of Freedom in standard deviation?

This is the document containing empirical proof of the same standard deviation formula using Excel.

In this spreadsheet we calculate the variance using a known population mean and compare this calculation to three alternate calculations where the population mean is unknown.

Imagine taking a sample of 100 employees in a company and asking them to write down the final  two digits of their employee number.
NOTE: This is like a random selection between digits 0-99. Thus, a known population mean of 49.5.

Step1: Standard Deviation using known population mean (µ=49.5)
For each employee, calculate the squared deviation from the population mean
For each sample, find the sum of these squared deviations and divide by n (which is 100). This is our estimate of the variance for each sample.
Now take the square root.This is our estimate of the standard deviation for each sample
Std Deviation:9.123210239

Step1: Standard Deviation assuming the population mean is unknown	
Find the sample mean.	
For each employee, find the squared deviation from the sample mean.
Now sum these squared deviations from the sample mean for each sample. This is the numerator of the sample variance formula.
Now divide this number by n, n-1 and n-2 respectively,. These are three alternate versions of the variance, using different denominators: n, n-1 and n-2
Now take the square root. This is now three alternate esimtations of the standard deviation for each sample

Now take the average of these calculations across all 100 samples. This is now three alternate esimtations of the standard deviation across all samples

Compare these estimates to our original calculation of the standard deviation (where the known µ was used)
At n-1, Standard Deviation when population mean is not known is closer to Standard Deviation when known population mean (µ=49.5).
