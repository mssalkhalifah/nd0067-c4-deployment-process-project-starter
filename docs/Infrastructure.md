# Overview
This section presents the workflow of the infrastructure.

![Infrastructure](https://res.cloudinary.com/domq50ciy/image/upload/v1674306128/Hosting%20a%20Full%20Stack%20Application/Inkdrop_Hyq5E8swhG_zjnvzp.png)

## AWS
Amazon web services is used for hosting the full-stack web application. The front-end of the web application is hosted on Amazon simple storage service or Amazon S3. And the back-end is hosted and managed by AWS elastic beanstalk. As for the database, we use Amazon relation database service.

## CircleCi
CircleCi is a continuous integration and delivery platform for implementing DevOps practices. And it is used in our project by pushing to github, then it goes through the build process where it will install and test packages. After that, it waits for approval. Then, the next and final process is the deploy stage where it will deploy and push the compiled and distributed version of our front and back end code to AWS services.

