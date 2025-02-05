# SUB DOMAIN ENUMERATION  
![image](./cover.jpg)

A Bash script to perform subdomain enumeration on a target domain using Kali Linux. This tool helps security professionals and enthusiasts discover subdomains of a given domain for reconnaissance and testing purposes.  

---

## **Prerequisites**  
Ensure the following requirements are met before running the script:  
- **Kali Linux** installed  
- Basic understanding of terminal commands  
- Utilities such as `unzip` and `bash` available  

---

## **Steps to Use the Script**  

### **Step 1: Download the Script**  
1. Go to the GitHub repository.  
2. Click on the green **Code** button and download the ZIP file to your local machine.

---

### **Step 2: Open the Terminal**  
1. Open a terminal window on your Kali Linux machine.  
2. Navigate to the **Downloads** directory:  
```bash
cd Downloads/
```
Step 3: Locate the ZIP File
List the contents of the Downloads directory to confirm the file name:

ls

Step 4: Unzip the File
Unzip the downloaded ZIP file using the following command:
```bash
unzip SUB-DOMAIN-ENUMERATION-main.zip
```

Step 5: Enter the Unzipped Folder
Navigate into the unzipped folder:
```bash
cd SUB-DOMAIN-ENUMERATION-main
```
Step 6: Grant Execute Permissions
To ensure the script can be executed, change its permissions:
```bash
chmod 755 sub_enum.sh
```
Step 7: Run the Subdomain Enumeration Script
Execute the script with the target domain as an argument:
```bash
./sub_enum.sh domain.com
```
Replace domain.com with the actual domain you want to scan (e.g., google.com, yahoo.com).
Example Usage
```bash
./sub_enum.sh google.com
```
Output
The script will output a list of subdomains associated with the target domain. This is useful for reconnaissance and vulnerability assessment.

Notes
Ethical Use Only: This script is for educational and research purposes. Ensure you have proper authorization before scanning any domain.
Use the results responsibly. Unauthorized scanning of domains may violate terms of service and laws.
Common Errors and Troubleshooting
"Permission Denied" Error: Ensure you granted execute permissions using chmod 755 sub_enum.sh.
"Command Not Found" Error: Verify that you are in the correct directory and that sub_enum.sh exists by running ls.
No Output: Ensure the target domain is valid and reachable.
Contact & Contribution
Feel free to fork the repository and submit pull requests for improvements. Report issues in the Issues tab of the repository.
