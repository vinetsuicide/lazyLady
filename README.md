# lazyLady 🍷

Lazy Lady Security Scanner 


Lazy Lady is a simple security scanner script written in Python. It automates the process of gathering information and performing various security scans on a target. It utilizes popular tools such as whois, nslookup, nmap, nikto, gobuster, wpscan, and xsstrike to provide comprehensive security assessments.
(you can change some parameters for yourself)👀

Features

    Target Selection: Enter the target URL or IP address to perform the security scans.
    Scan Modes: Choose between two scan modes: Safe Scan or Aggressive Scan.
    Output Organization: The script creates a timestamped output directory to store the scan results.
    Tool Installation: Automatically installs required tools if they are not already installed.
    API Token Support: Prompt for a Wpscan API Token before executing the wpscan command.
    Loading Bar: Displays a loading bar to indicate the progress of the scanning process.

=====================================================================================================

    Usage

    Clone the repository: git clone https://github.com/your-username/lazy-lady.git
    
    Navigate to the project directory: cd lazy-lady
    
    Install the required dependencies: pip install -r requirements.txt
    
    Run the script: python lazy_lady.py
    
    Enter the target to scan when prompted.
    
    Choose the scan mode (Safe Scan or Aggressive Scan).
    
    If using the wpscan tool, enter your Wpscan API Token when prompted.(Please get a token for wpscan)
    
    Sit back and relax while the script performs the security scans. ☕
    Once the scanning is completed, the scan results will be saved in a timestamped directory.
    Review the output files generated by each security tool in the respective directory.
    




