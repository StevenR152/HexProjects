# HexProjects
A series of loosely independent workshops that plug into each other to teach many parts of technology in a way the industry uses them

Exercises are labeled with letters to show dependency, A1 should be done before A2. But B1 is loosely independent of both. You'll have a more rounded project if you do them all, as they can interlink so give a overall portfolio peice. For example making your frontend call the backend which are deployed using the devop's and run on the infrastructure individual exercises.

## [AWS](https://aws.amazon.com/) Exercise A1: Host a static website in S3 for dirt cheap!
In this exercise you're tasked to:

- Make a website that is hosted on [AWS](https://aws.amazon.com/) (Amazon Web Services) using Simple Storage Service (S3).
- Configure AWS infrastructure using best practice with Infrastructure  as code using [Terraform](https://www.terraform.io/)
- Create a deployment pipeline using [CircleCI](https://circleci.com/signup/) to auto-magically update the website from changes in GitHub.

### What will you learn?

- S3 and bucket policies to store files publicly. 
- [Circleci](https://circleci.com/signup/) as a continuous deployment pipeline. 
- Git committing and pushing changes to GitHub 
- Infrastructure as code with terraform. 
- Structure a webpage using [HTML](https://www.w3schools.com/html/html_basic.asp) / [CSS](https://www.w3schools.com/css/default.asp).

### Steps
Let's get started:

1) Create a [GitHub](https://github.com) repository containing a hello world [html](https://www.w3schools.com/html/html_basic.asp) file (optional: that links a [css](https://www.w3schools.com/css/default.asp) file to change font size).
2) Use [terraform](https://www.terraform.io/) to create a [AWS](https://aws.amazon.com/) S3 storage bucket that will hold the website's files. 
3) Use [Circleci](https://circleci.com/signup/) to deploy all code changes to the S3 storage bucket when changed. [reference guide](https://circleci.com/docs/2.0/ecs-ecr/)
4) Update the [terraform](https://www.terraform.io/) to add a policy making the bucket publicly accessible. Don't forget to attach the bucket to the policy. You can browse the AWS Management Console S3 service to see the Policy is on the bucket.
5) View the [html](https://www.w3schools.com/html/html_basic.asp) file using the public url which is found on the html files properties tab (visible within the [aws](https://aws.amazon.com/) user interface). 
6) Commit and push changes to the repository that makes the webpage contain different content or link in a [css](https://www.w3schools.com/css/default.asp) file to style the page. 


## [AWS](https://aws.amazon.com/) Exercise A2: Make the hosted website call a backend!

In this exercise you're tasked to:
Update your A1 exercise's website to call functionality on a provided backend api.
- use jquery (or plain old javascript) to request a public api - For this tutorial no API key will be required
- use jquery to update the page. 
- use css/html to structure information on a page


### Steps
1 - use your  GitHub repository from the earlier website project (session 1). 
2 - Include jquery into the page in a script tag. 
3 - implement calling the public api to print the response to the console. 
4 - use the response object to update the page with information. 
5 - style the page. 

## Extra for experts
For advance users - try to build the following filters:

- Name search filter
- group geolocation

Wicked, the website is starting to take shape! 

Wrapping up the technology and purpose:

- JQuery to issue an HTTP GET request
- JQuery to manipulate the website DOM to add information
- CSS to style the page

## Resources

- [https://api.jquery.com/](https://api.jquery.com/)
- [https://github.com/codersuk/AWS-exercise-1](https://github.com/codersuk/AWS-exercise-1)
- Json data for the XMLhttprequest [data.json](https://codersuk-test.s3-eu-west-1.amazonaws.com/data.json)


## [AWS](https://aws.amazon.com/) Exercise B1: Create a serverless backend on AWS!
In this exercise you're tasked to:

- Make a python (or other) backend api which runs as a serverless app in AWS.
- Configure AWS infrastructure using best practice with Infrastructure  as code using [Terraform](https://www.terraform.io/)

### What will you learn?

- AWS API Gateway and AWS Lambda.
- Git committing and pushing changes to GitHub 
- Infrastructure as code with terraform. 
- JSON formatted API responses.

### Steps
Let's get started:

1) Create a [GitHub](https://github.com) repository containing a hello world [html](https://www.w3schools.com/html/html_basic.asp) file (optional: that links a [css](https://www.w3schools.com/css/default.asp) file to change font size).
2) Use [terraform](https://www.terraform.io/) to create a [AWS](https://aws.amazon.com/) S3 storage bucket that will hold the website's files. 
3) Use [Circleci](https://circleci.com/signup/) to deploy all code changes to the S3 storage bucket when changed. [reference guide](https://circleci.com/docs/2.0/ecs-ecr/)
4) Update the [terraform](https://www.terraform.io/) to add a policy making the bucket publicly accessible. Don't forget to attach the bucket to the policy. You can browse the AWS Management Console S3 service to see the Policy is on the bucket.
5) View the [html](https://www.w3schools.com/html/html_basic.asp) file using the public url which is found on the html files properties tab (visible within the [aws](https://aws.amazon.com/) user interface). 
6) Commit and push changes to the repository that makes the webpage contain different content or link in a [css](https://www.w3schools.com/css/default.asp) file to style the page. 
