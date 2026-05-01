## Official Definition
* **Configuration Enforcement:** The use of automated tools and policies to ensure that systems are configured according to a defined security baseline and that unauthorized changes are prevented or detected.

## Key Characteristics/Technical Details
* **Security Baselines:** A set of minimum security settings that must be applied to a system (e.g., CIS Benchmarks).
* **Group Policy Objects (GPO):** A Windows feature used to centrally manage and enforce configurations across a domain.
* **Infrastructure as Code (IaC):** Using code to define and deploy infrastructure, ensuring consistent and repeatable configurations.
* **Desired State Configuration (DSC):** A management platform that allows you to manage IT infrastructure with configuration as code.
* **Compliance Scanning:** Regularly checking systems against a baseline to identify "configuration drift."

## Real-World Examples
* **CIS Benchmarks:** A set of globally recognized best practices for securing IT systems and data.
* **Terraform / Ansible:** Tools used to enforce configuration by defining the "final state" of a server or cloud environment.

## Exam Tips
* **Keywords:** Baseline, GPO, Configuration Drift, IaC, Automated enforcement, Benchmarks.
* **Scenario:** If the goal is to "ensure all servers have the same security settings" or "prevent users from changing desktop wallpapers," use configuration enforcement.

## Relationship to other concepts
* **Hardening:** Configuration enforcement is the mechanism used to maintain a hardened state.
* **Shadow IT:** Helps detect unsanctioned systems that do not meet the corporate baseline.
