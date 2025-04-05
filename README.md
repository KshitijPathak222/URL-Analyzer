Project Execution Details:

System Requirements:
OS: Windows 10 or above
RAM: 4GB minimum (8GB recommended)
Python: Version 3.8+

Packages to Install:
pip install requests
pip install whois
pip install tk

External Tools/Accounts Needed:
Google Safe Browsing API Key (Free tier available)
VirusTotal API Key (Sign up required)

Steps to Run the Tool:
Clone the repository or download the zip folder from GitHub.
Install the required packages using pip.
Open the main Python file and insert your API keys in the respective variables.
Run the Python script: python url_analysis_tool.py

Enter any URL into the GUI input field and click "Analyze URL" to see results.

Output:
A detailed report window that includes:
URL metadata (IP, WHOIS, Domain Age)
Threat detection flags
Final verdict: Safe or Malicious
Recommendations

Additional Notes:
Always keep your API keys confidential.
Use rate-limiting strategies to stay within free tier limits.
This Version of this Tool is working on a free Tier service with a limit of 50 requests a month
Regularly update the code to adapt to API changes or upgrades.
Logs are generated for debugging and maintaining analysis history.
