## Official Definition
* **Virtualization Vulnerability:** A weakness in the virtualization layer (hypervisor) or virtual machine (VM) configuration that allows an attacker to bypass isolation or gain unauthorized access to the host or other VMs.

## Key Characteristics/Technical Details
* **VM Escape:** An attack where an attacker breaks out of a virtual machine and gains access to the underlying hypervisor or host operating system.
* **VM Sprawl:** The uncontrolled growth of virtual machines, making it difficult to maintain security patches and visibility.
* **VM Bolting / Data Remanence:** Residual data from a previously deleted VM that can be accessed by a new VM assigned the same physical memory or disk space.
* **Hypervisor Vulnerabilities:** Flaws in the software that manages the VMs (e.g., VMware, Hyper-V, KVM) that could compromise all hosted VMs.
* **Insecure VM Templates:** Using pre-configured VM images that contain vulnerabilities or default credentials.

## Real-World Examples
* **Venom (2015):** A critical vulnerability in the virtual floppy disk controller used by many hypervisors (QEMU, Xen, KVM) that allowed for VM escape.
* **Cloudborne:** A vulnerability that allowed attackers to plant malicious firmware on a bare-metal server in a cloud environment that could persist even after the server was reassigned to a new customer.

## Exam Tips
* **Keywords:** VM Escape, Hypervisor, Sprawl, Sandboxing, Guest-to-Host, Snapshots.
* **Scenario:** If an attacker "moves from one virtual machine to another" or "compromises the host via a guest," it's a virtualization vulnerability.

## Relationship to other concepts
* **Cloud-specific Vulnerabilities:** Virtualization is the foundation of cloud computing.
* **Mitigation:** Hypervisor patching, strong VM isolation, and regular auditing of VM usage (to prevent sprawl).
