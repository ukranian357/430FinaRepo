# 430FinaRepo
This repository will use Amazon Quick Sight to analyze very large sets of data we upload to Quick Sight.
Steps tp replicate

Slide 1: Introduction
 Title: Project Infrastructure Overview
Slide 2: AWS Setup
1. Title: AWS Setup
2. Instructions:
 Log into the AWS account.
 Select Amazon S3.
 Create a Bucket:
 General Configuration:
 AWS Region: US West (Oregon) us-west-2.
 Bucket Type: General purpose (default).
 Bucket Name: &quot;a3abucket.&quot;
 Block Public Access Settings:
 Uncheck &quot;Block all public access.&quot;
 Acknowledge the potential for public access.
 Create Bucket.

Slide 3: Data Download and GitHub Reference
1. Title: Data Download and GitHub Reference
2. Instructions:
 Refer to a YouTube video for setup.

 Follow the GitHub hyperlink provided.
 Download two files:
 Amazon-BestSeller-Dataset.csv.
 Manifest. Json.
 Modify &quot;ababucket1&quot; to &quot;a3abucket&quot; in Manifest. Json.
 Upload both files to the created bucket.

Slide 4: Bucket Permissions
1. Title: Bucket Permissions
2. Instructions:
 Access a3abucket info.
 Select Permissions.
 Edit bucket policy.
 Copy-paste the bucket name in policy.
 Save changes.
Slide 5: Validate Data Upload
1. Title: Validate Data Upload
2. Instructions:
 Access a3abucket info.
 Select Objects.
 Confirm the presence of both files.

Slide 6: QuickSight Setup
1. Title: QuickSight Setup
2. Instructions:
 Go to AWS QuickSight, and create an account.
 Input username and email.
 After account creation, select Datasets.
 Create a new dataset using S3 as the data source.

Slide 7: Dataset Configuration
1. Title: Dataset Configuration
2. Instructions:
 Data Source Name: Finalworks.
 Upload manifest file: s3://a3abucket/manifest.json.
 Connect and finish dataset creation.

Slide 8: Data Visualization
1. Title: Data Visualization
2. Instructions:
 Select Visualize.
 Create a graph.
 Utilize categories for bestsellers.
 Demonstrate how to display the bestsellers on a graph.

Slide 9: Graph Customization
1. Title: Graph Customization
2. Instructions:
 Show how to customize the graph by sorting categories.
 Sort descending for a clearer representation.
 Apply changes.
Slide 10: Project Overview
1. Title: Project Overview
2. Summary:
 Emphasize the importance of data visualization.
 Mention the project&#39;s focus on Amazon bestsellers.
 Highlight the potential applications for the project data.

Slide 11: Conclusion
1. Title: Conclusion

2. Closing remarks:
 Recap the key steps in setting up AWS and QuickSight.
 Encourage exploration and further customization.
 Express readiness for project development.

This restructured presentation provides a step-by-step guide for setting up AWS and QuickSight,
downloading and uploading data, configuring permissions, and visualizing the data for the
project.
















references: 
https://github.com/techwithlucy/youtube/tree/main/2-s3-quicksight (tech with lucy tutorial)
https://www.youtube.com/watch?v=4-8cXuZzKTg
i want to thank Lucy for the wonderful video along with her github on how to follow this project to establish a very detailed and customized graph using quicksight
