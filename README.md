##Cyber-Shield-Password-Evaluator 🛡️
Cyber-Shield-Password-Evaluator is a generative AI-powered security tool developed on the Amazon PartyRock platform. Unlike traditional password testers that rely solely on character counts, this application uses LLMs to simulate a "Professional Hacker" persona to identify deep-seated vulnerabilities in password construction and provide actionable hardening strategies.

📱 ##Interface Overview
As seen in the application interface (image_83f074.png), the tool is divided into four critical functional blocks:

Test Password Input: A dedicated field for users to enter potential credentials for evaluation.

Attacker Profile Configuration: A unique feature that allows the AI to shift its analysis perspective based on a specific threat actor (e.g., "Professional Hacker").

Vulnerability Analysis: A dynamic window where the AI generates a detailed breakdown of security flaws found in the input.

Hardening Recommendations: A specialized output area providing specific steps to secure the evaluated password.

🛠️ ##Technical Workflow
The application does not just calculate entropy; it follows a cybersecurity threat-modeling workflow:

Persona Simulation: The AI adopts a professional attacker's mindset to look for human-predictable patterns, common substitutions (leetspeak), and dictionary vulnerabilities.

Pattern Recognition: It identifies sequential keys, name-based strings, and common date formats.

Actionable Intelligence: Rather than just a "Weak/Strong" score, it delivers "Hardening Recommendations" to guide the user toward better credential hygiene.

🚀 ##Deployment & Usage
This app was built using Amazon PartyRock's integrated data analysis and LLM orchestration features. It serves as a proof-of-concept for how generative AI can be applied to automated security auditing and user education.

##How to use:
Navigate to the app on the PartyRock platform.

Select or define an Attacker Profile.

Enter a password in the Test Password field.

Review the Vulnerability Analysis and apply the Hardening Recommendations.

🛡️ ##Learning Objectives
This project was developed as part of a technical portfolio to demonstrate:

AI Implementation: Utilizing AWS generative AI tools for practical security solutions.

Cybersecurity Analysis: Understanding and simulating real-world attacker methodologies.

Documentation: Presenting technical workflows and UIs for professional review.
