# FUTURE_CS_03
🛡️ API Security Risk Analysis
📋 Project Overview
This project demonstrates a professional API Security Risk Analysis conducted on a public REST API. As an aspirant software developer, I performed a read-only security audit to identify common vulnerabilities that threaten modern SaaS applications, such as unauthorized data manipulation and excessive sensitive data exposure.

🎯 Objective

Identify insecure API endpoints: Detecting routes that allow unauthorized actions.


Analyze Data Exposure: Assessing if API responses return more information than necessary for the client.


Inspect Infrastructure: Identifying server fingerprinting through HTTP headers.


Provide Remediation: Suggesting clear, developer-friendly fixes for each identified risk.

🛠️ Tools Used

Postman: For executing and inspecting RESTful API requests (GET, DELETE).


JSONPlaceholder API: The target environment used for security testing and documentation.


MS Word / PDF: Used to compile the official technical report for stakeholders.

🕵️ Analysis Methodology

Endpoint Testing: Utilized Postman to test the behavior of state-changing methods (DELETE) without authentication tokens to verify access control gaps.


Payload Inspection: Analyzed JSON response bodies to identify the leakage of Personally Identifiable Information (PII) like geolocation and private phone numbers.


Header Reconnaissance: Inspected response headers for server fingerprinting and verified the presence of rate-limiting configurations.


Impact Assessment: Classified each finding based on its potential business impact and mapped out remediation strategies.

📂 Deliverables

API Security Risk Analysis Report.pdf: The full professional audit report.


Screenshots: Real evidence of the Postman requests and server responses.


API DELETE Proof 


API GET Response 


API Headers Analysis
