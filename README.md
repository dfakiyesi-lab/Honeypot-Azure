# 🎯 Explore the World of Honeypots (T-Pot on Azure)

## 🎯 Objective
Deploy and monitor **T-Pot**, an all-in-one honeypot solution, on **Microsoft Azure** to simulate cyberattacks and analyze threat behavior in a controlled environment.

---

## 🧰 Tools Used
- **Microsoft Azure**
- **T-Pot Honeypot Framework**
- **PuTTY**
- **Ubuntu Server (VM)**
- **Azure Network Security Groups (NSGs)**

---

## ⚙️ Steps Performed

1. **Created Azure Account**
   - Registered and configured a new **Microsoft Azure** account.
   - Navigated to the **Azure Portal** to access virtual machine resources.

2. **Provisioned the Virtual Machine**
   - Created an **Ubuntu Server** virtual machine to host T-Pot.
   - Configured network settings and assigned a static public IP address.
   - Adjusted **Network Security Groups (NSGs)** to allow relevant inbound ports for honeypot services.

3. **Connected via SSH**
   - Installed **PuTTY** on the local system to establish an SSH connection.
   - Used Azure-generated credentials to connect securely to the Ubuntu VM.

4. **Installed T-Pot**
   - Downloaded the official T-Pot installation script.
   - Executed the script to deploy multiple honeypot services (e.g., Cowrie, Dionaea, ElasticPot).
   - Verified successful installation and started monitoring dashboards.

5. **Monitored and Analyzed Attacks**
   - Accessed the **T-Pot web interface** via browser using the VM’s public IP.
   - Observed live attack attempts, including SSH brute-force and web-based exploits.
   - Recorded and analyzed threat intelligence data for potential patterns.

---

## 📸 Screenshots
1. **Azure portal view** *(showing VM and network configuration)*  
2. **PuTTY SSH session** *(connected to T-Pot instance)*  
3. **T-Pot dashboard** *(live attack logs and graphs)*  
4. **Elastic/Kibana analytics view** *(threat visualization)*  

---

## 🧩 Key Takeaways
- Learned how to deploy and secure a honeypot environment in the cloud.  
- Gained experience monitoring real-world attack traffic using T-Pot.  
- Understood how honeypots can collect valuable threat intelligence data.  
- Strengthened knowledge of Azure network security and Linux-based server management.
