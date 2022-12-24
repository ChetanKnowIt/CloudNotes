## Basics of Cloud
1. What is virtualization?
- Virtualization uses software to create an abstracted/virtual software layer over computer hardware that allows the hardware elements of a single computer—processors, memory, storage and more—to be divided into multiple virtual computers, commonly called virtual machines (VMs)

2. What is VM?
- A virtual machine is a virtual representation, or emulation, of a physical computer. They are often referred to as a guest while the physical machine they run on is referred to as the host.
Reference: https://www.ibm.com/cloud/learn/virtual-machines

3. What is a hypervisor?
- A hypervisor is a small software layer that enables multiple operating systems to run alongside each other, sharing the same physical computing resources. These operating systems come as virtual machines (VMs)—files that mimic an entire computing hardware environment in software.
Reference: https://www.ibm.com/cloud/learn/hypervisors

4. What is a container?
- The container includes all the code, its dependencies and even the operating system itself. This enables applications to run almost anywhere — a desktop computer, a traditional IT infrastructure or the cloud.
Reference: https://www.ibm.com/cloud/blog/containers-vs-vms#:~:text=What%20are%20containers%3F

5. What is an Docker image?
- An image is a read-only template with instructions for creating a Docker container. Often, an image is based on another image, with some additional customization. For example, you may build an image which is based on the ubuntu image, but installs the Apache web server and your application, as well as the configuration details needed to make your application run.
Reference: https://docs.docker.com/get-started/overview/#:~:text=of%20those%20objects.-,Images,-An%20image%20is

6. What is a Docker Container?
- A container is a runnable instance of an image. You can create, start, stop, move, or delete a container using the Docker API or CLI.
Reference: Docker getting started

7. What is a microservice?
- A microservices architecture splits an application into a series of independently deployable services that communicate through APIs. This allows each individual service to be deployed and scaled independently. 
Reference: https://www.atlassian.com/microservices/microservices-architecture/microservices-vs-monolith



## Syllabus https://cdac.in/index.aspx?courseid=65&id=DBDA
1. What is cloud computing?
- Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers
Reference: https://aws.amazon.com/what-is-cloud-computing/


2. Understanding Cloud Vendors (AWS:EC2 instance, lambda and Heroku: Heroku platform, Heroku Data services)
- AWS:EC2 provides IaaS where you get to choose a VM, OS, Memory and deploy your application on top of it with secure login
- Lambda is a compute service that lets you run code without provisioning or managing servers 
Use cases: https://www.contino.io/insights/aws-lambda-use-cases 
References: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html#features
- Heroku platform: Heroku (PaaS) lets you deploy, run and manage applications written in Ruby, Node.js, Java, Python, Clojure, Scala, Go and PHP.
References: https://devcenter.heroku.com/articles/getting-started-with-python?singlepage=true
- Heroku Data services: provides database for deployed apps without all the details of managing it. Heroku Data for Redis is an in-memory key-value data store, run by Heroku, that is provisioned and managed as an add-on.

3. Definition of cloud computing?
- Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared
pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that
can be rapidly provisioned and released with minimal management effort or service provider interaction.
This cloud model is composed of five essential characteristics, three service models, and four deployment
models.
	- Characterisitics:
	1. On-demand self-service.
	2. Broad network access.
	3. Resource pooling.
	4. Rapid elasticity. 
	5. Measured service.
	- Service Models:
	1. Software as a Service (SaaS)
	2. Platform as a Service (PaaS).
	3. Infrastructure as a Service (IaaS)
	- Deployment models:
	1. Private Cloud
	2. Community Cloud
	3. Public Cloud
	4. Hybrid Cloud

4. Components of cloud?
- CPU and Networking
- Storage
- Automation and Orchestration
- Operations and Management
- Visualization tools
- Security Compliance
Reference: https://aws.amazon.com/hpc/solution-components/

5. Organizational scenarios of cloud 
https://azure.microsoft.com/en-in/resources/cloud-computing-dictionary/what-is-cloud-computing/#benefits
- test and development
- disaster recovery and backup easily
- big data analytics
- big storage

6. How to choose cloud service?
https://azure.microsoft.com/en-in/resources/cloud-computing-dictionary/choosing-a-cloud-service-provider/

7. Comparison among SAAS, PAAS, IAAS
to admin and monitor you need to have AWS/login with cloud provider
SaaS is great for consumers to get great software without much investment
PaaS gives startups less time to market and pushes them to focus on just the software without worrying on the infrastructure management
IaaS lets big organizations pool capital resources to implement a multi-purpose data center model for long term use cases

8. Cloud Products and Solutions, Cloud Pricing, Compute Products and Services, Elastic Cloud Compute, Dashboard.
list of cloud solutions: S3 is storage for media and files, EC2 for VMs, RDS is for MySQL like database on cloud, CloudFront is the content delivery network

## Virtualbox
Follow the steps given here for virtualbox with ubuntu 
👉 [link to page](https://www.nakivo.com/blog/install-ubuntu-on-virtualbox-virtual-machine/)



