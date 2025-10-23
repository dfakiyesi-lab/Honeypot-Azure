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
1. **Azure portal view** *(showing VM properties)* <img width="1600" height="857" alt="image" src="https://github.com/user-attachments/assets/0bc4a688-f20f-4feb-be66-565dda932162" />


2. **PuTTY SSH session** *(connected to T-Pot instance)*  <img width="997" height="589" alt="Screenshot 2025-10-12 182402" src="https://github.com/user-attachments/assets/3ff800cb-f594-4431-9d47-3d2d5adb802f" />

3. **T-Pot dashboard** <img width="2548" height="1424" alt="Screenshot 2025-10-12 190833" src="https://github.com/user-attachments/assets/9ca74ff5-f77f-4884-81ec-4f57817e1fef" />
  
4. **Attack Map/ElasticVue/Kibana view** *(threat visualization)*  <img width="2518" height="1423" alt="Screenshot 2025-10-12 195145" src="https://github.com/user-attachments/assets/57f79cc7-4d74-492d-a8d1-ca8d031d14a4" /> <img width="2545" height="1442" alt="Screenshot 2025-10-12 200110" src="https://github.com/user-attachments/assets/26bb82bd-3f46-49d9-b20e-0ab8df4c4e8e" /> <img width="2535" height="1433" alt="Screenshot 2025-10-12 195521" src="https://github.com/user-attachments/assets/53b4e9c5-adbd-49fe-ab5a-7c5fbb99d2f3" />




---

## 🧩 Key Takeaways
- Learned how to deploy and secure a honeypot environment in the cloud.  
- Gained experience monitoring real-world attack traffic using T-Pot.  
- Understood how honeypots can collect valuable threat intelligence data.  
- Strengthened knowledge of Azure network security and Linux-based server management.
