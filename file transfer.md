# 📁 File Transfer Between Two Windows 11 PCs (Ethernet + Wireless SFTP)

## 🟡 Method 1: Direct Ethernet Cable File Transfer (No Internet Required)

### ✅ What You Need:
- 1x Ethernet cable (Cat5e or Cat6)
- Both PCs running Windows 11

### 🔧 Steps:

1. **Connect the Ethernet cable** to both laptops.

2. **Assign Static IPs**:
   - Go to: `Control Panel > Network and Sharing Center > Change adapter settings`
   - Right-click **Ethernet** > Properties > Internet Protocol Version 4 (TCP/IPv4)
   - Assign:
     - **Laptop A**: `192.168.0.1`, Subnet: `255.255.255.0`
     - **Laptop B**: `192.168.0.2`, Subnet: `255.255.255.0`

3. **Enable File Sharing**:
   - Go to: `Control Panel > Network and Sharing Center > Advanced sharing settings`
   - Enable:
     - Network discovery
     - File and printer sharing
     - Turn off password protected sharing (optional)

4. **Share the Folder**:
   - Right-click the folder > Properties > Sharing > Advanced Sharing
   - Enable sharing & set permissions (e.g., Everyone = Full Control)

5. **Access Shared Folder**:
   - On the other PC: Press `Win + R` and type:
     ```
     \\192.168.0.1\SharedFolderName
     ```
   - Copy files directly.

---

## 🔵 Method 2: Wireless File Transfer Over SFTP (Same Network or Hotspot)

### ✅ What You Need:
- Both PCs connected to the same Wi-Fi network or hotspot
- One PC will act as **SFTP server**

### 🔧 Steps:

1. **Create a Hotspot (if needed)**:
   - Go to: `Settings > Network & Internet > Mobile Hotspot`
   - Turn it on, and connect the other PC to it

2. **Enable OpenSSH Server** (on host PC):
   - Go to: `Settings > Apps > Optional Features`
   - Install **OpenSSH Server**
   - Start the service:
     - `Win + R` → `services.msc` → Start **OpenSSH SSH Server**

3. **Find Host IP**:
   - Open Command Prompt, run:
     ```
     ipconfig
     ```
   - Note the IPv4 address (e.g., `192.168.137.1`)

4. **Connect via SFTP** (from other PC):
   - **Using File Explorer**:
     ```
     sftp://192.168.137.1
     ```
   - **Using Command Line**:
     ```
     sftp username@192.168.137.1
     ```
   - **Using WinSCP**:
     - Protocol: SFTP
     - Host: `192.168.137.1`
     - Username & password of host PC

### 🟢 Tips:
- Ensure both devices are on the same subnet (192.168.x.x)
- Use WinSCP for easier GUI-based transfers

---
