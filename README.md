# Bike-Sharing-Demand-with-AutoGluon
Project Overview : In this project, you'll use the AutoGluon library to train several models for the Bike Sharing Demand competition in Kaggle. You will be using Tabular Prediction to fit data from CSV files provided by the competition. This project will demonstrate your ability to use AutoGluon to train several iterations of models and record your personal optimization of the problem.

Bike-sharing demand is highly relevant to related problems companies encounter, such as Uber, Lyft, and DoorDash. Predicting demand not only helps businesses prepare for spikes in their services but also improves customer experience by limiting delays.

In the end, you will have submitted several entries to the competition and achieved a rank within Kaggle. You will also complete a report of your findings that you can share publicly on Kaggle or your personal page, providing a way to showcase your work.

The first step is to download all of the starter materials for the project, and create a Kaggle account so you can download the dataset and submit to the competition.

You can find all of the starter materials for this project at this GitHub repo.

You can then sign up for a Kaggle account (go here and click on the "Register" tab). Environment and Dependencies : For this project, you can either complete the work within Sagemaker Studio provided through the Udacity classroom, or on your own local computer. Launch the AWS Web Console from your Udacity Classroom You are given a federated user account, a temporary AWS user account with limited permissions, that you can use in this program.

Before you begin, be sure to log out of any AWS instances you may already have running. Then click on the “LAUNCH CLOUD GATEWAY” link in the left navigation pane to access a customized instance with the right permissions specific to this program. It will open up a pop-up, and clicking on the "Open Cloud Console" button in the pop-up will open the AWS console in a new browser tab. This may take a few moments to load the first time. See a brief video below for a walkthrough.

Ensure that you do not have a pop-up blocker installed; it may prevent the new tab from launching. Please be sure to allow pop-ups from Udacity.

Animation of launching the AWS console explained above Animation of launching the AWS console

Important Points to Remember

Session limit Note that there is a certain session time limit. If reached, you will automatically be timed out. As long as you have not used your entire allocated budget, your work will be saved. You can re-launch using the same "Launch Cloud Gateway" button in the left navigation menu to return to your session.

Default AWS region The default AWS region for you will be US East (N. Virginia) (us-east-1 ). In case you need more than one region for your work you can use us-east-2, us-west-1 or us-west-2. Note: You would not have permissions to access regions other than us-east-1, us-east-2, us-west-1, and us-west-2.

The budget allocated for you All AWS services are a pay-as-you-go service. Udacity has set a budget for each student to complete their course work. Please understand that these credits are limited and available for you to use judiciously. The budget for this entire course is $25. Although, we find about $10 sufficient for most to complete this course.

Shut down your resources | No extra credits We recommend you shut down/delete every AWS resource (e.g., EC2, Sagemaker, Database, EMR, CloudFormation) immediately after the usage or if you are stepping away for a few hours. Otherwise, you will run out of your allocated budget. Udacity will not provide additional credits. In case you exhaust your credits:

You will lose your progress on the AWS console. You will have to use your personal AWS account to finish the remaining ND. Even if you are in the middle of the project/exercise and need to step away, you must shut down your resources. You can re-instantiate them later. To better understand pricing, see the AWS Pricing for all available services. > For reference, any service available to you @$0.1/hour or higher should be monitored closely and shut down immediately after use or if you are stepping away. > Check the pricing at https://aws.amazon.com/pricing/ Check the pricing at https://aws.amazon.com/pricing/

Tracking your usage You need to make sure that you have an adequate budget available to complete your project/task. If you hit your budget, your session will time out and your work will be lost and unrecoverable. .
Track your usage on the AWS web console. Go to AWS Cost Explorer, and view the spending by selecting a Date Range. The starting date should be your Date of Enrollment in this course.

Checking costs using the AWS Cost Management Dashboard AWS Cost Management Dashboard

Note: The AWS Billing Dashboard might show extra costs as the AWS accounts provided by Udacity are reused once students graduate from a course. So the best way to check costs is using the AWS Cost Explorer by setting the appropriate Date Range as discussed above.

Monitoring costs using the AWS Cost Explorer is a good skill to learn!

IMPORTANT Concurrent/Parallel instance launch We do not support launching multiple EC2, RDS, or Sagemaker instances unless specifically mentioned in the classroom. Your AWS account will be suspended if you attempt at launching concurrent instances where they not required. Personal Information in AWS Please do not add any type of personal information to the AWS account and resources provided by Udacity for this course. This includes: email addresses, resource names, tags, phone number, name, etc. Deleting and Reusing Accounts Udacity will delete all resources in AWS accounts after six months of inactivity to ensure proper resource utilization and data security. Deleting resources means that all work will be lost and will need to be redone.

