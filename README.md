# Lab 01: Enterprise Infrastructure Audit

**Date:** January __, 2026  
**Status:** Completed  

## Executive Summary
This project analyzes a large-scale enterprise infrastructure outage
from a systems and availability perspective. The focus is on identifying
technical failure points, cascading impacts, and recovery limitations.

## 🎯 Objective
To analyze an enterprise infrastructure failure and identify control-plane
and dependency weaknesses that contributed to extended service downtime.

## 🛠️ Tools Used
- Linux Terminal
- Wireshark
- Draw.io

## 🔍 Technical Findings
1. **Root Cause:** Infrastructure control mechanisms failed due to
   configuration or dependency design weaknesses.
2. **Cascading Impact:** Dependent internal systems failed once primary
   connectivity was lost.
3. **Recovery Limitation:** Remote recovery paths were unavailable,
   requiring alternative access methods.

## 💡 Lessons Learned
Enterprise environments must avoid single points of failure in control
planes and ensure recovery access is isolated from primary network paths.

## 📸 Proof of Work
Supporting diagrams and evidence are stored in the `/proof` directory.

## 🧰 Diagnostics
Error observations and resolution notes are documented in `/diagnostics`.
