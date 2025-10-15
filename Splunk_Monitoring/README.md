# 📊 Splunk Monitoring Project

## 📜 Overview
This project focused on designing and implementing a security monitoring solution using **Splunk**.  
I learned how to collect, analyze, and visualize log data to identify potential security incidents and trends.  
The goal was to simulate a SIEM (Security Information and Event Management) workflow similar to what security analysts use in real-world environments.

## 🧰 Skills & Tools
- Splunk Enterprise
- Log ingestion and parsing
- Dashboard creation
- Search Processing Language (SPL)
- Basic security monitoring concepts

## 🧪 What I Did
- Installed and configured Splunk for CSV log ingestion  
- Collected and indexed system log data    
- Applied search queries to detect suspicious activity
  -  
- Audited and analyzed user activity through log data

## 📸 Screenshots

Here are screenshots from the Splunk monitoring project:

![Splunk Page 1](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page1.png)
- Collected CSV logs containing server speed test results.  Used **eval** to calculate a ratio to compare download to upload speeds and **table** to display in information in specific order.  This lead to the indication of a possilbe DoS attack.
![Splunk Page 2](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page2.png)
- Created a count of critical serverity vulnerabiliites from the nessus_log.csv from a specific destination IP in order to know if we are vulnerable.
![Splunk Page 3](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page3.png)
- Set up an alert for the critical vulnerabilities with the highest priority.  
![Splunk Page 3](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page4.png)
![Splunk Page 3](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page5.png)
- Created an alert after establishing some baselines from a separate brute force attack.    
![Splunk Page 3](https://raw.githubusercontent.com/e-salinas/Boot_Camp_Projects/main/Splunk_Monitoring/Images/SplunkProject_Page6.png)

## 🧠 What I Learned
- How to set up a SIEM solution for log analysis and monitoring  
- Writing SPL queries to detect specific security events  
- Building dashboards to visualize critical data in real time  
- Gaining insight into security visibility and alerting

## 🔗 Related Resources
- [Splunk Documentation](https://docs.splunk.com/)
- [Search Processing Language (SPL) Guide](https://docs.splunk.com/Documentation/Splunk/latest/SearchTutorial/WelcometotheSearchTutorial)
