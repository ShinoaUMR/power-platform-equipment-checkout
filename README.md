# Equipment Checkout Management System

A complete end-to-end solution built on the Microsoft Power Platform to manage IT equipment checkouts, automate overdue status updates, and visualize usage data.

## 🏗️ Architecture & Data Model
The system is built on Microsoft Dataverse using a relational data model (1:N relationship).
*(Insert your Draw.io ER Diagram image here)*

## 📱 Model-Driven App
A user-friendly Model-driven app was created with custom forms and views. The custom `Not Returned` view filters for "Checked Out" and "Overdue" items, sorted by the earliest Due Date.
*(Insert your App View screenshot here)*

## ⚙️ Power Automate Automation
A scheduled cloud flow runs daily to automatically check for items that are past their due date. If an item is "Checked Out" and the Due Date has passed, the flow updates its status to "Overdue".
*(Insert your Flow Diagram screenshot here)*

## 🛠️ Tech Stack
- Microsoft Dataverse
- Power Apps (Model-driven)
- Power Automate
- Power BI (Coming Soon)
