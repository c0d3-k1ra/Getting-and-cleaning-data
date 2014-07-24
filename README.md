# Getting and Cleaning Data, Peer Assessment Project

## <u>How To</u>
To repeat the work done in this project:

* 1. Download source data from http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
* 2. Unzip to your working directory
* 4. Keep the data in 'UCI HAR Dataset'
* 3. Execute the script run_analysis.R from that directory.

## <u>Steps Performed</u>
The bulk of the steps done by the script involve loading the data provided from the source, and tidying this into a single data frame containing just the original data cells of interest, in the desired format.  Only the final major step computes a new result from the tidied data, writing out subject ids, activites, and mean of all measures of interest.


1.  feature names and subset to only those features of mean or std measures

2.  the train and test feature sets and subset only the desired features

3. bine the two datasets into 1

4. Each column names to features

5. Read and combine the train and test activity codes

6. Get activity labels and attach to activity codes

7. Get and combine the train and test subject ids

8. Combine and name subjects and activity names

9. Combine with measures of interest for finished desired data frame

### Compute New Result
From the set produced for analysis, compute and report means of all measures, grouped by subject_id and by activity.

