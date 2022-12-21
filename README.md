# EC2-shutdown-scheduler
Save on server cost by creating a lambda schedule job that startups and shutdowns with the time that is specified. This project is going to utilize boto3 library (python).

Create Lambda functions that stop and start your EC2 instances
1.    In the Lambda console, choose Create function.

2.    Choose Author from scratch.

3.    Under Basic information, add the following:
      For Function name, enter a name that identifies it as the function used to stop your EC2 instances. For example, "StopEC2Instances".
      For Runtime, choose Python 3.9.
      Under Permissions, expand Change default execution role.
      Under Execution role, choose Use an existing role.
      Under Existing role, choose the IAM role that you created.

4.    Choose Create function.

5.    Under Code, Code source, copy and paste the following code into the editor pane in the code editor ( lambda_function). This code stops the EC2 instances         that you identify.
