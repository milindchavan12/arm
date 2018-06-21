# Azure Resource Manager

First, ARM allows us to logically arrange resources together so that we can deploy, manage and erase multiple resources easily. It also allows us to define dependencies within the resources. This is exceptionally useful when architecting solutions which are multitiered in nature. 

We can define dependencies between all those resources to ensure that when we deploy them, they are deployed in the right order. ARM also allows for repeatable deployments. Once we've done a deployment, we can go back. And if we wish to make a change rather than redeploy the solution entirely from scratch.

ARM also gives us very fine grained control over who can access our resources and what actions they can perform against them, using role based access control or RBAC.

### ARM Architecture
![alt text](https://pbs.twimg.com/media/DgPXKqAX4AAObhG.jpg)

Github : https://github.com/jamesbannan/pluralsight/tree/master/microsoft-azure-resource-manager-mastering
