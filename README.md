In this project, you will deploy a static website to AWS using S3, CloudFront, and IAM.

The files included are: 

index.html - The Index document for the website.
/img - The background image file for the website.
/vendor - Bootssrap CSS framework, Font, and JavaScript libraries needed for the website to function.
/css - CSS files for the website.

Succesfully deployed out static travel blog page on cloudfront and s3 bucket


S3 Bucket Name: assignment-udacity-bucket1
we have gone for a secure approach (CloudFront with Origin Access Control), our S3 bucket is completely locked down and private to the outside world. The S3 Object URL will always throw an "Access Denied" error if we try to visit it directly in our browser.

CloudFront URL: d2vgr5srfduj3x.cloudfront.net
 and via https://d2vgr5srfduj3x.cloudfront.net/index.html both these urls are comppletely accessible

i have succesfully added the screenshots for all the points in rubric 
please find them attached in the screenshots folder in the repo.

Here is the direct endpoint url for out s3 bucket:

http://assignment-udacity-bucket1.s3-website-us-east-1.amazonaws.com/
(Visiting this URL returns a 403 Forbidden error because the bucket is secured with an OAC policy, ensuring traffic only flows through cloudfront)
