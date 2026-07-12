# Project 5 – Windows Event Viewer Log Analysis

## Objective

- Learn how to use Windows Event Viewer to investigate security events.
- Practice reviewing Windows logs to identify successful logins, failed logins, and other activity that could help during a security investigation.

---

## Environment

- Windows 10 Pro
- Windows Event Viewer
- Security Log
- Desktop Environment

---

## Skills Practiced

- Navigating Windows Event Viewer
- Reviewing Windows Security Logs
- Filtering event logs
- Investigating successful logon events
- Investigating failed logon events
- Identifying Windows Event IDs
- Understanding Windows authentication events

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Windows Event Viewer | Review Windows event logs |
| Windows Security Log | Analyze authentication activity |
| Filter Current Log | Search for specific Event IDs |
| Event Properties | Review event details |

---

## Lab Activities

- Opened Windows Event Viewer.
- Navigated to the Windows Security log.
- Reviewed Windows authentication events.
- Filtered the Security log by Event ID.
- Investigated successful logon events.
- Reviewed failed logon attempts.
- Examined event details including usernames, logon types, and timestamps.
- Learned how Windows records authentication activity for investigations.

---

## Screenshots

### 01 – Opening Windows Event Viewer

![Opening Windows Event Viewer](01%20Opening%20windows%20Event%20Viewer.png)

### 02 – Viewing Windows Security Log

![Viewing Windows Security Log](02%20Viewing%20Windows%20Security%20Log.png)

### 03 – Filtering Windows Security Logs

![Filtering Windows Security Logs](03%20Filtering%20Windows%20Security%20Logs.png)

### 04 – Investigating Successful Logon Events

![Investigating Successful Logon Events](04%20Investigating%20Successful%20Logon%20Events.png)

### 05 – Investigating Windows Logoff Events

![Investigating Windows Logoff Events](05%20Investigating%20Windows%20Logoff%20Events.png)

---

## Lessons Learned

- I learned how Windows records security activity using Event Viewer.
- I became more comfortable filtering logs to quickly find specific events.
- I learned how to identify successful and failed authentication attempts.
- I realized how important timestamps and Event IDs are during an investigation.
- I gained confidence navigating Windows logs without relying on third-party tools.

---

## SOC Analyst Takeaways

- Windows Event Viewer is one of the first places a SOC analyst checks during an investigation.
- Authentication logs help identify who logged in, when they logged in, and whether the activity was successful or failed.
- Event IDs make it easier to locate important security events without searching through thousands of log entries.
- Understanding Windows logs helps build a timeline during incident response.
