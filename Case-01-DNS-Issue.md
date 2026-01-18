# Case 01 – Websites Not Opening (DNS Issue)

## 🧩 Problem
User reported that some websites were not opening while internet connection was active.

## 🔍 Troubleshooting Steps
1. Checked physical network connection
2. Verified IP address using `ipconfig`
3. Tested connectivity using `ping`
4. Changed DNS servers to:
   - 8.8.8.8
   - 1.1.1.1
5. Flushed DNS cache

## ✅ Solution
After updating DNS settings and flushing DNS cache, websites started working normally.

## 🛠 Tools Used
- Windows 10
- Command Prompt

## 📝 Notes
DNS misconfiguration can cause partial internet access.
