This is task #2 "SIEM Configuration" in "Uneeq Interns" internship.

I wrote this query on splunk search
-----------------------------------------------------------
index="task2index" udp/* sourcetype="Firewall Logs (LOCAL)"
 | stats count by dstport
-----------------------------------------------------------
from the above query, i exctracted and detected the DoS anomaly from the firewall logs and then exported a report.
