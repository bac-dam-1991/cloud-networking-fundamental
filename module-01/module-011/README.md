# 1.1 Understanding Cloud Computing

## Objective
To introduce participants to the fundamentals of cloud computing, including its definition, key characteristics, service models, and deployment models. This section aims to lay the groundwork for understanding how cloud computing forms the backbone of modern cloud networking.

## Definitions and Basics

### What is Cloud Computing?
Cloud computing is a paradigm that allows on-demand access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort.

### Characteristics of Cloud Computing
- **On-demand self-service:** Users can provision resources without requiring human interaction with the service provider.
- **Broad network access:** Capabilities are available over the network and accessed through standard mechanisms.
- **Resource pooling:** The provider’s computing resources are pooled to serve multiple consumers.
- **Rapid elasticity:** Capabilities can be elastically provisioned and released to scale rapidly outward and inward with demand.
- **Measured service:** Cloud systems automatically control and optimize resource use by leveraging a metering capability.

## Cloud Service Models

### Infrastructure as a Service (IaaS)
Provides virtualized computing resources over the internet. Users get an infrastructure on which they can install any software, including operating systems and applications.

Amazon EC2 (Elastic Compute Cloud) is an example of Infrastructure as a Service (IaaS). EC2 provides scalable computing capacity in the Amazon Web Services (AWS) cloud. It allows users to rent virtual computers on which they can run their own computer applications. EC2 offers control over the physical hardware that runs the compute instance, albeit in a virtual environment, which is a characteristic feature of IaaS. Users are responsible for managing the operating system, applications, and network configurations, distinguishing it from PaaS and SaaS, where such management is handled by the provider to a greater extent.

### Platform as a Service (PaaS)
Offers hardware and software tools over the internet, typically for application development. PaaS provides a platform allowing customers to develop, run, and manage applications.

An example of Platform as a Service (PaaS) is Heroku. Heroku is a cloud platform that provides the infrastructure, operating systems, and runtime environments to allow developers to deploy, manage, and scale applications without the complexities of handling the underlying hardware or software layers. It supports multiple programming languages and takes care of much of the web hosting and server management tasks, making it easier for developers to focus on building their applications. Heroku abstracts away the infrastructure, allowing developers to push updates, manage scaling, and handle other aspects of web app deployment through simple commands, embodying the PaaS model's key benefits of simplicity, scalability, and efficiency.

### Software as a Service (SaaS)
Delivers software applications over the internet, on-demand, and typically on a subscription basis. With SaaS, cloud providers host and manage the software application and underlying infrastructure.

An example of Software as a Service (SaaS) is Google Workspace (formerly G Suite). Google Workspace offers a collection of cloud-based productivity and collaboration tools, including Gmail for email, Google Drive for file storage, Google Docs and Sheets for document creation and management, Google Meet for video conferencing, and many more. All these applications are delivered over the internet, with users able to access them through a web browser without the need to install or manage any software on their local devices. This service model allows businesses and individuals to use a suite of powerful tools on a subscription basis, emphasizing the SaaS characteristics of on-demand availability, scalability, and the outsourcing of infrastructure and software maintenance tasks to the cloud provider.

## Deployment Models

### Public Cloud
Services are delivered over the public internet and available to anyone who wants to purchase them. Resources like servers and storage are owned and operated by a third-party cloud service provider.

### Private Cloud
The cloud infrastructure is exclusively used by a single organization. It can be located on-site or off-site and managed by the organization or a third party.

### Hybrid Cloud
A combination of public and private clouds, bound together by technology that allows data and applications to be shared between them. It gives businesses greater flexibility and more deployment options.

### Community Cloud
The cloud infrastructure is shared among several organizations from a specific community with common concerns (security, compliance, jurisdiction, etc.). It can be managed by the organizations or a third party.
