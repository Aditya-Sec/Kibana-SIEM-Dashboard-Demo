# Kibana-SIEM-Dashboard-Demo
Detect brute force login attacks using Kibana with sample Linux logs.

# 📊 Kibana SIEM Dashboard Demo: Brute Force Login Detection

This project demonstrates how to detect brute force login attempts using Kibana's visualizations and log analysis capabilities.

---

## 🔍 Detection Logic

The Kibana dashboard identifies:

- 🔁 Repeated login failures from same IPs
- 🌍 Unusual geo-locations for login attempts
- 🔐 Accounts targeted most frequently

---

## 📷 Screenshots

Located in `dashboard-screenshots/`:

- `dashboard-overview.png`
- `failed-logins-visual.png`
- `geo-map-login-attempts.png`

---

## 📊 Visualizations

- Failed Logins per Username
- Source IP Location Map
- Login Status Distribution (Pie chart)
- Time-Series Failed Attempts

---

## 🧠 What I Learned

- Real-time log parsing with Kibana
- Index pattern creation
- Visual correlation between IP, user, and timestamps
- Foundations of detection engineering for brute force attacks

---

## 🗂 Folder Structure
Kibana-SIEM-Dashboard-Demo/
├── README.md
├── sample-logs/
│ └── Linux-auth-failed.csv
├── dashboard-screenshots/
│ ├── dashboard-overview.png
│ ├── failed-logins-visual.png
│ └── geo-map-login-attempts.png
└── visualizations.json (optional)


---

## 🙋 About Me

I’m a SOC Analyst transitioning into Red Teaming, actively building practical projects in log analysis, SIEM, and threat detection using tools like Kibana, Sumo Logic, and AWS CloudTrail.

📨 [Connect with me on LinkedIn]( www.linkedin.com/in/aditya-kumar-goswami)


