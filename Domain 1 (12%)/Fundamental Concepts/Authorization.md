## Official Definition
*   **Authorization:** The process of determining the specific resources an authenticated user is allowed to access and the operations they can perform (e.g., read, write, delete). It is the "What can you do?" phase of the AAA framework.

## Key Mechanisms/Tools
*   **Permissions/Rights:** File system permissions (NTFS, Linux permissions).
*   **Access Control Models:**
    *   **RBAC (Role-Based):** Based on job function (e.g., Manager, IT Admin).
    *   **ABAC (Attribute-Based):** Based on characteristics (e.g., time of day, location).
    *   **DAC (Discretionary):** Owner decides who has access.
    *   **MAC (Mandatory):** System-enforced labels (e.g., Secret, Top Secret).
*   **Principle of Least Privilege (PoLP):** Giving users only the minimum access needed to do their jobs.

## Real-World Examples
*   An employee having "Read" access to a project folder but not "Modify" or "Delete" access.
*   A user being able to log into the network but only during business hours (8 AM - 5 PM) via **ABAC**.
*   Using **Active Directory Group Policy** to grant a group of HR employees access to payroll software.

## Exam Tips
*   **Keyword:** "Permissions," "Privileges," "Rights," "Least Privilege."
*   **Scenario:** A user is promoted and their old permissions are removed while new ones are added. This is a management of Authorization.
*   **CIA vs. AAA:** Authorization is the second "A" in AAA. It relies on the identity verified during Authentication.

## Relationship to other concepts
*   **vs. Authentication:** You can be authenticated (the system knows who you are) but not authorized (you don't have permission to see the requested file).
*   **Implicit Deny:** The security principle where access is denied unless specifically granted.
