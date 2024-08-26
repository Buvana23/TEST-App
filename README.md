# CI/CD pipeline with Jenkins

1. initialize the repository

2. setup EC2:
-- create ec2 with ubuntu
    --edit the security group inbound rules with tcp 8080
      --allow traffic to port 8080 (inbound rules)
--install Jenkins
    --shell
	--configure the Jenkins server
--install docker
	--create a docker file on local repository
--clone the app to ec2

cd ..
