# Multi-COD Bot Tool

<div align="center">

The ultimate multi-view browser tool for Call of Duty bot lobbies with powerful automation, multi-instance management, and AFK protection.

**Contact:** Discord: **BluXploit** | TikTok: **@Bluontt**

</div>

---

## What is Multi-COD Bot Tool?

Multi-COD Bot Tool allows you to run multiple Call of Duty game instances simultaneously through an advanced multi-view browser system. Perfect for XP farming, bot lobbies, and managing multiple accounts at once.

### Key Features
- ✅ Support for MW3, BO6, and BO7
- ✅ Run 1-44 game instances simultaneously
- ✅ 8 powerful automation macros
- ✅ Game mode-specific layouts (Multiplayer, Warzone, CDL)
- ✅ Hardware-based license security
- ✅ Cross-platform support (Windows, macOS (soon), Linux)


---

## 🚀 Setup Guide

### System Requirements

**Minimum Requirements:**
- **RAM**: 4GB (8GB+ recommended for multiple views)
- **CPU**: Quad-core processor recommended
- **Internet**: Stable broadband (25+ Mbps recommended)
- **Display**: 1920x1080 resolution minimum
- **OS**: Windows 10/11, macOS 10.13+, or Linux

**Required:**
- Valid license key (hardware-bound)
- One Xbox account with Game Pass Ultimate per view (10 views = 10 accounts needed)
- Stable internet connection for cloud gaming

### Getting Started

1.  **Launch the Application**: Double-click the Multi-COD Bot Tool executable and wait for the selection window.
2.  **Activate Your License**: Enter your license key when prompted. Your hardware ID will be automatically validated.
3.  **Select Your Configuration**:
    *   **Choose Game Mode**: Multiplayer, Warzone, or CDL.
    *   **Select Game**: MW3, BO6, or BO7.
    *   **Choose Number of Views**: Select 1-44 instances based on your system's capability.
4.  **Start Your Session**: Click "Start" to launch all views. Each view loads as an independent browser session and will open the selected game automatically. Wait for all games to fully load before using macros.

---

## ✨ What's New in Version 4.2.1

This version introduces a refreshed user interface and a powerful new gameplay feature to enhance your experience.

**Key Updates:**
-   **New Main Screen Buttons**: The `main.html` screen has been updated with new buttons, providing quicker access to key features and a more intuitive user experience.
-   **Toggle Shooting Automation**: A new macro has been added that allows you to toggle automatic shooting on and off, giving you more precise control over in-game actions.
-   **Bug Fixes and Performance Improvements**: General stability enhancements to ensure a smoother and more reliable experience.

---

## ✅ Recommendations for Best Results

### Optimal Setup
1.  **Use Wired Internet**: Ethernet connection is much more stable than WiFi.
2.  **Close Background Apps**: Free up RAM and CPU for better performance.
3.  **Start Conservative**: Begin with 10 views, increase gradually.
4.  **Enable AFK Protection Early**: Toggle Macro 8 before going AFK.
5.  **Monitor First Session**: Watch the first 10-15 minutes to ensure stability.

### Recommended View Counts by System
-   **8GB RAM**: 10-15 views maximum
-   **16GB RAM**: 20-30 views recommended
-   **32GB+ RAM**: 30-44 views possible

### Macro Usage Strategy
-   **Starting Match**: Use Macro 1 (R key) to search.
-   **During Match**: Enable Macro 4 (Auto Movement) to stay active.
-   **End Match**: Use Macro 2 (Abandon) to return to lobby quickly.
-   **Going AFK**: Enable Macro 8 (AFK Both) before leaving.

### Gameplay Strategy & Ban Avoidance
-   **Shadowbanned Accounts**: Be aware that shadowbanned accounts will NOT gain XP.
-   **Headshot Limit Bypass**: To bypass headshot limits, get approximately 50 headshots, then leave the match, rejoin, and repeat.
-   **Avoid Nukes**: Do NOT drop nukes, as this can significantly increase your risk of detection and bans.
-   **Maintain Low KD**: Keep your Kill/Death (KD) ratio below 2.0 to avoid drawing unwanted attention and potential bans.

---

## ❓ Frequently Asked Questions (FAQs)

**Q: How many instances can I run at once?**  
A: The tool supports 1-44 views. Your actual limit depends on your PC specs and internet speed. Start with 10-15 views and increase if performance is good.

**Q: Do I need Xbox Game Pass?**  
A: Yes, you need Xbox Game Pass Ultimate for EACH view. Running 10 views requires 10 separate Game Pass Ultimate subscriptions.

**Q: How much does it cost to run multiple views?**  
A: Xbox Game Pass Ultimate costs ~$16.99/month per account. Running 20 views = 20 accounts = ~$340/month. Plan your budget accordingly.

