#Updated amazon guide for Student Accounts

This is a new guide for those who created an account while applying for the student accounts. (This will not be necessary if you already had an amazon console account, normal aws account).

In order to run spark clusters on amazon, there are a few extra steps with a student account.

	1. Log in at: https://awseducate.qwiklabs.com/focuses/2655?locale=en
	2. Here you can create a new lab. This will set up your user permissions and IAM related issues. 
	3. In a terminal type `aws configure`
	4. Enter the access key which was created when you started a lab ( left hand side in the web browser )
	5. You can now start clusters through the terminal and run your program.
	6. Open up the aws console to monitor the cluster.
	7. Remember to terminate the clusters.