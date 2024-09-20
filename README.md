This is task #2 "SIEM Configuration" in "Uneeq Interns" internship.

I wrote this query on splunk search
-----------------------------------------------------------
index="task2index" udp/* sourcetype="Firewall Logs (LOCAL)"
 | stats count by dstport
-----------------------------------------------------------

![image](https://github.com/user-attachments/assets/f6813b7e-1ebb-4ce4-a0a4-074ae102cbcf)



![Screenshot 2024-09-20 184133](https://github.com/user-attachments/assets/f2f5bae7-48ed-48ab-bd3d-8ac1ffad9a15)




From the above query, i exctracted and detected the DoS anomaly from the firewall logs and then exported a report.
