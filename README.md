# cloud-security-lab-ec2-ssrf-imds

The lab demonstrates how SSRF can be leveraged to access IMDS, obtain temporary AWS credentials, and enumerate cloud resources within the scope of assigned permissions. The work is performed entirely in a **sandboxed CloudGoat environment** for educational purposes.

## Objectives
By completing this lab, the following learning objectives were achieved:

- Validate an SSRF vector in a parameterized HTTP endpoint
- Demonstrate why **IMDSv1** is dangerous and how **IMDSv2** mitigates risk
- Safely retrieve and use **temporary IAM credentials** from IMDS
- Enumerate AWS resources using least-privilege principles
- Assess blast radius and business impact
- Propose **defense-in-depth mitigations** across application, host, IAM, network, and detection layers
