# Incident Handler’s Journal

## Overview
Documented an incident involving unusual account behavior using a structured incident response (IR) format. This demonstrates the ability to communicate clearly, think analytically, and follow IR procedures.

---

## 📝 Incident Summary
A user account exhibited multiple failed login attempts followed by a successful login from an unusual IP address. Activity suggested possible credential compromise.

---

## 🕒 Timeline
- **08:12** – First failed login  
- **08:14** – Additional failed login attempts  
- **08:17** – Successful login from unusual IP  
- **08:22** – Elevated privilege command executed  
- **08:25** – Account locked pending investigation  

---

## 🔍 Impact Analysis
- Potential unauthorized access  
- Possible lateral movement  
- Uncertain if data was accessed or modified  

---

## 🔧 Containment Steps
- Locked compromised account  
- Forced password reset  
- Reviewed authentication logs  
- Checked for privilege escalation  
- Monitored system for continued activity  

---

## 🧠 Root Cause Analysis
Likely cause: weak password reused from another compromised service.  
No MFA was enabled on the account.

---

## 🛡 Lessons Learned
- Enforce multi-factor authentication  
- Strengthen password policies  
- Monitor for repeated failed login attempts  
- Improve alerting thresholds  

---

## ✅ Outcome
Incident contained successfully, and preventative controls were recommended to reduce future risk.
