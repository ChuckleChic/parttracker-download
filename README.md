# Part Tracker App

A real-time Android application for tracking parts in manufacturing or assembly lines. It helps teams monitor planned vs actual production data, manage opening balances (OB), and maintain synchronized data across multiple devices using Firebase and a local Room database.

---

##  Features

-  **Part Management**: Track parts by model, color, shift, and date.
-  **Real-time Sync**: Synchronizes data across all devices using Firebase.
-  **Offline Support**: Uses Room Database to allow local storage and access, even without the internet.
-  **QR Scanning**: Quickly scan and identify parts.
-  **Manual Overrides**: Allows manual updates to part quantities, which override and sync correctly.
-  **Dashboard View**: Visualize planned vs actual counts, OB, and discrepancies.

---

##  Tech Stack

| Component       | Technology Used         |
|----------------|--------------------------|
| Language        | Kotlin                   |
| Local Storage   | Room Database            |
| Backend Sync    | Firebase Realtime Database |
| Networking      | Volley                   |
| Architecture    | MVVM (Model-View-ViewModel) |
| UI              | XML Layouts, Material Design |

---


