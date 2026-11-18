# Kopipiro Coffee Shop Application

Kopipiro is a web-based coffee shop management system featuring a customer-facing storefront, a staff and owner dashboard, role-based access control, product catalog filtering, and an order management API built with PHP and MySQL.

## Features

* **Customer Storefront:** Browse products by category, view member-exclusive discounts, manage cart items, and place orders.
* **Role-Based Access Control:** Secure user session management supporting Customer, Cashier, and Owner roles.
* **Staff Dashboard:** Real-time order tracking, status updates, sales reporting, and analytics charts.
* **Admin Capabilities:** Product management, image uploads, and Excel data export.
* **API Integration:** Automated menu seeding from public APIs and Midtrans sandbox payment gateway support.

## Project Directory Structure

```text
kopipiro/
├── api/
│   ├── auth.php
│   ├── export.php
│   ├── midtrans_notify.php
│   ├── orders.php
│   ├── pay.php
│   ├── products.php
│   └── sales.php
├── tools/
│   ├── seed_base.php
│   └── seed_from_api.php
├── uploads/
├── config.php
├── dashboard.html
├── helpers.php
└── shop.html
