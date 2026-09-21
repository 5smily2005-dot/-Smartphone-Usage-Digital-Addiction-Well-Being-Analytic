Smartphone Usage, Digital Addiction & Well-Being Analysis

An analytics pipeline and business intelligence report to process mobile telemetry, isolate dependency biomarkers, and guide digital well-being features.

---

 System Overview
* **Cohort Database:** 7,500 Profiles | 5,308 Users (70.77%) Flagged Addicted.
* **Usage Baseline:** 7.5 hours daily mean | Surges to 10.2 hours on weekends.
* **Habit Infrastructure:** 134.26 Daily Alerts | 97.83 App Opens (Check every 10 mins).
* **Cohort Consequences:** Restricted sleep windows averaging 6.74 hours.
* **Dominant Demographic:** Young adults aged 20–29 comprise 49% of the user base.

---

Project Environment Matrix
* **Hardware Demands:** Core processor (x86/x64) | Minimum 8 GB Volatile Memory (RAM).
* **Software Toolstack:** MySQL Engine | Power BI Desktop Framework | Microsoft Excel.
* **Staged Workspace Artifacts:** 
  * `Smartphone_Usage.csv` (7,500 record baseline data layer).
  * `smartphone_usage.sql` (Relational pipeline transformation logic).
  * `smartphone_usage.pbix` (Interactive visualization dashboard canvas).

---

 Sprint Project Backlog
**Total Velocity:** 4 Sprints | 11 User Stories (`USN-1` to `USN-11`) | 22 Story Points Total.

* **Sprint-1: Environment Setup & Data Pipeline Processing (6 Points)**  
  USN-1 (Setup problem parameters) | USN-2 (Load data to Power BI) | USN-3 (Clean data & age bins).
* **Sprint-2: Metric Layer Optimization & KPI Synthesis (4 Points)**  
  USN-4 (Build 11 metric overview card matrix) | USN-5 (Primary layout of multi-page report).
* **Sprint-3: Interactive Reporting & Visualizations (7 Points)**  
  USN-6 (6-chart report suite) | USN-7 (Isolate the weekend surge gap) | USN-8 (Cross-filtering dimension slicers).
* **Sprint-4: Analytics Integration & Repository Finalization (5 Points)**  
  USN-9 (Document target user personas) | USN-10 (Map feature weight correlation) | USN-11 (Package README).

---

 Key Core Causal Drivers
1. **The Weekend Surge:** Dependent users log 10.2 hours vs. 6.9 hours for non-dependent users; this 3.3-hour expansion gap is the strongest separator.
2. **The Notification Loop:** 134.26 daily system alerts trigger compulsive checking loops, forcing device interaction every 10 waking minutes.
3. **The Fatigue Catalyst:** Extreme daily screen exposure compresses biological rest windows to 6.74 hours, triggering chronic physical exhaustion.

---

 Strategic Product Action Plan
* **Weekend Usage Limits:** Auto-activate restricted mode when weekend use passes 8 hours.
* **Time Caps & Alert Batching:** Cap social media at 2 daily hours and bundle alerts into 3 fixed delivery windows.
* **Interaction Counters & Friction:** Show a live open counter and add a 2-second lag to social app launches.
* **Circadian Sleep Controls:** Force interfaces into monochrome greyscale at 10 PM to protect a healthy 7.5+ hour sleep target.
* **Prevention Threshold Research:** Launch early intervention loops targeting the high-volume moderate addiction tier to stop users from worsening.
