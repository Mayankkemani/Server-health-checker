

### Server Health Check Script

**Purpose:**  
This script automates daily server health monitoring for Linux systems. It reduces manual checking time from 10 minutes to 10 seconds.

**What It Checks:**
1. **Disk Usage:** Alerts if root partition > 90%. Prevents server crashes due to full disk.
2. **RAM Usage:** Monitors memory consumption. Alerts if usage > 90%.
3. **CPU Load Average:** Displays 1min, 5min, 15min load to detect high CPU usage.
4. **Critical Services:** Checks if Nginx/Apache is running. Essential for web servers.
5. **Top Processes:** Lists top 5 memory-consuming processes for quick troubleshooting.

<div align="center">

# Linux DevOps Scripts 🔧

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

## 📊 Scripts
1. `serverh.sh` - CLI health check





**Key Features:**
- **Color-Coded Output:** RED for Critical, YELLOW for Warning, GREEN for OK. Easy to read in terminal.
- **Zero Dependencies:** Uses built-in Linux commands only. Works on any Ubuntu/CentOS server.
- **Cron-Ready:** Can be scheduled via crontab for automated daily reports.

**How It Helps Business:**  
Prevents downtime. 1 hour of website downtime = ₹50,000+ loss. This script gives early alerts.
