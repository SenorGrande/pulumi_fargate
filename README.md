curl -fsSL https://get.pulumi.com | sh
restart shell
pulumi version

set up AWS creds

$ mkdir hello-fargate && cd hello-fargate
$ pulumi new aws-typescript --name myproject

$ mkdir app