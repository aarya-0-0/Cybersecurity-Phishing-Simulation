# Cybersecurity-Phishing-Simulation
This repository showcases a simulated phishing workflow using Zphisher to generate deceptive login links and VirusTotal to analyze their properties. The project demonstrates how phishing links can mimic legitimate websites by comparing visual and structural similarities in a browser, helping raise awareness of digital threats. 

Objectives: This project tries to demonstrate phishing attack attack is carried out by simulating it in a virtual and safe environment for educational purposes.

Tools Used:
-Kali Linux
-Zphisher
-Browser
-Virustotal
-VMware workstation

Skills Demonstrated:
- Ethical hacking methodology
- Red team simulation
- Understanding user behavior
- Security testing practices
- Linux command line usage
- VMware workstation

Observation:

Phase 1: Simulate the attack 
-Accessed zphisher using VMware kali [picture no 1]
-Generated the link for facebook login page using zphisher[picture no 3]
-Copy and paste the link in the email if required for further testing

   **note: I have not used a sample mail but used virustotal to analyze the link

Phase 2: Analyze the link
-We can view the url in virustotal as I have shown in the image 6 of this project 
-Observe that the link gives us insecure result with clearly specifies phishing

Phase 3: Analyze the link
-We can observe the link generated using the zphisher, in the browser 
-It is a total mimic of the real facebook login page[picture no 4]
-When I entered my fake credentials in it [picture no 5], it shows some kind of error cause that is not the true login page
-The credentials entered through that page is saved on the attacker's computer under the directory name auth which contains both the IP and the username + pass of the victim
[Picture no 7]

Conclusion: Phishing is a type of social engineering attack whose main cause is human ignorance and unawareness. This project tries to give an idea on how email phishing attack is carried out. 

------------------------------------------------------------

Author's note: It is important to check any link before opening it. Virustotal is a free service which assits in link analysis.



