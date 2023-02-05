# Outage Postmortem
# Issue Summary
Duration: February 2 nd, 2023, 7:00 AM to 7:20 AM  East African Time
Impact: During this time, it was reported that our master web server(web-01) was encountering 500 error, indicating a problem with the server-side code.
Root Cause: The error report shows that the issue was caused by a memory leak in the web application's code, which was causing the server to run out of memory and crash.

# Timeline
7:00 AM: Issue detected - A customer complained about not being able to access the website.
7:03 AM: Investigation started - The operations team was alerted and started to investigate the issue.
7:10 AM: Misleading investigation - The team initially assumed the issue was with the website's server and started debugging that, but it was not the root cause.
7:12 AM: Up reporting - The team reported the issue to the web Admensitrator  after realizing it was memory issue.
7:15 AM: Resolution - the issue by increasing the server's memory allocation and optimizing the code to reduce memory usage.
Root cause and resolution
The root cause of the issue was a memory leak in the web application's code, which was causing the server to run out of memory and crash. The website administrator was able to resolve the issue by increasing the server's memory allocation and optimizing the code to reduce memory usage.

# Corrective and preventative measures
Monitor server resource utilization: Regularly monitor the server's resource utilization, such as CPU, memory, and disk usage, to identify any potential issues before they cause problems.

Keep software and systems up-to-date: Regularly update the server's operating system, web server software, and any other applications or systems to ensure they are secure and free from vulnerabilities.

Conduct regular backups: Regularly back up critical data and systems to minimize data loss in the event of a server failure.

Implement monitoring for incoming traffic to the website to quickly detect any similar issues in the future
# Advanced : A  Humor to Lighten the Mood
our customers satisfaction is  our number one priority. We really understand that outages can be a  pain. But we would like to assure you that  our engineers ,programmers and the whole team are  always working hard to prevent them from happening. 
