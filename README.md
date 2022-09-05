# Associate Cloud Engineer Preparation Kit

<p align="justify"> An Associate Cloud Engineer deploys and secures applications and infrastructure, monitors operations of multiple projects, and maintains enterprise solutions to ensure that they meet target performance metrics. This individual has experience working with public clouds and on-premises solutions. They are able to use Google Cloud Console and the command-line interface to perform common platform-based tasks to maintain and scale one or more deployed solutions that leverage Google-managed or self-managed services on Google Cloud.</p>

### Check [Here](https://medium.com/@kp-the-great/how-i-cracked-gcp-associate-cloud-engineer-certification-successfully-just-in-12-days-e592ef771eba). I have shared my plan & strategies which I followed to ace the ACE just in 12 days.

---

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

- ### Section 4. Ensuring successful operation of a cloud solution
    - #### 4.1 Managing Compute Engine resources. Tasks include:
      - Managing a single VM instance (e.g., start, stop, edit configuration, or delete an instance)
      - Remotely connecting to the instance
      - Attaching a GPU to a new instance and installing necessary dependencies
      - Viewing current running VM inventory (instance IDs, details)
      - Working with snapshots (e.g., create a snapshot from a VM, view snapshots, delete a snapshot)
      - Working with images (e.g., create an image from a VM or a snapshot, view images, delete an image)
      - Working with instance groups (e.g., set autoscaling parameters, assign instance template, create an instance template, remove instance group)
      - Working with management interfaces (e.g., Cloud Console, Cloud Shell, Cloud SDK)
    - #### 4.2 Managing Google Kubernetes Engine resources. Tasks include:
      - Viewing current running cluster inventory (nodes, pods, services)
      - Browsing Docker images and viewing their details in the Artifact Registry
      - Working with node pools (e.g., add, edit, or remove a node pool)
      - Working with pods (e.g., add, edit, or remove pods)
      - Working with services (e.g., add, edit, or remove a service)
      - Working with stateful applications (e.g. persistent volumes, stateful sets)
      - Managing Horizontal and Vertical autoscaling configurations
      - Working with management interfaces (e.g., Cloud Console, Cloud Shell, Cloud SDK, kubectl)
    - #### 4.3 Managing Cloud Run resources. Tasks include:
      - Adjusting application traffic-splitting parameters
      - Setting scaling parameters for autoscaling instances
      - Determining whether to run Cloud Run (fully managed) or Cloud Run for Anthos
    - #### 4.4 Managing storage and database solutions. Tasks include:
      - Managing and securing objects in and between Cloud Storage buckets
      - Setting object life cycle management policies for Cloud Storage buckets
      - Executing queries to retrieve data from data instances (e.g., Cloud SQL, BigQuery, Cloud Spanner, Datastore, Cloud Bigtable)
      - Estimating costs of data storage resources
      - Backing up and restoring database instances (e.g., Cloud SQL, Datastore)
      - Reviewing job status in Dataproc, Dataflow, or BigQuery
    - #### 4.5 Managing networking resources. Tasks include:
      - Adding a subnet to an existing VPC
      - Expanding a subnet to have more IP addresses
      - Reserving static external or internal IP addresses
      - Working with CloudDNS, CloudNAT, Load Balancers and firewall rules
    - #### 4.6 Monitoring and logging. Tasks include:
      - Creating Cloud Monitoring alerts based on resource metrics
      - Creating and ingesting Cloud Monitoring custom metrics (e.g., from applications or logs)
      - Configuring log sinks to export logs to external systems (e.g., on-premises or BigQuery)
      - Configuring log routers
      - Viewing and filtering logs in Cloud Logging
      - Viewing specific log message details in Cloud Logging
      - Using cloud diagnostics to research an application issue (e.g., viewing Cloud Trace data, using Cloud Debug to view an application point-in-time)
      - Viewing Google Cloud status

- ### Section 5. Configuring access and security
    - #### 5.1 Managing Identity and Access Management (IAM). Tasks include:
      - Viewing IAM policies
      - Creating IAM policies
      - Managing the various role types and defining custom IAM roles (e.g., primitive, predefined and custom)
    - #### 5.2 Managing service accounts. Tasks include:
      - Creating service accounts
      - Using service accounts in IAM policies with minimum permissions
      - Assigning service accounts to resources
      - Managing IAM of a service account 
      - Managing service account impersonation
      - Creating and managing short-lived service account credentials
    - #### 5.3 Viewing audit logs

---
#### You can go through these courses on Udemy, they have covered the topics extremely well. 
1. [GCP Associate Cloud Engineer - Google Cloud Certification](https://www.udemy.com/course/google-cloud-certification-associate-cloud-engineer/)
2. [GCP Associate Cloud Engineer Certification : Google Cloud](https://www.udemy.com/course/google-cloud-gcp-associate-cloud-engineer-certification/)

---
### Other Resources :

| Sl. No. | Resource Name | Address |
| --- | ------------- |:-------------:|
| 01 | GCP Cheat Sheet  | [:link:](https://gist.github.com/pydevops/cffbd3c694d599c6ca18342d3625af97) |
| 02 | GCP Visual Notes  | [:link:](https://github.com/priyankavergadia/GCPSketchnote) |
| 03 | GCP Online Notes | [:link:](https://github.com/aceisScope/GCP_ACE_Notes/blob/master/README.md) |
| 04 | GCP Tips/Tricks | [:link:](https://github.com/murchie85/GCP-Associate-Cloud-Engineer#readme) |
| 05 | GCP All Resources | [:link:](https://github.com/kibablu/associate-cloud-engineer/blob/master/README.md) |








<br />

![GitHub last commit](https://img.shields.io/github/last-commit/Krushna-Prasad-Sahoo/GCP_AssociateCloudEngineer_PrepKit?style=for-the-badge)
