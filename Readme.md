=> In this project (UdacityUda App), I deployed web servers for a highly available web app using CloudFormation.
=> I wrote the script that creates and deploys the infrastructure and application for an Udagram app from the ground up.
=> The script begin deploying the networking components followed by servers, security roles and software.

## The files included are:
```sh
* /Images : Screenshot the result of deploy.
* /wesbite : Udacity website code
* create.sh : Cloudformation create stack script. 
* update.sh : Cloudformation update stack script.
* destroy.sh : Cloudformation delete stack script.
* infra_network.yml : UdacityUdaApp Project's CloudFormation script.
* infra_parameter.json : UdacityUdaApp Project's CloudFormation script parameters.
```
## Instruction of deploy:

Just run;
```sh
> ./create.sh UdagramApp infrastructure_networkandserver.yml infrastructure_networkandserver.json
```

Also, Check out the running website:
```sh
> http://udaci-webap-ecof8g3zmr4o-1681344935.us-west-2.elb.amazonaws.com/
```