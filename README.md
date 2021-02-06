`$ curl -fsSL https://get.pulumi.com | sh`  
restart shell  
`$ pulumi version`  

set up AWS creds  

`$ mkdir hello-fargate && cd hello-fargate`  
`$ pulumi new aws-typescript --name myproject`  

`$ mkdir app`  
`$ touch app/Dockerfile`  
`$ touch app/index.html`  

`$ pulumi up`  
Might have to log in/add an access token  
`$ pulumi destroy`  