**Q: Can I use this on multiple computers?**  
A: No, licenses are hardware-bound to one PC. Each PC needs its own license.

**Q: Do I need separate Xbox accounts for each view?**  
A: Yes, you need one Xbox account (with Game Pass Ultimate) for each view you want to run. Running 20 views = 20 Xbox accounts required.

**Q: How much bandwidth do I need?**  
A: Recommended 25+ Mbps for 5-10 views. Add ~2-3 Mbps per additional view.

**Troubleshooting:**
- If your mouse cursor does not line up, use W, A, S, D to navigate and SPACE to select.
- If the '@' symbol does not work, try refreshing the screen or restarting your PC.

---

## ⚠️ Legal Disclaimer

This tool is provided "AS IS" without warranty of any kind. Use of automation software may violate Call of Duty Terms of Service. The developer is NOT responsible for any account actions or bans. You assume ALL risks associated with using this software. No refunds are provided for bans or account restrictions.

---

## Contact & Support

**For questions, issues, or license inquiries:**

📱 **Discord**: BluXploit  
🎵 **TikTok**: @Bluontt  

---

<div align="center">

**Multi-COD Bot Tool 4.2.1**

*Manage. Automate. Dominate.*

Developed by BluXploit

---

© 2025 Blu Services. All Rights Reserved.

</div>

---

## Running on a VPS (24/7 Remote Server)

Want to run Multi-COD Bot Tool 24/7 on a remote server? Follow this guide to deploy on a VPS.

### Requirements

- **VPS with Linux** (Ubuntu 20.04+ or Debian 11+ recommended)
- **Minimum specs**: 4GB RAM, 2 CPU cores, 20GB storage
- **Linux package** (MultiCOD-Bot-Tool.AppImage or .deb file)
- **VNC Viewer** on your local computer to access the GUI

### Why Use a VPS?

✅ Run your bot 24/7 without keeping your PC on  
✅ Access from anywhere via VNC  
✅ Dedicated resources for optimal performance  
✅ Multiple instances on one server  
✅ Professional hosting environment  

### Important Note

**VPS servers don't have a desktop/GUI** - they're "headless" (no monitor). To view and interact with Multi-COD's GUI remotely, you need to set up a virtual display and VNC server. This guide shows you how.

### Setup Instructions

**Step 1: Prepare Your VPS**

```bash
# SSH into your VPS
ssh root@your-vps-ip

# Update system
sudo apt update && sudo apt upgrade -y

# Install required packages for virtual display and VNC
sudo apt install -y xvfb x11vnc fluxbox wget
```

**Step 2: Upload the Linux Package**

```bash
# On your local computer, upload the Linux package to your VPS
# Replace "MultiCOD-Bot-Tool.AppImage" with your actual filename
scp MultiCOD-Bot-Tool.AppImage root@your-vps-ip:/root/

# Make it executable
ssh root@your-vps-ip "chmod +x /root/MultiCOD-Bot-Tool.AppImage"
```

**If you have a .deb package instead:**
```bash
# Upload the .deb file
scp MultiCOD-Bot-Tool.deb root@your-vps-ip:/root/

# Install it
ssh root@your-vps-ip "sudo dpkg -i /root/MultiCOD-Bot-Tool.deb"
ssh root@your-vps-ip "sudo apt-get install -f"  # Fix dependencies if needed
```

**Step 3: Create Startup Script**

```bash
# SSH into your VPS
ssh root@your-vps-ip

# Create the startup script
nano /root/start-multicod.sh
```

Copy and paste this into the file:

```bash
#!/bin/bash

# Kill any existing processes
pkill -f Xvfb
pkill -f x11vnc
pkill -f MultiCOD

# Start virtual display (creates a fake monitor)
Xvfb :99 -screen 0 1920x1080x24 &
sleep 3

# Start window manager
DISPLAY=:99 fluxbox &
sleep 2

# Start VNC server (allows remote viewing)
x11vnc -display :99 -nopw -listen 0.0.0.0 -forever -shared &
sleep 2

# Start Multi-COD Bot Tool
# Replace the path with your actual file location
DISPLAY=:99 /root/MultiCOD-Bot-Tool.AppImage --no-sandbox --disable-gpu

# If you installed via .deb, use this instead:
# DISPLAY=:99 multi-cod-bot-tool --no-sandbox --disable-gpu
```

Save the file (Ctrl+X, then Y, then Enter)

```bash
# Make the script executable
chmod +x /root/start-multicod.sh
```

**Step 4: Create Auto-Start Service**

This ensures Multi-COD starts automatically when your VPS reboots.

```bash
# Create systemd service file
sudo nano /etc/systemd/system/multicod.service
```

Copy and paste this:

