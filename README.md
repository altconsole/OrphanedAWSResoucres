# OrphanedAWSResoucres
Finding Orphaned EBS Volumes, Snapshots and AMIs in all AWS Regions in an AWS Account
The code uses Python and BOTO3 and connects to AWS using BOTO3 API calls.
Number of API calls depends on the amount of orphanded resources and can be high if this activity has not been down earlier. 
The code also uses pandas to gather all this detail in to an excel file and saves it where the code runs.
We can make changes to the code and upload it to any specific location as well. 
