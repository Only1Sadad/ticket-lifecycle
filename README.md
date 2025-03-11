# osTicket Ticketing System Lab Guide  

## 1. Access osTicket  
### Admin & Analyst Login  
- **Admin/Analyst Panel:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
- **End Users Portal:** [http://localhost/osTicket](http://localhost/osTicket)  

---

## 2. Lab Overview  
In this lab, we will:  
✅ **Create tickets as end users**  
✅ **Observe ticket properties and respond as Help Desk professionals**  
✅ **Modify department structures**  
✅ **Assign priority and SLA levels to tickets**  
✅ **Escalate and resolve tickets**  

---

## 3. Modify Departments  
📍 **Admin Panel → Agents → Departments**  
- **Change "SysAdmins" to a Top-Level Department**  
- **DELETE "Maintenance" Department** *(Do not archive, fully delete it)*  

---

## 4. Creating & Managing Tickets  

### 🎟️ **Ticket #1: Mobile/Online Banking System is Down**  
#### 👤 End-User Action:  
- Create a ticket with the issue: **"Entire mobile/online banking system is down"**  

#### 🎧 Help Desk Agent (John) Action:  
1. Observe the ticket properties:  
   - **Priority**  
   - **Department**  
   - **SLA**  
   - **Assigned To**  
2. Set ticket properties:  
   - **SLA:** Sev-A (1 hour, 24/7)  
   - **Department:** Online Banking  
3. Attempt to observe the ticket again as "John"—can you view or change it?  
4. **Resolve the ticket as Jane**  

---

### 🎟️ **Ticket #2: Adobe Upgrade for Accounting Department**  
#### 👤 End-User Action:  
- Create a ticket with the issue: **"Accounting department needs Adobe upgrade, broken"**  

#### 🎧 Help Desk Agent (John) Action:  
1. Observe the ticket properties:  
   - **Priority**  
   - **Department**  
   - **SLA**  
   - **Assigned To**  
2. Set ticket properties:  
   - **SLA:** Sev-B (4 hours, 24/7)  
   - **Department:** Support  
3. **Work the ticket to completion as John**  

---

### 🎟️ **Ticket #3: CFO’s Laptop Won’t Turn On**  
#### 👤 End-User Action:  
- Create a ticket with the issue: **"CFO’s laptop will no longer turn on"**  

#### 🎧 Help Desk Agent (John) Action:  
1. Observe the ticket properties:  
   - **Priority**  
   - **Department**  
   - **SLA**  
   - **Assigned To**  
2. Set ticket properties:  
   - **SLA:** Sev-B (4 hours, 24/7)  
   - **Department:** Support  
3. **Work the ticket to completion as John**  

---

## 5. Escalation & Access Restrictions  

### 🔄 **Escalate Tickets & Observe Access Changes**  
- Set properties for all tickets  
- Assign **Sev-A SLA to SysAdmins last**  
- Observe that John loses access to the escalated ticket  

### 🛠️ **Regain Access via Admin Panel**  
📍 **Admin Panel → Agents → Assign View Access to SysAdmins**  
- Switch to **Agent Panel**  
- Observe that the escalated ticket is visible but cannot be modified  

---

## 6. Solve All Tickets & Ticketing System Behavior  

### 📬 **Email Notifications in Ticketing Systems**  
- Most ticketing systems have **email integration**  
- Every ticket update sends a **notification to the user**  
- Users can respond via email, and replies are logged in the ticket  

---

## 7. Real-World Ticket Intake  
Tickets can be created via:  
📞 **Phone Calls**  
💬 **Chat Apps**  
📧 **Email**  
🌐 **Web Forms**  
👥 **In-Person Requests**  

⚠️ **Pro Tip:** Always create a ticket for every issue you resolve! This is crucial for:  
- **Tracking metrics** 📊  
- **Justifying workload & team efficiency** 🏆  
- **Ensuring accountability & documentation** 📝  

---

## 8. Finishing Up & Additional Practice  
✅ Explore more features (especially the **email feature**)  
✅ Repeat this lab multiple times to **build intuition**  
✅ Develop the **Technical Skill Pillar** by redoing and mastering the lab  

---

🎯 **Goal:** By practicing enough times, you should be able to implement this process using only a **simple checklist**! 🚀
