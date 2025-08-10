# Firewall Configuration Steps – Windows Defender Firewall (Advanced Settings)

## 1️⃣ Open Firewall Advanced Settings
1. Open **Windows Security**.
2. Click **Firewall & network protection**.
3. Scroll down and click **Advanced settings**.

---

## 2️⃣ View Current Inbound Rules
1. In the left sidebar, click **Inbound Rules**.
2. Review the list of existing rules.

---

## 3️⃣ Block a Specific Port (Example: Port 23 – Telnet)
1. Click **New Rule…** (right-hand panel).
2. Select **Port** → **Next**.
3. Choose **TCP**, enter `23` in **Specific local ports** → **Next**.
4. Select **Block the connection** → **Next**.
5. Apply to **Domain**, **Private**, **Public** → **Next**.
6. Name the rule **Block Telnet Port 23** → **Finish**.

---

## 4️⃣ Test the Rule
- Try connecting to port 23 (using Telnet or network tool).
- Connection should fail if the rule is applied correctly.

---

## 5 Remove the Test Rule
1. In **Inbound Rules**, find **Block Telnet Port 23**.
2. Right-click → **Delete** → Confirm.

---

## 6 Screenshots
📸 Add screenshots for each step in the `/screenshots` folder.
