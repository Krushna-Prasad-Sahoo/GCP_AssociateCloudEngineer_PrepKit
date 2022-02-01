# Associate Cloud Engineer Preparation Kit

<p align="justify"> An Associate Cloud Engineer deploys and secures applications and infrastructure, monitors operations of multiple projects, and maintains enterprise solutions to ensure that they meet target performance metrics. This individual has experience working with public clouds and on-premises solutions. They are able to use Google Cloud Console and the command-line interface to perform common platform-based tasks to maintain and scale one or more deployed solutions that leverage Google-managed or self-managed services on Google Cloud.</p>

![](https://www.cloudsmog.net/wp-content/uploads/google-cloud-certified_associate-cloud-engineer.jpg)

# Syllabus

- ### Section 1 : Setting up a cloud solution environment
    - #### 1.1 Setting up cloud projects and accounts. Activities include:
      - Creating a resource hierarchy
      - Applying organizational policies to the resource hierarchy
      - Granting members IAM roles within a project
      - Managing users and groups in Cloud Identity (manually and automated)
      - Enabling APIs within projects
      - Provisioning and setting up products in Google Cloud’s operations suite
    - #### 1.2 Managing billing configuration. Activities include:
      - Creating one or more billing accounts
      - Linking projects to a billing account
      - Establishing billing budgets and alerts
      - Setting up billing exports
    - #### 1.3 Installing and configuring the command line interface (CLI), specifically the Cloud SDK (e.g., setting the default project).

- ### Section 2. Planning and configuring a cloud solution
    - #### 2.1 Planning and estimating Google Cloud product use using the Pricing Calculator
    - #### 2.2 Planning and configuring compute resources. Considerations include:
        - Selecting appropriate compute choices for a given workload (e.g., Compute Engine, Google Kubernetes Engine, Cloud Run, Cloud Functions)
        - Using preemptible VMs and custom machine types as appropriate
    - #### 2.3 Planning and configuring data storage options. Considerations include:
        - Product choice (e.g., Cloud SQL, BigQuery, Firestore, Cloud Spanner, Cloud Bigtable)
        - Choosing storage options (e.g., Zonal persistent disk, Regional balanced persistent disk, Standard, Nearline, Coldline, Archive)

- ### Section 3. Deploying and implementing a cloud solution
    - #### 3.1 Deploying and implementing Compute Engine resources. Tasks include:
      - Launching a compute instance using Cloud Console and Cloud SDK (gcloud) (e.g., assign disks, availability policy, SSH keys)
      - Creating an autoscaled managed instance group using an instance template
      - Generating/uploading a custom SSH key for instances
      - Installing and configuring the Cloud Monitoring and Logging Agent
      - Assessing compute quotas and requesting increases
    - #### 3.2 Deploying and implementing Google Kubernetes Engine resources. Tasks include:
      - Installing and configuring the command line interface (CLI) for Kubernetes (kubectl)
      - Deploying a Google Kubernetes Engine cluster with different configurations including AutoPilot, regional clusters, private clusters, etc.
      - Deploying a containerized application to Google Kubernetes Engine
      - Configuring Google Kubernetes Engine monitoring and logging
    - #### 3.3 Deploying and implementing Cloud Run and Cloud Functions resources. Tasks include, where applicable:
      - Deploying an application and updating scaling configuration, versions, and traffic splitting
      - Deploying an application that receives Google Cloud events (e.g., Pub/Sub events, Cloud Storage object change notification events)
    - #### 3.4 Deploying and implementing data solutions. Tasks include:
      - Initializing data systems with products (e.g., Cloud SQL, Firestore, BigQuery, Cloud Spanner, Pub/Sub, Cloud Bigtable, Dataproc, Dataflow, Cloud Storage)
      - Loading data (e.g., command line upload, API transfer, import/export, load data from Cloud Storage, streaming data to Pub/Sub)
    - #### 3.5 Deploying and implementing networking resources. Tasks include:
      - Creating a VPC with subnets (e.g., custom-mode VPC, shared VPC)
      - Launching a Compute Engine instance with custom network configuration (e.g., internal-only IP address, Google private access, static external and private IP address, network tags)
      - Creating ingress and egress firewall rules for a VPC (e.g., IP subnets, network tags, service accounts)
      - Creating a VPN between a Google VPC and an external network using Cloud VPN
      - Creating a load balancer to distribute application network traffic to an application (e.g., Global HTTP(S) load balancer, Global SSL Proxy load balancer, Global TCP Proxy load balancer, regional network load balancer, regional internal load balancer)
    - #### 3.6 Deploying a solution using Cloud Marketplace. Tasks include:
      - Browsing the Cloud Marketplace catalog and viewing solution details
      - Deploying a Cloud Marketplace solution
    - #### 3.7 Implementing resources via infrastructure as code. Tasks include:
      - Building infrastructure via Cloud Foundation Toolkit templates and implementing best practices
      - Installing and configuring Config Connector in Google Kubernetes Engine to create, update, delete, and secure resources.
