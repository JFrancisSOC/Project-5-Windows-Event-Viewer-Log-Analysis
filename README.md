
# Project 5 – Windows Event Viewer & Log Analysis

## Objective

* Develop practical Windows log analysis skills used by Security Operations Center (SOC) analysts by viewing, searching, filtering, and interpreting Windows Security logs using Event Viewer.

---

## Environment

* Windows 11
* Windows Event Viewer

---

## Skills Practiced

* Opening Windows Event Viewer
* Navigating Windows Security logs
* Viewing Windows authentication events
* Filtering Security logs by Event ID
* Identifying successful logon events
* Identifying failed logon events
* Identifying logoff events
* Interpreting Windows Event IDs
* Performing basic Windows log analysis

---

## Commands Used

| Command        | Purpose                   |
| -------------- | ------------------------- |
| `eventvwr.msc` | Open Windows Event Viewer |

---

## Lab Activities

* Opened Windows Event Viewer.
* Navigated to the Windows Security log.
* Reviewed successful logon events using Event ID 4624.
* Filtered the Security log for failed logon events using Event ID 4625.
* Reviewed logoff events using Event ID 4634.
* Identified authentication details including account name, logon type, and logon ID.
* Compared authentication events to understand user activity.
* Completed a simulated SOC investigation involving Windows authentication events.

---

## Screenshots

* P5 01 Opening Windows Event Viewer
* P5 02 Viewing Windows Security Log
* P5 03 Filtering Windows Security Logs
* P5 04 Investigating Successful Logon Events
* P5 05 Investigating Windows Logoff Events

---

## Lessons Learned

* I learned how Windows records authentication activity within the Security log.
* I practiced identifying successful logon, failed logon, and logoff events using Event IDs 4624, 4625, and 4634.
* I learned how to filter Windows Security logs to locate specific authentication events.
* I learned that authentication events should always be reviewed within their proper context before determining whether suspicious activity has occurred.

---

## SOC Analyst Takeaways

* Windows Security logs are one of the primary sources of evidence during authentication investigations.
* Reviewing Event IDs 4624, 4625, and 4634 helps analysts understand user authentication activity and identify potential security concerns.
* Authentication events should be correlated and analyzed as part of a timeline before determining whether escalation is necessary.
