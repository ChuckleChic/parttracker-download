#  Part Tracker App

A real-time, cloud-enabled Android application developed to digitize and optimize the part tracking workflow in a manufacturing environment. Designed specifically for paint shops and assembly lines, the app reduces manual errors, enables live shift planning, and brings full traceability to the shop floor.

---

##  Features

### 🗓 **Production Planning**
- Create daily production plans by shift, date, model, color, and parts.
- Plans are auto-fetched at the start of the shift and stored centrally.
- Color and model filters improve user input accuracy.

###  **QR Code System**
- **QR Code Generation**: Unique QR per trolley based on part, model, and quantity.
- **QR Code Scanning**:
  - Location-specific scanning (Paintshop/CTL).
  - Real-time part identification and quantity tracking.
  - Ensures correct part-model-color mapping.

###  **Dashboard & Monitoring**
- View **Planned vs. Produced vs. Closing Balance (CB)** for every part.
- Color-coded progress indicators:
  - 🔴 Low completion
  - 🟠 Moderate progress
  - 🟢 Fully completed
- Nested scrollable views provide quick, detailed overviews.

###  **Live Status & Logs**
- **Cumulative Part Status Panel**:
  - Tracks total scanned, dispatched, received, and used parts.
  - Updates continuously with every scan.

- **Scan History**:
  - Date-wise logs of all scans.
  - Includes trolley ID, timestamps, and part info.
  - Ensures accountability and audit-ready traceability.

### ☁️ **Cloud Integration**
- Firebase Realtime Database for seamless multi-device access.
- Live updates for:
  - Dashboard
  - Scan logs
  - Shift plans
  - Part statuses

- Central collections:
  - `dashboard`, `plans`, `parts`, `scanned_parts`, `used_parts`, `model_production`

---

##  Why This App?

Traditional part tracking relied on:
- Manual whiteboards
- WhatsApp messages
- Verbal updates between paintshop and vehicle assembly

This led to:
- Communication gaps
- Delays in production
- Missing traceability
- No real-time visibility

###  After Implementation:
- Centralized planning and tracking
- Live dashboard for instant visibility
- Improved Material Flow Index (MFI)
- 21% **reduction in lead time per part**
- Inline operations reduce handling and floor space

---

##  Technology Stack

| Component         | Technology              |
|------------------|--------------------------|
| Language          | Kotlin                   |
| Architecture      | MVVM                     |
| Local Storage     | Room Database            |
| Cloud Backend     | Firebase Realtime Database |
| UI Framework      | Android XML              |
| Network Layer     | Volley                   |
| Data Backup       | Google Sheets (optional) |

---

##  Project Outcomes

- 🕒 **Lead Time Reduction**: ~50 sec saved per part
- 📉 **Lower WIP**: Inline sanding/polishing streamlined material flow
- 🔁 **Kaizen Implementation**: Continuous improvement in part handling and tracking
- 📶 **Real-time Insights**: Full visibility of progress and bottlenecks

---

##  Status

✅ Deployed on Paint Shop Floor  
✅ Tested for shift-wise tracking and multi-device sync  
✅ Integrated with Firebase for cloud-based operations  

🔗 **Live Demo / Download**:  
🌐 [Website Link](https://chucklechic.github.io/parttracker-download/)  
📥 [Drive Link](https://drive.google.com/file/d/1cRO7eG6BtA13z3-UBfRH0gzTECD1mW7B/view?usp=sharing)

---

