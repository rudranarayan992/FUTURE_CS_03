# FUTURE_CS_03
🔐 Wi-Fi Security Assessment | Cyber Security Internship Task 03   Performed a security audit on a home Wi-Fi network using tools like Nmap, Wireshark, and Aircrack-ng. Identified open ports, tested password strength, and monitored unauthorized access. Includes scan results, recommendations, and proof of work.
# 📡🔐 **Wi-Fi Security Assessment | Task 03** 🛡️🔍

## 🚀 **Task Overview** 💡

As part of my **Cyber Security Internship** with **Future Interns**, I conducted a **Wi-Fi Security Assessment** on my home network. The purpose was to analyze network traffic, check for weak passwords, identify open ports, and detect unauthorized devices. This task helped me gain hands-on experience with **network security tools** and methods, ensuring that my home network is secure and protected from potential vulnerabilities.

---

## 🛠️ **Tools & Techniques Used** 🧰

- **Wireshark** – 📊 Capturing and analyzing network traffic.  
- **Aircrack-ng** – 🔑 Auditing wireless networks and testing WPA2 password strength.  
- **Nmap** – 🌐 Scanning open ports, network mapping, and detecting potential security issues.

---

## 🧠 **Skills Gained** 🎓

- Understanding of **Wi-Fi encryption protocols** (WEP, WPA, WPA2).  
- Hands-on experience with **penetration testing** tools for wireless networks.  
- Knowledge of **network monitoring** and analysis techniques to identify vulnerabilities.  
- Identifying and mitigating potential risks from unauthorized devices and open ports.

---

## 📝 **Assessment Procedure** 📑

### 1. **Wi-Fi Encryption & Password Strength** 🔒
- **Goal**: Ensure the Wi-Fi password is strong and the network is encrypted using WPA2.  
- **Method**: I used **Aircrack-ng** to capture the WPA2 handshake and checked password strength using a custom wordlist.  
- **Result**: The network was secured with a strong password, not found in any dictionary.

### 2. **Port Scanning & Network Mapping** 🌍
- **Goal**: Identify any open ports or services running on the network that could be exploited.  
- **Method**: I used **Nmap** to scan the local network and identify all active devices and open ports.  
- **Result**: Found several services running, including HTTP on port 80 (local device) and SSH on port 22 (valid service).

### 3. **Device Monitoring & Traffic Analysis** 🚨
- **Goal**: Monitor network traffic for any signs of unauthorized access or suspicious activity.  
- **Method**: Using **Wireshark**, I captured network traffic and analyzed packets to detect any malicious or unusual traffic patterns.  
- **Result**: No unauthorized devices were found, but I did detect frequent communication from IoT devices to external IPs.

---

## 📊 **Findings & Results** 📈

| **Check**                    | **Status**     | **Notes**                              |
|------------------------------|----------------|----------------------------------------|
| **Wi-Fi Encryption**          | ✅ **Secure**   | WPA2 encryption with strong password   |
| **Open Ports**                | ⚠️ **Found**   | Port 80 (HTTP) on a local device       |
| **Unauthorized Devices**      | ✅ **None**     | All connected devices are known        |
| **Suspicious Traffic**        | ⚠️ **Minor**   | IoT devices communicating externally   |

- **Wi-Fi Security**: The network was protected by a strong WPA2 password, and no cracks were found using Aircrack-ng.
- **Port Scanning**: Discovered open ports, notably port 80, which is associated with a local service. This should be disabled if not needed.
- **Device Monitoring**: No unauthorized devices detected, but some IoT devices were communicating with external servers, potentially leaking data.

---

## ✅ **Recommendations** 🛡️

1. **Strengthen IoT Security** 🏠  
   - Change default credentials on all IoT devices.  
   - Use a **guest network** for IoT devices to isolate them from the main network.

2. **Close Unnecessary Ports** 🚪  
   - Disable unused services like HTTP (port 80) to reduce the attack surface.  
   - Regularly scan the network for open ports using tools like Nmap.

3. **Use MAC Address Filtering** 🆔  
   - Implement MAC address filtering on the router to allow only known devices to connect to the network.

4. **Regular Traffic Monitoring** 👀  
   - Continuously monitor network traffic with Wireshark for any unusual activity.  
   - Set up alerts for suspicious behavior like unauthorized devices or abnormal data transfers.

5. **Firmware Updates** 🔄  
   - Regularly update the router’s firmware to patch any security vulnerabilities.

---

## 📁 **Project Files** 📂














---

## 📅 **Task Completion** 📆  
**Task**: 03  
**Track**: Cyber Security (CS)  
**Intern**: [Rudra Narayan Swain]  
**Date**: April 2025  

---

## 📣 **Proof of Work** 📹

📹 **Video demonstration** of the Wi-Fi security assessment: [task03_demo.mp4]
---

# 💻 **Follow My Internship Journey** 🚀

- **LinkedIn**: [Linkhttps://www.linkedin.com/in/rudra-narayan-swain-cyber-student/]  
  