```ini
[Unit]
Description=Multi-COD Bot Tool
After=network.target

[Service]
Type=simple
User=root
WorkingDirectory=/root
ExecStart=/root/start-multicod.sh
Restart=always
RestartSec=10
Environment="DISPLAY=:99"

[Install]
WantedBy=multi-user.target
```

Save the file (Ctrl+X, then Y, then Enter)

```bash
# Enable and start the service
sudo systemctl daemon-reload
sudo systemctl enable multicod.service
sudo systemctl start multicod.service

# Check if it's running
sudo systemctl status multicod.service
```

**Step 5: Open Firewall Port for VNC**

```bash
# Allow VNC port through firewall
sudo ufw allow 5900/tcp
sudo ufw enable
sudo ufw status
```

**Step 6: Connect from Your Computer**

```bash
# On your local computer, install a VNC viewer:
# - Windows: Download TigerVNC or TightVNC
# - Mac: Download RealVNC Viewer
# - Linux: sudo apt install tigervnc-viewer

# Connect to your VPS
# Open VNC Viewer and connect to: your-vps-ip:5900

# You should see the Multi-COD Bot Tool interface!
```

### Managing Your VPS Deployment

**View Logs:**
```bash
sudo journalctl -u multicod.service -f
```

**Restart the Application:**
```bash
sudo systemctl restart multicod.service
```

**Stop the Application:**
```bash
sudo systemctl stop multicod.service
```

**Check Status:**
```bash
sudo systemctl status multicod.service
```

**Update to New Version:**
```bash
# Stop the service
sudo systemctl stop multicod.service

# Upload new version from your computer
scp MultiCOD-Bot-Tool-NEW.AppImage root@your-vps-ip:/root/

# Update the path in startup script if filename changed
nano /root/start-multicod.sh

# Start the service
sudo systemctl start multicod.service
```

**Check Resource Usage:**
```bash
# Overall system resources
htop

# Check specific process
ps aux | grep MultiCOD
```

### VNC Connection Tips

- **Port 5900** must be open on your VPS firewall
- **No password** is set by default for simplicity
- **For better security**, use SSH tunneling instead of exposing port 5900:
  ```bash
  # On your computer, create SSH tunnel
  ssh -L 5900:localhost:5900 root@your-vps-ip
  
  # Then connect VNC to: localhost:5900 (not your VPS IP)
  # This encrypts VNC traffic through SSH
  ```

### Resource Recommendations by View Count

| Views | RAM  | CPU Cores | VPS Cost (approx) |
|-------|------|-----------|-------------------|
| 1-10  | 4GB  | 2 cores   | $10-15/month      |
| 11-20 | 8GB  | 4 cores   | $20-30/month      |
| 21-30 | 12GB | 6 cores   | $40-60/month      |
| 31-44 | 16GB | 8 cores   | $80-120/month     |

**Recommended VPS Providers:**
- **DigitalOcean** (Droplets) - Easy to use, great documentation
- **Linode** (Shared/Dedicated instances) - Reliable, good support
- **Vultr** (Cloud Compute) - Fast deployment, many locations
- **Hetzner** (Cloud Servers) - EU based, very affordable
- **Contabo** - Cheapest option, good for testing

### Troubleshooting VPS Deployment

**Problem: Can't connect via VNC**
```bash
# Check if VNC is running
ps aux | grep x11vnc

# Check if port 5900 is open
sudo netstat -tulpn | grep 5900

# Check firewall
sudo ufw status

# Allow port if blocked
sudo ufw allow 5900
```

**Problem: Application won't start**
```bash
# Check service status
sudo systemctl status multicod.service

# View detailed logs
sudo journalctl -u multicod.service -n 50

# Check if display is running
ps aux | grep Xvfb

# Try starting manually to see errors
/root/start-multicod.sh
```

**Problem: Black screen in VNC**
```bash
# Display might not be ready
# Wait 10-15 seconds after starting

# Restart the service
sudo systemctl restart multicod.service

# Check if window manager is running
ps aux | grep fluxbox
```

**Problem: Out of memory**
```bash
# Check memory usage
free -h

# Check what's using memory
ps aux --sort=-%mem | head

# Reduce view count or upgrade VPS
# Kill and restart service
sudo systemctl restart multicod.service
```

**Problem: Performance is slow**
```bash
# Check if VPS is overloaded
top
htop

# Check I/O wait
iostat -x 1 5

# Consider upgrading to higher tier VPS
# Or reduce number of views
```

**Problem: App crashes after a while**
```bash
# Service will auto-restart (RestartSec=10)
# Check logs to see why it crashed
sudo journalctl -u multicod.service -n 100

# Common causes:
# - Out of memory (reduce views)
# - Network issues (check connection)
# - License validation failed (check KeyAuth)
```

**Problem: Xbox Cloud Gaming Says "No Input Device Detected"**

If you're using Xbox Cloud Gaming on your VPS and see this error, the system needs to detect virtual input devices. Follow these steps:

