# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
   Pillow version 9.4.0
3. Which CVE is linked to this vulnerability?
   CVE-2023-50447
5. What remediation steps do you suggest?
   Upgrade the Pillow package to the fixed version, 10.2.0, or newer. This can be done by updating the project's requirements.txt file to       Pillow>=10.2.0 and then rebuilding the Docker image.
### Vulnerability 2:
1. Which vulnerability are you addressing?
   PyYAML version 5.1
3. Which CVE is linked to this vulnerability?
   CVE-2020-1747
5. What remediation steps do you suggest?
   Upgrade the PyYAML package to the fixed version, 5.3.1, or newer. This can be done by updating the project's requirements.txt file to        PyYAML>=5.3.1 and then rebuilding the Docker image.
