# rioMajor-AWS-LIVE-PROJECT-DEPLOY-APP-USING-HTTPD
# AWS-LIVE-PROJECT-DEPLOY-APP-USING-HTTPD

#step1:First Launch an EC2 instance in the AWS
#step2👨‍💻:login to the ec2 instance
#step3:update the system using the Package Manager
#step4: install the git using the following command
       yum install git (Note: the package manager may vary depend upon the distribution of the Linux)
#step5: install the httpd (the httpd is a web server)using the below command
       yum install httpd -y 
       the httpd is required for keeping the application live as well as to get the http traffic.
#step6: inorder to run the project we should move our project to the directory called /var/www/html
        note: make use of the cp command to push the files to this particular directory
#step7: start the httpd web server using the following command
        systemctl start httpd
#step8: access the web app from the public IP address of the EC2 instance 
              Happy Learning:)
