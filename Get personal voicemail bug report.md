# 🐞 Get Personal Voicemail - Bug Report

## 📌 Overview
This document presents the **bug report** for the **Get Personal Voicemail App (Version 1.0)** based on manual testing conducted from **03.06.2024 - 06.06.2024**. A total of **16 defects** were identified across different modules, categorized by severity.

---

## 🛠 Testing Environment
- **Operating System:** Android 13  
- **Device:** Redmi Note 11  
- **Testing Dates:** 03.06.2024 - 06.06.2024  
- **Total Testing Time:** 20 hours  

---

## 🔴 Defect Summary  

| **Severity** | **Number of Defects** |
|-------------|----------------------|
| Critical    | 1 (6.25%)             |
| Major      | 6 (37.5%)             |
| Average    | 6 (18.75%)            |
| Minor      | 3 (37.5%)             |
| **Total Defects** | **16** |  

---

## 🏷 Defects by Module  

| **Module**       | **Total Defects** | **Severity Breakdown** |
|----------------|--------------|------------------|
| Greetings      | 10           | 1 Critical, 4 Major, 3 Average, 2 Minor |
| Quick Status   | 1            | 1 Major |
| 3 Dots Menu    | 5            | 2 Major, 2 Average, 1 Minor |

---

## 🔥 Top Severity Issues  

### 🔴 Critical Issue (1 Bug)  
- **[QATC-847873] Voicemail greeting does not play for callers.**  
  **Impact:** Users cannot set up proper voicemail greetings, affecting core functionality.  

### 🟠 Major Issues (6 Bugs)  
1. **[QATC-847907] Status is not deleted when clicking on delete.**  
2. **[QATC-847902] Purchase option does not open when clicked.**  
3. **[QATC-847689] Recording starts from the beginning when clicking the resume button.**  
4. **[QATC-847868] The value of time before greeting cannot be changed (always resets to 5).**  
5. **[QATC-848036] UI freezes when clicking 'Settings' multiple times.**  
6. **[QATC-847998] App crashes on rapid navigation between menus.**  

### 🟡 Average Issues (6 Bugs)  
7. **[QATC-847899] UI overlaps when entering long status.**  
8. **[QATC-847905] Greeting preview button does not function properly.**  
9. **[QATC-847910] Volume control slider does not work.**  
10. **[QATC-847912] Settings reset after app restart.**  
11. **[QATC-847919] Status updates are not reflected in real-time.**  
12. **[QATC-847922] Notification sound cannot be changed.**  

### 🟢 Minor Issues (3 Bugs)  
13. **[QATC-847924] Typo in error message ("Credntials" instead of "Credentials").**  
14. **[QATC-847928] Help section does not load correctly.**  
15. **[QATC-847930] App icon missing on some devices (Redmi-specific issue).**  

---

## 📌 Recommendations  
- **Fix Critical Bug First:** Ensure voicemail greetings work correctly.  
- **UI & UX Improvements:** Resolve layout overlaps and interaction issues.  
- **Enhance Stability:** Fix crashing issues in **Settings** and **Purchase Menu**.  

---

## 👥 QA Team  
- **Company:** a1qa  
- **QA Manager:** Dalia Dzhaafar  
- **QA Engineer:** Abdulla Al Bayzed  

---

