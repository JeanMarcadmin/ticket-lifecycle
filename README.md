<p align="center">
  <img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1 align="center">osTicket - Ticket Lifecycle Overview</h1>

Understanding the ticket lifecycle in osTicket is essential for efficient help desk operations. This guide outlines the journey of a support ticket from creation to resolution, including all key status changes and actions.

---

## 🔄 What is the Ticket Lifecycle?

The **Ticket Lifecycle** represents the stages a ticket passes through during its existence — from when it's opened by a user to when it's resolved and closed by an agent or admin.

---

## 🛤 Lifecycle Stages

### 1. 🎫 **New**
- **How it starts:** A user submits a ticket via the web form or email.
- **Status:** *Open*
- **Action Required:** Assigned to an agent or team.

---

### 2. 👨‍💻 **Assigned**
- **Status:** *Open*
- Ticket is manually or automatically assigned to a staff member or department.
- SLA timer starts (if configured).

---

### 3. 🕵️ **In Progress**
- Agent is actively working on the ticket.
- Internal notes or public replies may be added.
- May involve back-and-forth communication with the user.

---

### 4. 📥 **Awaiting Response (User/Third Party)**
- Agent replies and awaits user or vendor response.
- **Status:** May still be *Open*, or marked *Pending* using a custom status.

---

### 5. ✅ **Resolved**
- Issue is fixed.
- Ticket is marked as **Resolved**, but not yet closed — this gives the user a chance to confirm resolution.

---

### 6. 🔒 **Closed**
- Ticket is officially closed:
  - Automatically after a time period (if configured)
  - Manually by the agent/admin
- **Status:** *Closed*
- SLA stops tracking, ticket becomes read-only.

---

## 📌 Related Ticket Actions

| Action                | Description |
|-----------------------|-------------|
| **Assign**            | Assign to agent or department |
| **Transfer**          | Move to another department |
| **Post Reply**        | Sends response to the user |
| **Add Internal Note** | Adds non-public comment |
| **Merge Tickets**     | Combine duplicates |
| **Reopen**            | Move closed ticket back to open |

---

## 📊 Ticket Statuses in osTicket

osTicket uses these default statuses:

- `Open` – Unresolved and awaiting action
- `Answered` – Agent responded, waiting on user
- `Closed` – Resolved and finalized
- `Overdue` – SLA violated or user hasn’t responded

> You can customize or extend statuses via plugins or modifications.

---

## 🧠 Best Practices

- Always close resolved tickets to keep the system clean.
- Use SLAs to track response times.
- Use internal notes for documentation within the team.
- Enable email alerts for ticket activity to stay updated.

---

## 🖼 Sample Ticket Flow Diagram

*(Optional: You can add a diagram showing each step as a visual)*  
Would you like me to generate a flowchart image?

---

## ✅ Summary Checklist

- [x] New tickets are assigned promptly
- [x] Responses are documented
- [x] SLA plans are applied
- [x] Tickets are closed when resolved
- [x] Ticket stats are reviewed regularly

---

## 🙋‍♂️ Learn More

- [osTicket Official Docs](https://docs.osticket.com/)
- [osTicket Forums](https://forum.osticket.com/)

---

## 📄 License

This documentation is part of an educational guide.
