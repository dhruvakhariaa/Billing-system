Billing System Application
📌 Project Overview
The Billing System Application is a desktop-based software designed for retail stores, supermarkets, and businesses to manage their billing operations efficiently. Built using Python (Django for the backend & PyQt for UI), the application supports multi-role authentication (Admin & Employee), inventory management, and secure transaction processing.

🛠️ Tech Stack
Frontend (UI): PyQt (for a native desktop experience)
Backend: Django with Django REST Framework (DRF)
Database: SQLite (for local use) / PostgreSQL (for production)
Security: Django authentication, JWT for API security, BCrypt for password hashing
Packaging & Deployment: PyInstaller (to generate .exe / .app), Inno Setup (for Windows installers)
🚀 Features
✔ User Authentication & Role-Based Access:

Admin: Can manage users, generate reports, add/edit products, apply discounts, and view analytics.
Employee: Can generate bills and void transactions but cannot edit inventory.
✔ Billing & Transactions:

Scan or search products and generate invoices
Apply discounts and coupons
View past transactions
✔ Inventory Management (Admin Only):

Add, update, or delete products
Track stock availability
✔ Secure Payment Processing:

Supports multiple payment methods (cash, card, UPI)
Secure database encryption for sensitive data
✔ Data Analysis & Reporting:

Generate daily, weekly, and monthly sales reports
View customer purchasing trends

🛠 Future Enhancements
Multi-branch support for large businesses
Barcode Scanner Integration
Mobile App Version (Kivy for Android/iOS)
