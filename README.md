# Environment description

Firstly, that is a live doc. For sure, everytime you come, it will have a disparate version than the last time you came. <br>

This environment consists in having a GitlabCI deploying Apps via Helm in a Kubernetes environment <br>

In addition, this GitlabCI has a Kubernetes CI/CD pipeline deploying an Node.js application that returns randomly the Http codes 200 and 500. <br>

As we are using GitlabCI we will have here an Canary Deploy implementation. I'll still think about the requirements! <br>

I will try to deploy another Node.js app that make calls for the app above and logs only the Http code 500 in some resource, I'll still decide in what resource! Any recommendations? Let me know! <br>

In the future it will have a Terraform integration with Helm as well, maybe to deploy the Kubernetes environment or/and some resources in a Cloud as GCP, AWS or Azure. <br>

Is desired to have here an Grafana Deployment to collect Metrics and Observability (spams, traces) of our Microservices. <br>

For now that's it! <br>
