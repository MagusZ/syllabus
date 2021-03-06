# Instructors

This document contains information that is relevant to running the course, including technical details about computing resources.

It will be helpful to standaridize computing tools, file distribution, etc as much as possible. The information provided here serves to help that effort, but if these tools aren't appropriate for your needs then by all means do procede however is best for you.

## Github

Casey will maintain course files using [github education tools](https://education.github.com/guide). I can provide write access to these respoitories, or post files that you send to me.

The intent of using github is:

- To streamline the operation of the course.
- To provide students with access to all materials after they leave so that they can continue to work with them and share them with others.
- To create a consolidated set of resources that could be used to teach the course in the future.

## Amazon Web Services

We will use [AWS](https://aws.amazon.com) for the remote computing components of the class.

The course will be configured as follows:

- We will have [EBS](https://aws.amazon.com/ebs/) storage for storing data and other files while the course will be in session. This will be deleted at the end of the course. Small datasets (less than a few hundred MB) can also be included on this virtual drive. Casey will provide information on how to add data to this drive when it is created.

- Casey will create an Ubuntu [Amazon Machine Instance](http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AMIs.html) (AMI) for the course that has all software preinstalled. This image will be used to create each new virtual computer. Please create a new issue on the [issue tracker](https://github.com/neptune2016/syllabus/issues) to request software for Casey to install by May 13, 2016.

- For each analysis, students will create an [EC2](https://aws.amazon.com/ec2/instance-types/) instance with the course AMI. This will give them a fresh virtual machine with preconfigured software for each analysis. After the results are obtained, the virtual machine will be terminated.

To keep costs down, we will want to keep the example analyses as small as possible to reduce data footprint and run times. Everyone will need an amazon account for authentication, but computing charges will be covered by the course (up to a limit). 

