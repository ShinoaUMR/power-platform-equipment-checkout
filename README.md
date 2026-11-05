# Equipment Checkout Management System

A complete end-to-end solution built on the Microsoft Power Platform to manage IT equipment checkouts, automate overdue status updates, and visualize usage data.

## 🏗️ Architecture & Data Model
The system is built on Microsoft Dataverse using a relational data model (1:N relationship).
<img width="522" height="152" alt="Equipment Checkout Record Table_ drawio" src="https://github.com/user-attachments/assets/68612713-c368-41c1-9113-c68d66e28d7a" />


## 📱 Model-Driven App
A user-friendly Model-driven app was created with custom forms and views. The custom `Not Returned` view filters for "Checked Out" and "Overdue" items, sorted by the earliest Due Date.
<img width="1900" height="385" alt="Not Returned filter view" src="https://github.com/user-attachments/assets/62871189-b1e1-472c-8d68-b76d126242d6" />

## ⚙️ Power Automate Automation
A scheduled cloud flow runs daily to automatically check for items that are past their due date. If an item is "Checked Out" and the Due Date has passed, the flow updates its status to "Overdue".
<img width="1894" height="938" alt="Power Automate Flow Diagram" src="https://github.com/user-attachments/assets/d3d7445a-5aaa-4c77-965b-8014f9b21aa0" />

## 🛠️ Tech Stack
- Microsoft Dataverse
- Power Apps (Model-driven)
- Power Automate
- Power BI (Coming Soon)
