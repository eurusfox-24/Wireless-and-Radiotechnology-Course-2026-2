# Local Wi-Fi Network Analysis Report

## 1. Project Objective
The objective of this assignment is to analyze the configuration and performance of a local Wi-Fi network using the **Net Analyzer** mobile application to identify potential issues and propose technical optimizations.

---

## 2. Measurement Setup & Environment
* **Location:** University Library (Open space environment)
* **Device Used:** iPhone / iOS
* **Tool:** Net Analyzer App

---

## 3. Collected Data & Observations

### Network Identity
| Parameter | Value |
| :--- | :--- |
| **SSID** | Savonia |
| **BSSID** | dc:8c:37:2c:d7:0f |
| **Gateway IP** | 10.211.31.254 |
| **Security Type** | Enterprise |

### Performance Metrics
* **Network Speed and Latency:** Ping tests indicate a stable connection. Latency is low, suggesting the backend infrastructure is not overwhelmed.
* **Operating Channels:** (Check your app for the specific channel number and add it here).
* **Nearby Networks:** Scanning shows minimal interference from neighboring SSIDs in this specific area of the library.

---

## 4. Analysis and Troubleshooting
Based on the data collected, the following analysis was performed:

* **Network Congestion:** - **Status:** Not Congested. 
  - **Reason:** Ping tests were successful with low jitter. Being at the university during a period with fewer connected clients results in high available bandwidth.
  
* **Weak Signal Coverage:** - **Status:** Nominal/Excellent. 
  - **Reason:** The library layout is open-concept. There are no thick walls or tall metal furniture obstructing the path between the device and the Access Point.

* **Channel Overlap or Interference:** - **Status:** No significant interference. 
  - **Reason:** The current operating channel is clear of competing high-strength signals from different networks.

* **Suboptimal Router Placement:** - **Status:** Optimal. 
  - **Reason:** The Access Points (APs) are ceiling-mounted and facing downward. This provides a clear line-of-sight to users and minimizes signal absorption by floor-level objects.

---

## 5. Proposed Practical Solutions
To ensure the network remains high-performing during peak hours, the following solutions are recommended:

1. **Channel Changes:** Maintain a policy of using non-overlapping channels ($1$, $6$, or $11$ for $2.4$ GHz). If $5$ GHz congestion occurs, consider moving to higher UNII bands.
2. **Router Repositioning:** Continue the use of ceiling mounts. Ensure APs are not placed directly above large metal ventilation ducts which can cause signal reflection.
3. **Use of Different Frequency Bands:** Encourage high-traffic tasks (video streaming/large downloads) to stay on the **5 GHz band**, leaving the **2.4 GHz band** for lower-priority or long-range tasks.
4. **Security or Configuration Adjustments:** Maintain **WPA2/WPA3 Enterprise** for robust security. Ensure **Quality of Service (QoS)** is configured on the controller to prioritize educational applications over background data.

---



## 7. Conclusion
The "Savonia" Wi-Fi network in the library is well-optimized. The combination of Enterprise-grade security, strategic ceiling placement, and the use of modern frequency management ensures a reliable user experience for the university community.
