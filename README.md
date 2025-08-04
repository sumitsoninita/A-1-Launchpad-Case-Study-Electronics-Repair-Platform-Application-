# A-1 Electronics Repair Service Platform 

Welcome to the A-1 Launchpad submission for **Streamlining Electronics Repair Services**. This Power BI + Google Workspace-enabled solution reimagines the complaint, repair, and dispatch lifecycle for electronics such as Energizers, Gate Motor Controllers, and Power Adapters—eliminating manual workflows, reducing TAT, and improving customer transparency.

---

## Project Highlights

- Created a unified **Web & Mobile Interface** (Figma Wireframes) for internal and external complaint registration.
- Designed a full **Service Flow**: From complaint logging to dispatch, with EPR handoffs and cost approval checkpoints.
- Developed a fully interactive **Power BI Dashboard** with complaint status, cost trends, and root cause analytics.
- Used Pareto & Fishbone Analysis to diagnose 80% of faults from 20% root issues.
- Integrated a **Chatbot** & **FAQ Module** to resolve customer queries in real time.
- Designed **Role-based Secure Access** for Admin, EPR, Service, and End Users using Google Authentication.

---

## Web App / Interface Wireframes

| Interface | Description |
|----------|-------------|
| Login Page | User enters ID & password with role-based access control |
| Complaint Form | Customer enters product, fault, purchase date & uploads photo |
| Complaint Tracker | Tracks ticket status: Submitted → Validated → Repair → Dispatch |
| Chatbot & FAQ | AI-based support for product use, warranty & general queries |
| Roles | Supports: `User`, `Service`, `EPR`, `Admin` roles via dropdown |




## App Highlights

><img width="1846" height="891" alt="image" src="https://github.com/user-attachments/assets/66c3a2ee-6a72-4e6f-bc1c-3d315b3aa8fc" />


## Key Visuals & Analytics

- **Pareto Analysis (80/20 Principle)**  
  Top 5 issues make up 100% of logged complaints:
  - Software Glitch (24)
  - Overheating (24)
  - Physical Damage (20)
  - Charging Fault (19)
  - Power Issue (13)

- **Product-Level RCA**
  - Gate Motor Controllers → Software & Thermal Issues
  - Power Adapters → High in 3 out of 5 issues
  - Energizers → Dominated by Charging Faults

- **Fishbone Analysis** (Man-Machine-Method-Material):
  - Root causes include poor soldering, faulty cables, inadequate QA, and lack of preventive maintenance.

- **Power BI Dashboard:**
  - Complaint Trends by Product Type
  - RCA Distribution
  - Complaint TAT (Turnaround Time)
  - Repair Cost Buckets (<₹400, ₹400–₹700, >₹700)
  - User-wise & Team-wise complaint resolution stats

---

## Tools & Stack Used

- Power BI Desktop & Service – Interactive dashboards, DAX KPIs, and RCA visuals
- Google Forms + Sheets – Complaint submission and live data logging
- Canva + Figma – Interface & Mobile Wireframes
- Google Apps Script – Chatbot & auto-email response
- GitHub + PDF Export – Final documentation and project hosting

---

## Project Objective

> Digitally transform the manual PDI and complaint-handling process into a secure, scalable, no-cost platform using free tools (Google ecosystem + Power BI) that:
- Minimizes repair turnaround time
- Reduces repeat complaints
- Improves customer satisfaction and feedback transparency
- Enables data-driven decision making for RCA and quality improvement

---

## Strategic Insights

- 48% of all complaints are due to Software Glitches & Overheating.
- Power Adapters are involved in 3 out of 5 major complaint categories—urgent redesign needed.
- Chatbot & FAQ modules deflect common queries, reducing service load.
- Component Quality SOPs and EPR training can resolve over 70% of recurring faults.

---

## Dummy_dataset_Used_for_analysis

><img width="883" height="675" alt="image" src="https://github.com/user-attachments/assets/815a50d4-81e3-40d3-8541-b5f92d7da4b6" />

## Dataset Headings

| Column                    | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------|
| Product Type              | The specific product (e.g., Energizer, Power Adapter).                      |
| Complaint Type            | The nature of the issue (e.g., Software Glitch, Overheating).              |
| Issue Severity            | The level of urgency or impact of the complaint.                           |
| Assigned To               | The individual or team responsible for the repair.                         |
| Complaint Status          | The current stage of the complaint (e.g., Submitted, Validated, Repair).   |
| Service Validation Outcome| The result of the initial service team assessment.                         |
| Dispatch Request Date     | The date a dispatch request was created.                                   |
| Received by EPR (Yes/No)  | Indicates if the complaint has been handed off to the EPR team.            |
| Estimated Repair Cost     | The projected cost for the repair.                                         |
| Approved (Y/N)            | Indicates if the repair cost has been approved.                            |
| Repair Completed Date     | The date the repair was finished.                                          |
| Final Dispatch Date       | The date the repaired item was dispatched.                                 |
| Resolution Summary        | A brief summary of how the issue was resolved.                             |
| TAT (Turnaround Time)     | The total time taken to resolve the complaint.                             |


---

## Special Thanks

Thanks to the A-1 Launchpad
