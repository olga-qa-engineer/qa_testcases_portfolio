# Contact Tab - Permissions

---

## TC54 — Client > Edit > "Contact" tab is visible for authorized users

| Step | Expected Result |
|------|-----------------|
| Log in to RMSys as Administrator | User successfully logs into RMSys |
| Select any Client and click "Edit" button | "Edit Client" window opens |
| Verify "Contact" tab | "Contact" tab is visible |
| Log out from RMSys | User logs out successfully |
| Log in to RMSys as Office Manager | User successfully logs into RMSys |
| Select any Client and click "Edit" button | "Edit Client" window opens |
| Verify "Contact" tab | "Contact" tab is visible |
| Log out from RMSys | User logs out successfully |
| Log in to RMSys as RMSys Operator | User successfully logs into RMSys |
| Select any Client and click "Edit" button | "Edit Client" window opens |
| Verify "Contact" tab | "Contact" tab is visible |
| Log out from RMSys | User logs out successfully |
| Log in to RMSys as Staffing Manager | User successfully logs into RMSys |
| Select any Client and click "Edit" button | "Edit Client" window opens |
| Verify "Contact" tab | "Contact" tab is visible |

---

## TC55 — Client > Edit > "Contact" tab is not visible for unauthorized user

| Step | Expected Result |
|------|-----------------|
| Log in to RMSys as a user without Contact tab permission | User successfully logs into RMSys |
| Select any Client and click "Edit" button | "Edit Client" window opens |
| Verify "Contact" tab | "Contact" tab is NOT visible |
