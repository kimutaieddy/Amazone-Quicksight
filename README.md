# NextWork - Visualize Data with QuickSight

## Project Overview

This project demonstrates how to visualize data using Amazon QuickSight. It covers the steps involved in setting up the necessary AWS resources, uploading data to an S3 bucket, and creating visualizations in QuickSight.

## Table of Contents

1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Project Steps](#project-steps)
    - [Upload Project Files to S3](#upload-project-files-to-s3)
    - [Create QuickSight Account](#create-quicksight-account)
    - [Connect S3 Bucket to QuickSight](#connect-s3-bucket-to-quicksight)
    - [Create Visualizations](#create-visualizations)
    - [Using Filters](#using-filters)
    - [Setting up a Dashboard](#setting-up-a-dashboard)
4. [Project Duration](#project-duration)
5. [Unexpected Findings](#unexpected-findings)
6. [Conclusion](#conclusion)
7. [References](#references)

## Introduction

Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence (BI) service built for the cloud. This project utilizes QuickSight to analyze and visualize data from a dataset stored in an Amazon S3 bucket.

## Prerequisites

- An AWS account
- Basic knowledge of AWS S3 and QuickSight
- The dataset files: `manifest.json` and `netflix_titles.csv`

## Project Steps

### Upload Project Files to S3

1. Create an S3 bucket in your AWS account.
2. Upload the `manifest.json` and `netflix_titles.csv` files to the S3 bucket.
3. Edit the `manifest.json` file by replacing the URL in the file with the S3 URL of your dataset.

### Create QuickSight Account

1. Sign up for Amazon QuickSight.
2. Note that creating a QuickSight account costs $18 per user per month with an annual commitment.
3. The account creation process should take approximately 2 minutes.

### Connect S3 Bucket to QuickSight

1. Open your AWS Management Console and navigate to QuickSight.
2. Connect your S3 bucket to QuickSight by following the guided steps.
3. The `manifest.json` file will direct QuickSight to your data.

### Create Visualizations

1. In QuickSight, create a new analysis.
2. Load the data from your S3 bucket into QuickSight.
3. Use the drag-and-drop interface to create visualizations. For example, you can create a graph to visualize Netflix data.

### Using Filters

1. Apply filters to your data to narrow down the visualization results.
2. Example: Filter the data to show the number of TV shows and movies listed under categories like 'Action & Adventure', 'TV Comedies', or 'Thrillers'.

### Setting up a Dashboard

1. Create a dashboard to display your visualizations.
2. Export your dashboard as a PDF for sharing or presentation purposes.

## Project Duration

This project took approximately 2 hours to complete.

## Unexpected Findings

One unexpected aspect of this project was the ease and efficiency of using Amazon QuickSight for data visualization.

## Conclusion

This project demonstrates how to effectively use Amazon QuickSight for data visualization. By following the steps outlined, you can set up your own visualizations and dashboards with ease.

## References

- [Amazon QuickSight Documentation](https://docs.aws.amazon.com/quicksight/)
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/)
- [NextWork.org](https://nextwork.org/)

