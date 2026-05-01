## Official Definition
The management and provisioning of infrastructure (networks, virtual machines, load balancers, and connection topology) through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools.

## Key Characteristics/Technical Details
*   **Automation:** Replaces manual configuration with scripts and templates.
*   **Consistency:** Eliminates "configuration drift" by ensuring all environments are identical.
*   **Version Control:** IaC files are stored in Git or other VCS, allowing for auditing, rolling back, and peer review.
*   **Idempotence:** The property where an operation can be applied multiple times without changing the result beyond the initial application.
*   **Immutable Infrastructure:** Instead of patching servers, new servers are deployed from updated IaC templates and old ones are destroyed.
*   **Tools:** Terraform, Ansible, CloudFormation, Chef, Puppet.

## Real-World Examples
*   **Terraform:** Deploying an entire VPC, including subnets and security groups, in AWS using a `.tf` file.
*   **Ansible Playbooks:** Automatically installing and configuring Nginx on 100 virtual machines simultaneously.
*   **CloudFormation:** AWS-native tool for defining resources in JSON or YAML.

## Exam Tips
*   **Keywords:** Automation, Configuration Drift, Idempotence, Version Control, Orchestration.
*   **Scenario:** If an organization wants to ensure their Dev, Test, and Prod environments are identical, IaC is the solution.
*   **Security Benefit:** Security "as code" allows for automated scanning of infrastructure templates for vulnerabilities before deployment.

## Relationship to other concepts
*   **DevSecOps:** IaC is a cornerstone of integrating security into the CI/CD pipeline.
*   **Change Management:** IaC simplifies change management by making infrastructure changes visible in code commits.
*   **Resilience:** Enables rapid reconstruction of entire environments from scratch in the event of a disaster.