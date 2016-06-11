# s3-static-website-cloudformation

[A CloudFormation script](https://raw.githubusercontent.com/matthew-andrews/static-website-cloudformation/master/stack.json) that does simple static file hosting on S3.

## Usage

1. Login to your **AWS console**
1. Go to **Identify & Access Management**
1. Create a **new user** and download its access and secret keys, remember what you called your user
1. Select the **region** in which you wish to host your S3 bucket in
1. Go to CloudFormation, click **create stack**
1. Download the contents of [`https://raw.githubusercontent.com/matthew-andrews/s3-static-website-cloudformation/master/stack.json`](https://raw.githubusercontent.com/matthew-andrews/s3-static-website-cloudformation/master/stack.json) — you may be able to alt+click this link.
1. In Select Template, choose **Upload a template to Amazon S3** and choose the file you just downloaded and click Next
1. In **Stack name** enter a sensible name (it doesn't matter), in **DomainName** enter the domain name of your website, and in **IAMDeployUser** enter the name of the user you created in step 3, click Next
1. Click Next again and click Create
