# Malware Detection Engineering with the Pyramid of Pain

## Objective
This project involved a simulated threat detection and response scenario using the "Pyramid of Pain" framework. The goal was to increase the adversary's cost of operation by identifying and mitigating various indicators of attack during a series of malware detection exercises.

## Skills Learned
- **Threat Intelligence and Detection:** Improved skills in identifying and mitigating threats by analyzing different indicators of compromise.
- **Security Tool Configuration:** Hands-on experience configuring security tools to detect and prevent the execution of malicious software.
- **Incident Response:** Enhanced ability to respond to security incidents through iterative purple-team scenarios.

## Tools Used
- **Security Information and Event Management (SIEM):** Utilized for monitoring and analyzing security-related data.
- **Endpoint Detection and Response (EDR):** Deployed to detect and respond to advanced threats.
- **Malware Analysis Sandboxes:** Used to analyze the behavior of malicious samples in a controlled environment.

## Steps
1. **Initial Setup:**
    - Configured PicoSecure's security tools to detect and prevent malware on a simulated internal workstation.
    - Reviewed the Pyramid of Pain framework and understood its application to increasing adversaries' operational costs.

2. **Detection Exercises:**
    - Detected and analyzed five different malware samples named `sample1.exe` to `sample5.exe`.
    - Successfully retrieved flags upon detection, verifying the effectiveness of the security setup.
    
    Flags obtained:
    - **Sample 1:** THM{f3cbf08151a11a6a331db9c6cf5f4fe4}
    - **Sample 2:** THM{2ff48a3421a938b388418be273f4806d}
    - **Sample 3:** THM{4eca9e2f61a19ecd5df34c788e7dce16}
    - **Sample 4:** THM{c956f455fc076aea829799c0876ee399}
    - **Sample 5:** THM{46b21c4410e47dc5729ceadef0fc722e}
    
3. **Final Challenge:**
    - Completed the final detection challenge involving Sphinx, receiving the final flag:
    - **Final Flag:** THM{c8951b2ad24bbcba60c16cf2c83d92c}

## Conclusion
This project reinforced the importance of structured threat detection and response processes. By leveraging the Pyramid of Pain, the detection and mitigation strategies proved effective, ultimately increasing the operational cost for adversaries and improving the security posture of the simulated environment.


## Screenshots
Here are some key screenshots from the project:

### Pyramid of Pain Overview
![Pyramid of Pain Overview](https://github.com/user-attachments/assets/7395dc79-2970-41cd-88dd-69a0a4e5ba36)

### SHA256 Hash Detection for Sample 1
![Sample 1](https://github.com/user-attachments/assets/f5c6df3c-2c71-42d2-a1d2-64d6cbdcbe97)

### Firewall Rule for Sample 2
![Sample 2](https://github.com/user-attachments/assets/a216aec5-5f03-41e6-b998-ad5f45eb3b8a)

### DNS Rule for Sample 3
![Sample 3](https://github.com/user-attachments/assets/9b465ad1-877f-4f3d-bf6f-22296b1a3bfe)

### Registery Change Detection Sigma Rule for Sample 4
![Sample 4](https://github.com/user-attachments/assets/f0b9daaa-d4bf-45cb-988f-1944a776f25d)

### Network Connections Sigma Rule for Sample 5
![Sample 5](https://github.com/user-attachments/assets/8b04c86e-3060-4467-b9d9-6a7937ec0f96)

### File Creation and Modification Rule for Final Attempt
![commands.log](https://github.com/user-attachments/assets/66aa575b-ea09-4fef-87c1-a4a77da3f158)
![Final Flag](https://github.com/user-attachments/assets/1ea2c21c-c517-4b4d-8a7d-70c93c9760fb)






