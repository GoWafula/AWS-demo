# AWS-demo
Deploying a simple static website to AWS

The website was downloaded from [FREE CSS](https://www.free-css.com/free-css-templates/page201/myportfolio)



# Deploying Your App to an EC2 Instance with Ubuntu and Nginx

This guide provides step-by-step instructions on deploying your application to an Amazon EC2 instance running Ubuntu, and configuring Nginx as the web server to serve your application.

## Prerequisites

- An AWS account with appropriate permissions to create and manage EC2 instances.
- Basic knowledge of AWS services and concepts.
- An application ready for deployment.
- SSH key pair for accessing the EC2 instance.

## Step 1: Launch an EC2 Instance

1. Go to the AWS Management Console and navigate to the EC2 service.
2. Launch a new instance, selecting Ubuntu Server as the operating system.
3. Configure the instance details, including instance type, networking, and security groups.
4. Select or create a new SSH key pair for accessing the instance.
5. Launch the instance.

## Step 2: Connect to the EC2 Instance

1. Use SSH to connect to the EC2 instance using the provided public IP address or DNS name.


## Step 3: Update and Install Dependencies

1. Update the package repository and installed packages.


2. Install required dependencies for your application.

## Step 4: Deploy Your Application

1. Transfer your application files to the EC2 instance using SCP or another file transfer method.


2. Configure and set up your application according to its specific requirements.

## Step 5: Install and Configure Nginx

1. Install Nginx on the EC2 instance.


2. Configure Nginx to serve your application. Create a new server block configuration file in `/etc/nginx/sites-available/` and symlink it to `/etc/nginx/sites-enabled/`.

3. Test the Nginx configuration for syntax errors.

4. If the configuration test passes, reload Nginx to apply the changes.

## Step 6: Access Your Application

1. Open a web browser and navigate to your EC2 instance's public IP address or DNS name.

2. You should see your application running and served by Nginx.

## Additional Steps

- **Security**: Implement security best practices such as firewall configuration, HTTPS setup, and regular system updates.
- **Monitoring and Logging**: Set up monitoring and logging to track the performance and health of your EC2 instance and application.
- **Scaling**: Consider implementing auto-scaling and load balancing for high availability and scalability.

## Resources

- [AWS Documentation](https://docs.aws.amazon.com/)
- [Nginx Documentation](https://nginx.org/en/docs/)


