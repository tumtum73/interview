# Intro - soft skills
- Tell me about yourself
- What techniques and tools do you use to keep yourself organized?
- Job History
- What are your Strengths
- What are your Weaknesses
- biggest accomplishment / most proud of
- biggest failure
- What have you done to improve your knowledge in the last year?

# General
- Most apps we deploy these days are web based. You open a browser, any browser, type a url and hit enter.  Describe what happens.
- What operating system do you prefer and why?

# Agile
- [What is the difference between agile and devops?](https://azure.microsoft.com/en-us/overview/devops-vs-agile/#:~:text=Understanding%20the%20difference&text=DevOps%20is%20a%20culture%2C%20fostering,common%20reality%20of%20changing%20needs.)

# DevSecOps / DevOps
- [Why do we want to adopt DevOps?](https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-devops/#:~:text=By%20adopting%20a%20DevOps%20culture,and%20achieve%20business%20goals%20faster.)
- What are the different phases of DevOps?
   - Plan - Initially, there should be a plan for the type of application that needs to be developed. Getting a rough picture of the development process is always a good idea.
   - Code - The application is coded as per the end-user requirements. 
   - Build - Build the application by integrating various codes formed in the previous steps.
   - Test - This is the most crucial step of the application development. Test the application and rebuild, if necessary.
   - Integrate - Multiple codes from different programmers are integrated into one.
   - Deploy - Code is deployed into a cloud environment for further usage. It is ensured that any new changes do not affect the functioning of a high traffic website.
   - Operate - Operations are performed on the code if required.
   - Monitor - Application performance is monitored. Changes are made to meet the end-user requirements.
- What is the difference between continuous integration, continuous delivery, and continuous deployment?
- What are some deployment strategies?
   - Rolling
   - Blue/Green
      - Define a plan for blue/green deployment with rollback on Azure using Terraform and pipelines.    
   - Canary
      - In a canary deployment to production, half the traffic returns 502, while others succeed. Walk us through your troubleshooting approach.
- - What is Infrastructure as Code and why do we use it?
- What is git and why do we use it?
- Tell me about Branching and Branch Policies.
- CI/CD pipeline takes 40 mins to deploy a small change. What would you do to optimize it?
- Suppose your production pipeline is blocked due to missing approvals and stakeholders are unreachable. What will you do?

# Security
- You’re asked to design a highly available logging system for 100+ microservices across 3 regions. What tools and architecture would you suggest?

# Kubernetes
- Explain how containers run in Kubernetes.
   - Pods
   - Routes
   - Ingress Controller
   - Secrets
- How does a Virtual Machine differ from a container?
- You’ve deployed an app to Kubernetes and it fails health checks randomly. How do you debug this end-to-end?
- You see high CPU usage in one pod, but logs look clean. What next?
- Production app works fine for internal users but fails for external ones (403 error). How will you isolate the issue?
- How would you set up an automated rollback strategy in Kubernetes for failed deployments?

# OpenShift

# Terraform
- How can you support Terraform IaC scenario where resources already exist in a cloud subscription?
   - terrform import [https://developer.hashicorp.com/terraform/cli/import](https://developer.hashicorp.com/terraform/cli/import)

# Azure DevOps
- How do you ensure secure and dynamic secret rotation in Azure DevOps pipelines?

# Azure 
- What are some of the Azure Services you have worked with?
- Describe how Azure Storage manages data in a cost-effective manner. 
    - Access Tiers - https://docs.microsoft.com/en-us/azure/storage/blobs/access-tiers-overview
    - File
    - Blob
    - Queue
    - Table

## - Azure PaaS

## - Azure Serverless

## - Azure IaaS

# AWS

## - AWS PaaS

## - AWS Serverless / Lambda

## - AWS IaaS / EC2

# Microservices

# Finish
- Why do you want this job?
- What do you expect to accomplish in the first 90 days?
- What are your goals for the next five years / ten years?
- Why should we hire you?

# Summary
Provide Summary at end of interview:

```
My assessment on [candidate]:
They have a good grasp on DevOps concepts.
They have little to no experience / understanding of Azure but willing to learn.  
They have a good understanding of Kubernetes.
They have a good understanding of Terraform and Infrastructure as Code solutions.
They have experience with jenkins, Grafana, and Prometheus.

I [do/do not] recommend hiring them as an [Senior DevOps Engineer], they seemed confident in most of their answers and have a drive to learn new things.
```


# References
- [Top 100+ DevOps Interview Questions and Answers for 2022](https://www.simplilearn.com/tutorials/devops-tutorial/devops-interview-questions)
- [Top DevOps Interview Questions You Must Prepare In 2022](https://www.edureka.co/blog/interview-questions/top-devops-interview-questions-2016/)
- [J.P. Morgan Interview Experience - LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7353638746455519232/?origin=NETWORK_CONVERSATIONS&midToken=AQHWFwFeu6M1eg&midSig=2Xal2kedAd1HU1&trk=eml-email_network_conversations_01-truncated~share~message-0-see~more&trkEmail=eml-email_network_conversations_01-truncated~share~message-0-see~more-null-kmofa~mdp8tczo~gi-null-null&eid=kmofa-mdp8tczo-gi&otpToken=MTEwMTE4ZTUxMjJhYzljMmJlMmYwMmVmNDUxNmU0YjI4Y2NjZDg0MTkxYWM4NTY5NzdjNzA0NmM0ZjVhNWZmMGZjODk4ZjhhNjllY2U0YzQwN2U4Y2QxN2U3YzQ3YTc0ZTExOWFjOWU0ZjRlNDQyMWFhLDEsMQ%3D%3D)
