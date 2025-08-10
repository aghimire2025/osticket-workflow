<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>
<h1>osTicket Ticket Management and Workflow Simulation</h1>
This project involved handling tickets from creation to resolution using end-user and agent accounts. It included configuring department structures, assigning SLAs, testing access control, and walking through real-life support ticket workflows for incident resolution and technical team collaboration.<br />

<h2>Environments and Technologies Used</h2>

- osTicket Admin Panel (http://localhost/osTicket/scp/login.php)
- osTicket End User Portal (http://localhost/osTicket)
- Web Browser Interface
- Role-Based Access Controls (RBAC)
- Service Level Agreement (SLA) Configuration
- Ticket Workflow & Lifecycle Features


<h2>Operating Systems Used </h2>

- Windows 11 Pro </b> (21H2)

<h2>List of Prerequisites</h2>

- Understanding of Role-Based Access Control (RBAC) in osTicket
- Knowledge of ticket workflow and lifecycle features
- Predefined ticket categories and help topics for classification <br />

<h2>Key Tasks Performed:</h2>
<p>

•  Promoted SysAdmins to a Top-Level Department and permanently deleted the Maintenance department to streamline and simplify the organizational structure within osTicket
<br />
<p>
 <img width="608" height="433" alt="image" src="https://github.com/user-attachments/assets/91581f83-36a6-404f-b1e3-3d36bb72a31c" />
</p>
<p>
<b>• Mobile/Online Banking Outage </b><br /><br />
Karen has created a ticket titled "Entire mobile/online banking system is down", reporting that her employees are reporting that the customers are no longer able to access the online banking portal. The ones who can occasionally access it are unable to log in. This was first reviewed by John Doe, IT support. John could not access it because it is restricted due to the department's scope. John was, however, able to set the SLA plan to Sev-A for the ticket with a note "wide impact, customers unable to do online banking," and assigned it to the Online Banking department. This ticket was resolved by Jane Doe (sysAdmin), who discovered that the issue is caused by a recent update. Jane reverted the system to the previous version, notified the vendor, and then waited for the system to be fixed. The online banking was then up and running.
<br />
<p>
 <img width="784" height="773" alt="image" src="https://github.com/user-attachments/assets/05ad3d22-7edf-497d-995b-1b3f3540ffb8" />
 <img width="975" height="116" alt="image" src="https://github.com/user-attachments/assets/bc3fa704-48b3-42d6-a5cb-3d3ba2493b23" />
</p>
<b>• Adobe Upgrade Request (Accounting) </b><br /><br />
Ken has created a ticket titled "accounting department needs Adobe upgrade, broken", reporting that many employees in the accounting department can't use their Adobe Acrobat. John Doe assigned this ticket to Support, reviewed it, and set the SLA plan to Sev-C for this ticket. This ticket was resolved by John as he restarted the computers of the affected employees, and it fixed the issue. John closed the ticket with a note stating that "restarting has fixed the issue."
<br />
<p>
<img width="817" height="391" alt="image" src="https://github.com/user-attachments/assets/4cc98c22-116e-4e8b-97a6-fc560efaa964" />
<img width="975" height="104" alt="image" src="https://github.com/user-attachments/assets/900adf74-a4cf-454e-8c3f-91adb55885c5" />
</p>
<b>• CFO’s Laptop Won’t Turn On </b><br /><br />
Karen has created a ticket stating the CFO is unable to use his laptop despite pressing the power button. Again, John Doe assigned this ticket to Support, reviewed it, and set the SLA plan to Sev-B. This was again resolved by John Doe when he went to check the CFO's laptop and found out the charger was not functional anymore. He brought a new charger and handed it to the CFO. After charging the computer CFO was able to turn on his computer and work with it. The ticket was closed.
<br />
<p>
<img width="975" height="460" alt="image" src="https://github.com/user-attachments/assets/4baabde8-d262-4f9e-857d-b44aa0a7afda" />
<img width="975" height="103" alt="image" src="https://github.com/user-attachments/assets/bb631209-32d2-4257-b1bf-c427387c1ca9" />
</p>
<br />
<p>
<b>Ticket Visibility & Access Testing</b> <br />

  - Assigned all tickets to their respective SLA and departments
  - Confirmed loss of access for John to SysAdmins tickets
  - Updated admin panel settings to grant John view-only access
  - Verified escalated ticket visibility with restricted editing rights
 </p>
 <p>
<b>Skills Demonstrated</b> <br />

  - End-to-end ticket lifecycle management
  - SLA assignment and priority classification
  - SLA design and priority classification
  - Department-based access control testing
  - Understanding escalation, visibility, and ticket ownership

</p>
<br />
<p>
<b>Challenges & Solutions</b> <br />
<b>Challenge:</b> Restricted agent access after SLA reassignment <br />
<b>Solution:</b> Used Admin Panel to grant view-access for restricted departments, validated limited interaction scope
</p>
<br />
<p>
<b>Results & Takeaways</b> <br />

  - Simulated real-world support workflows from ticket intake to closure
  - Validated the importance of ticket documentation for tracking and metrics
  - Demonstrated that in professional systems, email integration can notify users of ticket updates and allow them to respond directly
  - Reinforced the importance of creating tickets for all support actions, even informal or spontaneous ones, for performance tracking
 </p>


