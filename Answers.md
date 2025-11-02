# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below. 

## Vulernability Remediation:
### Vulnerability 1: 
1. Which package or library are you addressing?
**I am addressing the Pillow package, version 9.4.0**

2. Which CVE is linked to this vulnerability?
**CVE-2023-50447 is linked to this vulnerability.**

3. What remediation steps do you suggest?
**I would upgrade the Pillow package by updating the dependency in the requirements.txt file from 9.4.0 to a more recent version. Then I would rebuild the container.** 
**You can use pip install --upgrade Pillow.**

### Vulnerability 2:
1. Which vulnerability are you addressing?
**I am addressing the Werkzeug library, version 2.1.2.**

2. Which CVE is linked to this vulnerability?
**CVE-2024-34069 is linked to this**

3. What remediation steps do you suggest? 
**Update the library to the latest version to 3.0.3 or later because the vulnerability is ficed in 3.0.3. I would update the dependency in the requirements.txt file. Then, I would also rebuild the container and see if the vulnerability scan verifies that the vulnerability is no longer there.**