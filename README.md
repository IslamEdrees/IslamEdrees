<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00FFB3,100:111827&height=210&section=header&text=ISLAM%20EDREES&fontColor=FFFFFF&fontSize=48&animation=fadeIn"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?color=00FFB3&size=26&center=true&vCenter=true&width=900&lines=VoIP+Engineer+%7C+Asterisk+%7C+SIP;Handling+50K%2B+Calls%2FDay;Real-Time+Monitoring+%26+Troubleshooting;Call+Center+Architecture;High+Availability+Systems">
</p>

---

## LIVE SYSTEM SNAPSHOT

```bash
$ voip-status --live

SIP Registrations : OK (2/2)
Active Calls      : 148
Calls Today       : 51,284
System Load       : 32%
Latency           : 11 ms
Packet Loss       : 0.1%
Alerts            : 0

Routing Engine    : Kamailio (LB Active)
Media Server      : Asterisk Cluster (Healthy)
Monitoring        : Prometheus + Grafana (Running)

Status            : ✔ ALL SYSTEMS OPERATIONAL
```

---

##  REAL-TIME STATUS

<p align="center">
  <img src="https://img.shields.io/badge/SIP-ONLINE-00FFB3?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/RTP-STABLE-3B82F6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/LATENCY-11ms-10B981?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/ALERTS-0-111827?style=for-the-badge"/>
</p>

---

## SYSTEM ACTIVITY

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=IslamEdrees&theme=react-dark&bg_color=111827&color=00FFB3&line=00FFB3&point=3B82F6&area=true&hide_border=true"/>
</p>

---

## SYSTEM ARCHITECTURE (Real Deployment)

<p align="center">
  <img src="https://raw.githubusercontent.com/IslamEdrees/IslamEdrees/main/architecture.png" width="900"/>
</p>

---

## ⚙️ ARCHITECTURE BREAKDOWN

```bash
Inbound Calls:
Telecom → PRI → SBC → Asterisk → Queue → Agents

Inter-Site:
Sites connected via VPN (WAN)

Load Distribution:
PRI 1 → 25%
PRI 2 → 25%
PRI 3 → 50%
```

---

## 🚀 CORE SYSTEMS (Production)

<table>
<tr>
<td width="50%">

### 📡 VoIP Monitoring Platform

```bash
$ monitor --voip
SIP Trunks   : ACTIVE
RTP Streams  : MONITORED
Alerts       : ENABLED
```

✔ Real-time SIP/RTP monitoring  
✔ Automated alerting  

💣 Impact:
- ↓ Troubleshooting **70%**

👉 https://github.com/IslamEdrees/Asterisk-Monitoring-with-Prometheus-Grafana

</td>

<td width="50%">

### 🔔 Alerting System

```bash
$ alert --system
Event: SIP DOWN → Telegram
```

✔ Instant alerting  
✔ Failure detection  

💣 Impact:
- ↓ Response time **45%**

👉 https://github.com/IslamEdrees/SwitchMonitoring-telegram

</td>
</tr>
</table>

---

## 🔥 CASE STUDY — One-Way Audio

```bash
Problem:
Calls connected but no audio

Root Cause:
NAT + RTP misconfiguration

Fix:
rtp_symmetric=yes
rewrite_contact=yes
direct_media=no
```

```bash
Result:
✔ Audio restored
✔ Issues reduced ~70%
✔ Stable RTP flow
```

---

## 🛠️ TECH STACK

<p align="center">
  <img src="https://skillicons.dev/icons?i=linux,docker,kubernetes,ansible,python,bash,git"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Asterisk-VoIP-00FFB3?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Kamailio-LB-3B82F6?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/SIP-RTP-111827?style=for-the-badge"/>
</p>

---

## 📡 CONTACT

<p align="center">
  <a href="https://linkedin.com/in/islam-hassan-edres">
    <img src="https://img.shields.io/badge/LinkedIn-Hire%20Me-3B82F6?style=for-the-badge"/>
  </a>
  <a href="mailto:islamedres.hassan@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-10B981?style=for-the-badge"/>
  </a>
</p>

---

<p align="center">
  <b>Available for VoIP / Asterisk / SIP Engineering Roles</b>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:00FFB3&height=150&section=footer"/>
</p>