```bash
# 1. Install required packages
sudo apt update
sudo apt install -y libevdev-dev build-essential xdotool evemu-tools

# 2. Load kernel modules for virtual input devices
sudo modprobe uinput
sudo modprobe joydev
sudo modprobe evdev

# 3. Make modules persistent across reboots
echo -e "uinput\njoydev\nevdev" | sudo tee -a /etc/modules

# 4. Set proper permissions for uinput
sudo chmod 666 /dev/uinput

# 5. Verify virtual input devices were created
ls -la /dev/input/

# You should see /dev/input/event* devices listed
# If you see them, Xbox Cloud Gaming should now detect input devices
```

If Xbox Cloud Gaming still doesn't detect input after these steps:

```bash
# Create a virtual input device service that runs at startup
sudo bash -c 'cat > /opt/virtual-input-device.js << '\''EOF'\''
#!/usr/bin/env node
const fs = require("fs");
const { spawn } = require("child_process");

class VirtualInputDevice {
    init() {
        if (!fs.existsSync("/dev/uinput")) {
            console.error("[VirtualInputDevice] ERROR: /dev/uinput not found!");
            process.exit(1);
        }

        try {
            fs.accessSync("/dev/uinput", fs.constants.W_OK);
            console.log("[VirtualInputDevice] Virtual input devices initialized");
        } catch (error) {
            console.warn("[VirtualInputDevice] WARNING: /dev/uinput not writable");
        }

        setTimeout(() => this.verifyDevices(), 2000);
    }

    verifyDevices() {
        try {
            const devices = fs.readdirSync("/dev/input/");
            const eventDevices = devices.filter(d => d.startsWith("event"));
            console.log(`[VirtualInputDevice] Found ${eventDevices.length} input event devices`);
            eventDevices.forEach(device => {
                console.log(`  - /dev/input/${device}`);
            });
        } catch (error) {
            console.error("[VirtualInputDevice] Verification error:", error);
        }
    }
}

const virtualInput = new VirtualInputDevice();
virtualInput.init();

process.on("SIGINT", () => {
    console.log("[VirtualInputDevice] Shutdown");
    process.exit(0);
});
EOF'

# Make it executable
sudo chmod +x /opt/virtual-input-device.js

# Create systemd service for auto-start
sudo bash -c 'cat > /etc/systemd/system/virtual-input.service << '\''EOF'\''
[Unit]
Description=Virtual Input Device Service for Xbox Cloud Gaming
After=network.target

[Service]
Type=simple
ExecStart=/usr/bin/node /opt/virtual-input-device.js
Restart=on-failure
RestartSec=5
User=root
StandardOutput=journal
StandardError=journal

[Install]
WantedBy=multi-user.target
EOF'

# Enable and start the service
sudo systemctl daemon-reload
sudo systemctl enable virtual-input
sudo systemctl start virtual-input

# Verify it's running
sudo systemctl status virtual-input
```

**Note:** Your existing `macros.js` continues to work normally. This service runs in the background to create virtual input devices that Xbox Cloud Gaming can detect at the OS level, while your macros still send browser-level keyboard events. No changes to your code are needed.

### Windows VPS Alternative

If you prefer to use the **Windows .exe** file instead of Linux:

**Note:** Windows VPS costs 2-3x more than Linux VPS (~$30-80/month minimum)

1. Rent a Windows VPS (Windows Server 2019 or 2022)
2. Connect via Remote Desktop (RDP)
3. Download and run the MultiCOD .exe file
4. Runs like on your desktop - no Xvfb/VNC needed

**Pros:** Simple, runs .exe natively  
**Cons:** Much more expensive, slower performance  

Most users prefer Linux VPS for cost and performance.

### Security Best Practices

1. **Use SSH Key Authentication** instead of passwords
2. **Enable UFW Firewall**:
   ```bash
   sudo ufw enable
   sudo ufw allow 22    # SSH
   sudo ufw allow 5900  # VNC
   ```
3. **Use SSH Tunneling** for VNC instead of exposing port 5900
4. **Keep your VPS updated**:
   ```bash
   sudo apt update && sudo apt upgrade -y
   ```
5. **Use strong license keys** and keep .env file secure

### Cost Estimation

**Monthly costs for running on VPS:**

- VPS Hosting: $10-120/month (depending on resources)
- Xbox Game Pass Ultimate: $17/month × number of views
  - Example: 20 views = $340/month for Game Pass accounts

**Total for 20 views:** ~$360-380/month

---

<div align="center">

**Multi-COD Bot Tool 4.2.1**

*Manage. Automate. Dominate.*

Developed by BluXploit

Discord: **BluXploit** | TikTok: **@Bluontt**



© 2025 Multi-COD Bot Tool. All Rights Reserved.

</div>
