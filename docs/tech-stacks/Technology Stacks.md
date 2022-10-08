## Technology Stacks

Technologies and Tools I have worked with for over 3 years

**GitOps**  | **Distributed Systems** | **AWS**
-----------------------|-----------------------|-----------------------
Linux, Bash Scripting |  Blockchain |  S3, CodeBuild
Python |  Kubernetes, Istio |  Cloudwatch
Asdf, Git, GitHub |  Helm, Docker |  EC2, EKS, ECS, ECR
Groovy |  YAML, JSON |  IaC, IAM
Terraform |  Spring, Micronaut, |  Datadog, Splunk
FluxCD, ArgoCD |  Jib/Docker |  Okta

### GitOps ⭐️⭐️⭐️

Certified GitOps At Scale. My first used of GitOps was ArgoCD. I love working with declarative approach where the desired states is known through well defined files and versioned.

***Learnings:*** 

- *Starting:* *FluxCD, GitOps Operator*

### **Linux, Bash Scripting, Python** ⭐️⭐️⭐️

- I used Linux daily for building **containers images** and **GitHub runners** for microservices, **automating script, GitHub actions** to published libraries and I constantly learn new things every day

***Learnings**:* 

- *Ongoing: API development with FastAPI. FastAPI is a python framework for rapid APi development for microservices.*

### **Distributed Systems** ⭐️⭐️⭐️

- I built and deployed distributed systems with **Spring & Micronaut** microservices technologies using as **Docke**r, **Kubernetes**
- I managed the deployment with **helm, Spinnaker**
- I also created a continuous integration testing system to test **Yaml** formatting and good practices for **Kubernetes manifests.**  The continuous testing also ensures developers does not integrate error to production regardless of the code and location

***Learnings:*** 

- S*tarting: learning Go-Operator Development with Kubebuilder*
- *Integrate Jib to build Java images because Java has memory leaks with Docker and Jib images are lighter and native to Java*

### **AWS** ⭐️⭐️⭐️

- I developed a pipeline that compiled **Java (**Spring & Micronaut) **microservices** with **Groovy**  into **Jar** file, and built the image on **Amazon Web Services** with AWS **CodeBuild.** The image stored on AWS container registry **ECR** which triggers the Spinnaker to deployed the images to **EKS** clusters

### Monitoring, Observability and Troubleshooting ⭐️⭐️⭐️

- I owned **Java microservices** and I monitored the DevOps pipeline end-to-end. I used **Komodor** for pods uptime and downtime, and **Lens** to **monitor** and **troubleshoot** failed **containers** in **pods.**
- As part of my day-to-day activities, I monitored the pipeline from build stage (CodeBuild), Spinnaker deployments with **Slack notifications**, service failures alert with **PagerDuty** and **CloudWatch.**
- I configured **Splunk agents** on Kubernetes manifest while I enabled services and monitor the **Pods** from **Splunk Dashboard**
- I configured **DataDog agents for Spring & Micronuat** microservices**, monitored** and **traced errors** from DataDog ****dashboard

***Learnings:***

- DONE: **Istio**: *Traffic Monitoring, Distributed Tracing and Observability, and Security with Istio Service Mesh, Promethues, Grafana, Kiali, Jaeger*

### Infrastructure As Code - IaC ⭐️⭐️⭐️

- I used terraform to orchestrate the infrastructure as a DevX Engineer enabling services for developers. terraform and terraform cloud
- I used **kOps** to orchestrate clusters on AWS, **deployed** (the built images on ECR) on **EKS** and created **Backup** of the **Cluster** with **Valero**
- I used Spin-hepler script to provisioned **EKS** cluster accessible to **Spinnaker** while I deployed the services from Images on ECR
- I provisioned elastic infrastructure VPC, EC2 instances, Security groups, LoadBalancers, InternetGateways with **CloudFormation**

### **Kubernetes** ⭐️⭐️⭐️

- I provisioned  EKS clusters with **kOps,** back-up and restore the cluster with **Velero**
- As a DevX Engineer, I troubleshoot EKS clusters, pods and containers and communicate findings with developers. And, I implemented continuous testing that informed developers of errors about to introduce to production

***Learnings:***

- *Staring:* Go - Developing Kubernetes Operator with Kubebuilder

### DevOps Strategies ⭐️⭐️⭐️

I developed strategies based on my day-to-day collaboration with Developers and enhanced the Developer Experience (DevX)-I implemented a continuous testing that informed Developers on errors about to introduce to production

### Technical writing ⭐️⭐️⭐️

I enjoy writing about technical subjects and I feel I can do a pretty good job about it! My motivation is explaining things in simple and practical terms and thus making things easier for others

### Collaboration ⭐️⭐️⭐️

Jira (Sprint & Kanban), Notion, Slack, Google Meet, Zoom

### Versioning  ⭐️⭐️⭐️

Git, GitHub, Jira

I use **A tool version manager (Asdf) to manage my local environment**

I use Pip and Poetry for code versioning and dependency management

I use Renovate for dependency management for distributed reposirtories

