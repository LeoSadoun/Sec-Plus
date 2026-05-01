## Official Definition
A model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services).

## Key Characteristics/Technical Details
*   **Service Models:**
    *   **IaaS (Infrastructure as a Service):** Provides raw computing resources (VMs, storage, networks). Customer manages OS and up.
    *   **PaaS (Platform as a Service):** Provides a platform for developers to build/run apps. Customer manages code/data.
    *   **SaaS (Software as a Service):** Provides fully functional applications. Customer only manages configuration/users.
*   **Deployment Models:** Public, Private, Hybrid, Community.
*   **Shared Responsibility Model:** Clear division of security tasks between the provider (security *of* the cloud) and the customer (security *in* the cloud).
*   **Operational Expenditure (OpEx):** Pay-as-you-go pricing model.
*   **Elasticity/Scalability:** Ability to dynamically scale resources up or down.

## Real-World Examples
*   **IaaS:** AWS EC2, Azure VMs, Google Compute Engine.
*   **PaaS:** AWS Elastic Beanstalk, Heroku, Google App Engine.
*   **SaaS:** Microsoft 365, Salesforce, Gmail.
*   **Shared Responsibility:** AWS manages data center security; customer manages firewall rules (Security Groups).

## Exam Tips
*   **Keywords:** Shared Responsibility, Elasticity, OpEx, On-demand, Resource Pooling.
*   **Scenario:** Look for who is responsible for patching the OS (IaaS = Customer, PaaS/SaaS = Provider).
*   **Key Concept:** Understand that the provider is always responsible for physical security and the hypervisor.

## Relationship to other concepts
*   **Availability:** High availability and disaster recovery are core benefits of cloud architecture.
*   **Zero Trust:** Often integrated into cloud environments to verify every access request regardless of location.