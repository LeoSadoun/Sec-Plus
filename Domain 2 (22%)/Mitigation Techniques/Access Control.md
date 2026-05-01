## Official Definition
* **Access Control:** The process of granting or denying specific requests to obtain and use information and related information processing services.

## Key Characteristics/Technical Details
* **RBAC (Role-Based Access Control):** Access is based on the user's role in the organization (e.g., Manager, HR, IT).
* **ABAC (Attribute-Based Access Control):** Access is based on attributes (e.g., user department, time of day, location, device health).
* **MAC (Mandatory Access Control):** Access is based on security labels (e.g., Secret, Top Secret); used in high-security environments.
* **DAC (Discretionary Access Control):** The owner of the data decides who has access.
* **Least Privilege:** Giving users only the minimum level of access required to perform their job.
* **Privileged Access Management (PAM):** Specialized tools for managing and monitoring administrative accounts.

## Real-World Examples
* **Active Directory Group Policy:** Using security groups to assign folder permissions based on departmental roles (RBAC).
* **Cloud IAM Policies:** Using JSON policies in AWS or Azure to define precisely what an identity can do (often ABAC-like).

## Exam Tips
* **Keywords:** Least Privilege, RBAC, ABAC, MAC, DAC, IAM, PAM.
* **Scenario:** If the question asks how to "prevent an employee from seeing data they don't need," the answer is Least Privilege or RBAC.

## Relationship to other concepts
* **Identity and Access Management:** Access control is the "Authorization" part of IAM.
* **Insider Threats:** One of the most effective ways to mitigate the impact of a malicious insider.
