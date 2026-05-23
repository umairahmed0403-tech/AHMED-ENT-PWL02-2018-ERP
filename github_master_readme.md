# Ahmed Enterprises ERP - Custom Bonded Warehouse Management System

## Project Overview
This repository contains the high-fidelity frontend code for the Ahmed Enterprises ERP system (PWL-02/2018PB). The system is designed as a mobile-first, professional logistics and bonded warehouse management platform.

## Project Structure
The project is organized into the following functional modules:

### 1. Core Operations
- `index.html`: Project Hub / Sitemap
- `NOC_Management.html`: Central hub for NOC tracking and applications.
- `Inbound_GD_Entry.html`: Physical receiving and cargo manifest declaration.
- `Warehouse_Inventory.html`: Real-time stock tracking with aging and weight alerts.
- `Ex-Bond_GD_Entry.html`: Customs release and partial release management.

### 2. Gate & Logistics
- `Gate_Pass_Registry.html`: OCR-enabled gate-out entry and vehicle logging.
- `Daily_Gate_Pass_Report.html`: Daily throughput and crane loading income monitoring.
- `Location_Occupancy.html`: Visual breakdown of warehouse capacity utilization.

### 3. Accounting & Finance
- `Accounting_Ledger.html`: Comprehensive transaction history (PKR).
- `Cash_Bank_Receipts.html`: Inflow management.
- `Expenses_Payments.html`: Outflow and utility tracking with receipt uploads.
- `Financial_Reports.html`: Income Statement (P&L) and Balance Sheet.

### 4. Importer Portal
- `Importer_Login.html`: Secure authentication for clients.
- `Importer_Dashboard.html`: Client-side view of stored goods, duty status, and D.O. creation.
- `Consolidated_Invoice.html`: Monthly automated billing with PDF export support.

### 5. Administration & Automation
- `Notification_Editor.html`: SMS/Email/WhatsApp template management for compliance alerts.
- `Service_Contracts.html`: Legal undertaking and service agreement documentation.

## Tech Stack
- **HTML5 / CSS3**
- **Tailwind CSS**: For utility-first styling and responsive design.
- **Lucide Icons / Material Symbols**: For consistent iconography.
- **Google Fonts (Inter / IBM Plex Sans)**: For industrial-grade legibility.

## Deployment Instructions
1. Download the full project ZIP from Stitch.
2. Upload the extracted files to this GitHub repository.
3. Ensure `index.html` is in the root directory for proper hosting (e.g., via GitHub Pages).
