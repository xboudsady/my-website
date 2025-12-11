---
sidebar_position: 5
title: Data Synchronization and Troubleshooting
---

# Troubleshooting and Maintenance for Analysts

This section outlines common issues and the steps an analyst can take to troubleshoot the field user's application.

## Data Refresh and Synchronization Issues

Synchronization is how the app exchanges data with the server. [cite_start]When technicians report missing or outdated data, the first step is to check the refresh status[cite: 4].

* [cite_start]**Manual Refresh:** Technicians can manually update the record data (worklists, maps, supporting data) directly from the device to ensure they have the latest server information[cite: 4].
* [cite_start]**Partial Data Refresh:** Newer versions support refreshing only specific data components (e.g., just the map data or worklists), which is faster and more efficient than a full sync[cite: 4].

## Leveraging Maximo Mobile Logs

[cite_start]The application generates logs that are essential for diagnosing connectivity, sync, and application errors[cite: 7].

1.  [cite_start]**Viewing Logs:** Technicians can often view log file contents directly from within the mobile device's settings menu[cite: 7].
2.  [cite_start]**Clearing Logs:** Log files accumulate and can be cleared periodically to improve performance and free up storage[cite: 10].
3.  **Analyst Action:** If a ticket requires advanced troubleshooting, instruct the user to **share the log files** with you. [cite_start]This can be done by saving the logs to a local folder (common on Android) or using the device's sharing features[cite: 7].

## Map Feature Troubleshooting

[cite_start]Map features are crucial for route planning and locating work orders[cite: 3].

* [cite_start]**Requirement:** The underlying Maximo server requires a proper configuration of **Map Manager**, often leveraging Maximo Spatial Asset Management, for map data to display correctly on the mobile device[cite: 3].
* **Checklist:** If a technician cannot see map data, verify the following:
    * Is the device location/GPS enabled?
    * Is the Maximo Spatial license active on the server?
    * Is the Map Manager configured and linked to the mobile application profile?