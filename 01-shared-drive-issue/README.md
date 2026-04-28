# 🎫 Ticket 001 — Cannot Access Shared Drive (VPN Issue)

## 📌 Issue
User cannot access shared network drive while working remotely.

**Error:**  
"The network path was not found"

---

## 🧠 Analysis

- User working remotely (WFH)
- Internet and email working fine
- Other users not affected
- Mapped drive shows disconnected

👉 Likely cause: **User not connected to VPN**

---

## 🛠️ Troubleshooting Steps

### Step 1 — Review Ticket
User reports issue accessing shared drive.
![Ticket Overview](screenshots/ticket-overview.png)

---

### Step 2 — Start Remote Support Session
Connected to user's machine.
*(optional if you want to mention it, no screenshot needed if not clear)*

---

### Step 3 — Check VPN Status
VPN is disconnected.
![VPN Disconnected](screenshots/vpn-disconnected.png)

---

### Step 4 — Connect to VPN
User connects to corporate VPN.
![VPN Connected](screenshots/vpn-connected.png)

---

### Step 5 — Locate File Server Path
Used documentation to find correct UNC path:

![Documentation](screenshots/documentation-file-server.png)

---

### Step 6 — Verify Existing Drive Issue
Mapped drive is currently disconnected.
![Disconnected Drive](screenshots/network-drive-disconnected.png)

---

### Step 7 — Map Network Drive
Mapped drive using correct UNC path.
![Map Network Drive](screenshots/map-network-drive-dialog.png)

---

### Step 8 — Confirm Drive Access
Drive is now connected and files are accessible.
![Working Drive](screenshots/network-drive-working.png)

---

### Step 9 — Close Ticket
Issue resolved and ticket closed.
![Ticket Closed](screenshots/ticket-closed.png)

---

## ✅ Resolution
Connected user to VPN and remapped the network drive successfully.

---

## 🔍 Root Cause
User was not connected to VPN, preventing access to internal file server.

---

## 💡 Skills Demonstrated

- VPN troubleshooting
- Network drive mapping
- Remote support workflow
- Documentation usage
- Root cause analysis
- End-user support
