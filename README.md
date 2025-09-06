# Attendance_Tracker
Dynamic Attendance Tracker using Excel, Power Query, and Power BI with automated monthly-to-yearly reporting and interactive dashboard

# 📊 Attendance Tracker Project

## 📌 Project Overview

The **Attendance Tracker** is a reporting and visualization solution built with **Excel, Power Query, and Power BI**.
It allows tracking employee attendance across **12 months**, consolidating the data into a **yearly report**, and creating an **interactive dashboard**.

Any update made in the monthly reports automatically flows into the yearly report and Power BI dashboard with just a refresh.

---

## ⚙️ Workflow

1. **Monthly Attendance Reports**

   * Created a dynamic Excel workbook with **12 sheets (one for each month)**.
   * Used complex formulas to manage and calculate attendance.

2. **Yearly Consolidation**

   * Connected monthly Excel workbook to a separate file using **Power Query**.
   * Combined all 12 months into a single **Yearly Attendance Report**.
   * Any change in the monthly file automatically reflects in the yearly report.

3. **Power BI Dashboard**

   * Connected the Yearly Attendance Report to **Power BI**.
   * Designed an interactive **Attendance Dashboard** with key insights.
   * Updates in the monthly report propagate to the dashboard by clicking **Refresh**.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel** (Formulas, Power Query)
* **Power BI** (Data visualization & Dashboarding)

---

## 🚀 Features

* Dynamic monthly attendance reports.
* Automatic consolidation into a yearly report.
* One-click refresh to update the dashboard.
* Interactive Power BI visuals for quick insights.
* Scalable and easy-to-maintain workflow.

---

## 📂 Project Structure

```
Attendance-Tracker/
│
├── Monthly_Attendance.xlsx    # 12-month attendance (dynamic formulas)
├── Yearly_Report.xlsx         # Consolidated report using Power Query
├── Attendance_Dashboard.pbix  # Power BI dashboard
└── README.md                  # Project documentation
```

---

## ▶️ How to Use

1. Update any sheet in **Monthly\_Attendance.xlsx**.
2. Open **Yearly\_Report.xlsx** → Refresh Power Query to see updates.
3. Open **Attendance\_Dashboard.pbix** in Power BI → Click **Refresh** to sync data.

---

## 📸 Screenshots

*<img width="979" height="547" alt="image" src="https://github.com/user-attachments/assets/d78e68c5-3dc3-4514-a3fc-6719e4da2bce" />*

---

## 📌 Future Improvements

* Automate refresh with Power BI Service.
* Add role-based filtering for employee-level analysis.
* Integrate with SQL database for scalability.
