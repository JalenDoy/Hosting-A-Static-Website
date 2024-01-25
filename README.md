# Hosting-A-Static-Website

<h2>Task 1: Creating a bucket in Amazon S3</h2>

1. In the AWS Managment Console, click on S3 in the services menu.
2. Click **Create Bucket**.
3. For Bucket name, enter: website-<123> (replace <123> with a random number)
4. In the Object Ownership section, select ACLs enabled, then verify Bucket owner preferred is selected.
5. Clear Block all public access, then select the box that states I acknowledge that the current settings may result in this bucket and the objects within becoming public. Then click Create Bucket.
6. Choose the bucket that was just created.
7. Select properties tab. scroll to tags, and then choose edit and add tag to enter the following.
     - Key: Department
     - Value: Marketing
8. Choose save changes
9. Scroll to the bottom of the page to get to Static Web Hosting. Choose edit and enter the following settings
     - Static Web Hosting: Enable
     - Hosting Type: Host a Static Website
     - Index Document: index.html (Type this in)
     - Error Doucment: error.html
10. Save changes
11. In the Static website hosting panel, choose the link under Bucket website endpoint. (You will receive a 403 Forbidden message because the bucket permissions have not been configured yet. Keep this tab open in your web browser so that you can return to it later. Your bucket has now been configured to host a static website)

<p align="center">
<br/>
<img src="https://i.imgur.com/V97GtNn.png"/>
