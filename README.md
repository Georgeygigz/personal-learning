# Cloud computing
## Fundamentals of cloud computing
### Basic of cloud computing
- Infrustructure as a service
- Platform as a service
- Software as a service

### Cloud computing the basic
#### What is it
- On demand computer resources delivered to you over the internet
#### Traits
 - **Elastic:** It can Scale up or down
 - **Metered:** On pay what to use
 - **Self service:** No or reduce of need for it engineers
#### Benefits
- First access to resources or services
- Only pay for you use
- No capital expenditure to get started
- Potential to eliminate the need for local IT staff
- Potential to lower costs
- Deploy What I need
- Allow IT staff to focus on business

#### Risk
- Placing your trust in the cloud provider
- Potential for data loss
- Potential for slow access to the data
- Potential questions related to regal
- Potential for loss of customization
- Potential for unknown cost

#### Forms of clod computing
- IaaS: accessing virtual machine, instance of physical computer 
- Saas: access application directly on the cloud eg gmail, office
- PaaS: Sql server, webserver

#### History
##### How was it called in the past
 - Centralized computing
 - Distributed Computing
 - Grid computing
 - Hosting
 - ASP
 - oN-DEMAND COMPUTING

#### Demo
- SaaS
### infrastructure as a service
#### What is virtualization
- Logical division of physical computing resources

#### What is virtual Machine
- Hypervisor you are able to run a Virtual Machine
- Virtual machine is a software based instance of a physical server where guest OS has access to emulated virtual hardware
- Virtual machine runs on top of hypervisor that is loaded on virtual server

#### What is a container 
- Software container
- Is OS level virtualization where the os Kernel provides isolated user spaces to run specific application
- Os is sliced up with isolated secure area to run specific applications
- Cloud computing utilizes containers
#### Private cloud,Hybrid cloud,Public cloud
- IaaS
- Hybrid you have connected Private to public
#### Virtualization vs Private cloud
##### Virtualization
- Provides scalability in elastic computing
- Load balancing
- Resource sharing and pooling
- Portability
- cloning
##### Private cloud
 - Provides the abstraction of the underlying infrastructure layer
 - Provides secure multi-tenancy
 - Self service portal
 - catalog of application
 - Chargeback/showback
 - Potential to burst to a hybrid cloud
#### IaaS Pricing models
- Pay for what to use
- Amazon Web services, Google compute engine Microsoft Azure
##### Pricing plans
- On demand
- Spot instances
- ReservedInstances
- Dedicated host
 
#### SLA(Service legal Agreements)
- Service level agreement

#### Migration to the cloud
- Migrating to cloud

###  Infrastructure as a Service networking
#### IaaS Networking option
##### Public networking
- Using public IP adress
##### Private networking
- Via VPN or dedicated connection

#### Virtual Private cloud Networking
- Private network that can be connected to my network
- One have control over

   ** Private Ip Address networking

   ** Routing

   ** Network access list
    
   ** Add VPN Connectivity

#### Connecting to the cloud with a virtual Private network
- Demo

### Storage in the cloud
#### Understanding IaaS Storage option
- Where file/ data is stored
##### Store data inside virtual machine
- Each VM has its own virtual storage

##### Store data outside the virtual machine
- Each VM can access external storage like block or object
- Object => perfect for unstructured data(Tradition file structure)
- Elastic Block Storage

#### Cloud file storage
##### Eg of cloud file storage solution
- Dropbox, microsoft1drive, Google drive

#### Object Storage
- Storage for unstructured data
- Eg, picture, video files, archival data
- Most popular object storage service in the word is Amazon S3(Simple Storage Service)
- Microsoft Azure
- Can tun object storage on premises, you can use C-E-P-H, SWIFT

#### Data Protection in the cloud
- use different cloud protection solution eg, CrashPlan, AWS Storage Gateway, Carbonite
  and Microsoft Azure Backup
- Disaster Recovery in the cloud 

### IaaS Security
#### Cloud security concern
- Concerned of availability and performance
- Is my data safe
- Who can see my data
- Can my data be modified

#### Encryption
- Process of converting information or data into a ciphertext which cannot be easily 
  understood by anyone without a key.

#### Compliance
- Eg of compliance is Laws, Policies, Rules, Standards, Governance
- 
#### Vulnerability and Mitigation
- Vulnerability, hole

### Comparing IaaS and PaaS
#### What is PaaS
- For developers
- Cloud services for developers who want to develop, run and Manage application in the public cloud
- Eg of IaaS, AWS Elastic BeanStalk, Microsoft Azure App Service, Heroku, Google App engine, Cloud Foundry
- IaaS for infrastructure people.

#### How do IaaS and PaaS 

IaaS
- Provided all Servers, Storage, and Networking
- Developers must install their own softwares such as web services, data servers etc

PaaS
- PaaS runs on top of IaaS, you need to purchase PaaS and not IaaS 
- Developers have access to already installed, web servers, database servers etc

#### Demo
- AWS Elastic bin

### SaaS cloud Solution
#### Benefits of SaaS cloud solutions
- No hardware to buy or install 
- No software to buy or install
- No Software to maintain or upgrade
- Only pay for what to use
#### Demo Office 365
#### Demo Google G Suite
#### Demo Sales Force.com