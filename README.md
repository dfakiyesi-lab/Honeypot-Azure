# 🕵️‍♂️ Multi Honeypot Platform – T-Pot on Azure Cloud

## 🎯 Objective
To deploy and manage a **multi-honeypot system (T-Pot)** in the Azure cloud environment to capture, monitor, and analyze real-world cyberattacks, enhancing skills in **threat detection**, **incident response**, and **cloud infrastructure security**.

---

## 🧰 Tools & Technologies Used
- **T-Pot** (multi-honeypot framework)
- **Microsoft Azure**
- **Ubuntu Server**
- **Docker & Docker Compose**
- **Elasticsearch, Kibana, and Logstash (ELK Stack)**
- **Firewall and Network Security Groups**

---

## ⚙️ Steps Performed

1. **Provisioned an Azure Virtual Machine**
   - Created an **Ubuntu Server VM** on Microsoft Azure.
   - Configured **network security groups (NSGs)** to allow inbound connections on relevant honeypot ports (e.g., 22, 80, 443, 445, 1433, etc.).
   - Secured SSH access via key-based authentication.

2. **Installed and Configured T-Pot**
   - Updated the system and installed **Docker** and **Docker Compose**.
   - Cloned the official **T-Pot repository** from GitHub.
   - Executed the T-Pot installation script, deploying multiple honeypots (e.g., **Cowrie**, **Dionaea**, **ElasticPot**, **Mailoney**, etc.).
   - Verified successful deployment via the T-Pot dashboard.

3. **Enabled Monitoring and Logging**
   - Accessed the **T-Pot Web UI (Cockpit)** for visual monitoring.
   - Configured **Kibana dashboards** to visualize attack data in real time.
   - Analyzed logs for intrusion attempts, malware uploads, and brute-force attacks.

4. **Analyzed Honeypot Data**
   - Monitored **source IPs, attack frequency, and targeted ports**.
   - Identified common attack patterns and tools used by threat actors.
   - Documented insights from live attack data for further study.

5. **Hardened the Environment**
   - Restricted management ports to specific IPs using Azure NSG rules.
   - Deployed automated backups and system updates to maintain reliability.
   - Regularly reviewed resource utilization for optimal performance.

---

## 📸 Screenshots

Include **4–5 high-value visuals** that demonstrate the project in action:

| Screenshot | Description |
|-------------|--------------|
| ![Azure VM Overview](./images/azure-vm.png) | Deployed Ubuntu VM running T-Pot in Azure |
| ![T-Pot Dashboard](./images/tpot-dashboard.png) | Overview of honeypot services |
| ![Kibana Attack Visuals](./images/kibana-visuals.png) | Attack data visualization in Kibana |
| ![Network Security Groups](./images/azure-nsg.png) | Azure network security configuration |
| ![T-Pot Cockpit Login](./images/tpot-login.png) | Secure T-Pot web interface |

💡 *Redact or blur sensitive IPs, domains, or usernames.*

---

## 🔒 Security & Analysis Highlights

- Captured live attack attempts from global threat actors.  
- Used **T-Pot’s modular honeypot system** to simulate multiple vulnerable services.  
- Visualized and analyzed real-time attack metrics using **ELK Stack dashboards**.  
- Reinforced Azure VM with security rules and SSH key-based access.

---

## 🧩 Key Takeaways

- Gained experience in **deploying honeypots** in a cloud environment.  
- Learned to interpret **attack patterns and telemetry data** using Kibana.  
- Strengthened practical knowledge in **Azure cloud security** and **network management**.  
- Enhanced awareness of common attack vectors targeting exposed services.

---

## 🚀 Next Steps (Optional Improvements)

- Integrate T-Pot logs with **Microsoft Sentinel** for SIEM correlation.  
- Automate data export for long-term trend analysis.  
- Deploy multiple honeypots across regions for broader visibility.  
- Add email alerts for high-severity attack activity.
