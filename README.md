# Programmatically-Utilizing-Data-From-S3
Introduction
In this assignment we're tasked with completing a Lambda function that collects data from S3,
performs some basic formatting, and returns it to API Gateway to be loaded into a simple web
interface.
Scenario
You've been brought into a team to complete a proof of concept for a low cost employee
directory for your company. The team has created a simple web interface, organized some
placeholder employee information, and placed it in S3. They're having trouble getting the data
from S3 into Lambda and need your assistance. You will need to collect all 1500 placeholder
records from JSON files stored in an S3 bucket and return them in a single return from the
Lambda function provided in the lab environment.
Solution
Log in to the AWS Management Console. In another browser tab, open the random-users
website provided for the lab. The site won't load yet because you haven't assigned the Lambda
function an action.
What you can do:
Create couple of buckets named as per below and copy the respective files under them as
appropriate
random-users-<ACCOUNT_NUMBER>, which should be your static website.
random-users-data-<ACCOUNT_NUMBER>, which is the data that will populate the website.
Deploy the code using Lambda services after making necessary changes in the code. You can
write your own code or modify the existing code which has been attached for your reference
Finally test your url
http://random-users-<ACCOUNT_NUMBER>.s3-website-us-east-1.amazonaws.com
