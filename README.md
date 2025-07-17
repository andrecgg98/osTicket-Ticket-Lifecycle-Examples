<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>



---

## 1. Ticket Intake (Creation)

**A. User Submits a Ticket (Web Portal):**
1. User goes to your osTicket support portal (e.g., `http://<your-domain>/osticket`).
2. Clicks on **Open a New Ticket**.
3. Fills in required fields:
    - Name
    - Email address
    - Help Topic (e.g., Technical Support)
    - Subject and Message
    - Any custom fields/forms
4. Clicks **Create Ticket**.
5. User receives an on-screen confirmation and (optionally) an email acknowledgement.

**B. Ticket Submitted via Email (if enabled):**
1. User sends an email to the helpdesk address (e.g., support@yourdomain.com).
2. osTicket automatically converts the email into a ticket.
3. User receives an email confirmation.

---

## 2. Ticket Assignment

1. Staff log in to the Staff Control Panel: `http://<your-domain>/osticket/scp`.
2. Go to **Tickets** > **Open**.
3. Click on the new ticket to view details.
4. To assign the ticket, click **Assign** (top right).
5. Select a staff member or team and confirm.
6. The assigned staff member receives a notification.

---

## 3. Ticket Acknowledgement & Initial Response

1. Assigned staff reviews the ticket details and any attachments.
2. Staff clicks **Post Reply**.
3. Types a response to the user.
4. Optionally, sets the ticket status (e.g., Open, Answered, Pending).
5. Clicks **Post Reply**.
6. User receives the staff reply via email and/or web portal.

---

## 4. Ticket Follow-Up (Correspondence)

- **User replies:**  
  1. User can reply to the ticket via email or by logging into the portal.
  2. osTicket attaches the reply to the existing ticket.
  3. Assigned staff are notified of the new response.

- **Staff replies:**  
  1. Staff logs into the admin panel.
  2. Opens the ticket and posts further replies or internal notes as necessary.

- **Internal Notes:**  
  1. Staff can add internal notes (not visible to users) to document troubleshooting or decisions.
  2. Click **Post Internal Note**, type the note, and save.

---

## 5. Ticket Status Updates & Escalation

1. Staff can change ticket status (Open, Pending, Answered, Closed) at any time.
2. If the issue requires escalation:
    - Staff reassigns the ticket to a different team or department.
    - Optionally, adds internal notes for context.

---

## 6. Ticket Resolution

1. Once the issue is resolved, staff clicks **Post Reply** to notify the user of the resolution.
2. Staff sets the ticket status to **Closed** (or the equivalent in your system).
3. User receives a resolution confirmation via email and/or portal.

---

## 7. Ticket Closure and Archiving

1. Closed tickets are moved to the **Closed** queue.
2. All ticket details, correspondence, and notes are retained for future reference.
3. Tickets can be searched, exported, or reported on as needed.

---

## 8. (Optional) User Feedback

- If feedback is enabled, user may receive a survey or rating request after ticket closure.

---

## Summary Table

| Step          | Responsible Party | Action(s) Taken                           |
|---------------|------------------|-------------------------------------------|
| Intake        | User / System    | Ticket created via web/email/API          |
| Assignment    | Staff            | Ticket assigned to team or agent          |
| Acknowledgement | Staff          | Initial response sent to user             |
| Follow-Up     | User/Staff       | Replies, notes, further information       |
| Status Update | Staff            | Status changed, escalated if needed       |
| Resolution    | Staff            | Solution delivered, ticket closed         |
| Closure       | System/Staff     | Ticket archived, can be reported/exported |
| Feedback      | User/System      | (Optional) User feedback collected        |

---

**References:**
- [osTicket User Documentation](https://docs.osticket.com/)
- [osTicket Forums](https://forum.osticket.com/)

---
You have now completed a literal, step-by-step osTicket ticket lifecycle from intake through resolution!
