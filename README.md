This repo holds the configuration file used for the Autoscaling in AWS with Memory metrics tutorial on Medium. 
https://medium.com/p/c21158176b3d/edit

Download the AWS CloudWatch Agent - https://amzn.to/2UlHNQD
Install the AWS CloudWatch Agent - sudo rpm -U ./amazon-cloudwatch-agent.rpm
Start the agent with a custom configuration file - sudo amazon-cloudwatch-agent-ctl -a fetch-config -m ec2 -c file:./config.json -s

Lawal Adekunle Olusegun
lawaladekunle@gmail.com
