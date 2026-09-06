# Vevel Ventures – Enterprise Resource Management (ERM) System

> **🚀 From Quotation to Invoice – A complete business management tool for commercial refrigeration distributors.**

---

## 📖 Overview

Vevel Ventures ERM is a lightweight, browser‑based business management system designed specifically for **commercial refrigeration distributors** in India. It streamlines the entire sales cycle – from customer inquiry and quotation generation to tax‑compliant invoicing and payment tracking.

Built as a **single‑page HTML application**, it requires **no server**, **no database**, and **no installation** – just open it in a browser and start generating professional GST‑compliant documents immediately.

This tool is the **first step** toward a full‑fledged ERP, currently managing:

- ✅ Quotations
- ✅ Proforma Invoices
- ✅ Tax Invoices (GST‑compliant)
- ✅ Advance Payment Receipts
- ✅ Purchase Orders (to distributors)

---

## 🎯 Why This ERM?

| Challenge | Solution |
| :--- | :--- |
| ❌ Manual document creation with Word/Excel | ✅ One‑click generation with auto‑filled fields |
| ❌ No GST compliance | ✅ Built‑in CGST/SGST (9% each) with HSN support |
| ❌ No document numbering | ✅ Auto‑generated numbers (`VV/<type>/DD-MM/xxxx`) |
| ❌ No business tracking | ✅ Export to CSV for Excel‑based accounting |
| ❌ Expensive ERP software | ✅ **100% free**, runs offline in any browser |

---

## ✨ Features

### 📄 Document Generation
- **Quotation** – Price estimates with bank details toggle.
- **Proforma Invoice** – Formal order confirmation & advance payment request.
- **Tax Invoice** – GST‑compliant bill with E‑Way Bill toggle.
- **Advance Payment Receipt** – Acknowledgment of partial payments.
- **Purchase Order** – Order to your distributors.

### 🧮 Smart Calculations
- Automatic **tax calculation** (18% GST).
- **CGST / SGST split** (9% each).
- **Amount in words** (Indian numbering system – Lakhs/Crores).
- **70% / 30%** advance/default payment terms.

### 🖨️ Print & Export
- **Print directly** or **Save as PDF** (browser print).
- **Export to CSV** for Excel‑based record keeping.
- **Responsive design** – works on desktop, tablet, and mobile.

### 💾 Data Management (Roadmap)
- Customer Master – auto‑fill customer details.
- Product Master – auto‑fill product details (HSN, pricing).
- Transaction Log – auto‑log every invoice to Excel/Google Sheets.

### 🎨 UX Highlights
- **Collapsible** operational terms for cleaner UI.
- **Bank details toggle** – show/hide bank info.
- **Live preview** – see the document update in real time.
- **One‑click printing** – directly from the sidebar.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend** | HTML5, CSS3, Vanilla JavaScript |
| **Styling** | Custom CSS with CSS Variables (no frameworks) |
| **Data** | JSON (inline) + CSV export |
| **Print Engine** | Native `window.print()` with @page CSS |
| **Storage** | Browser `localStorage` for doc numbering |
| **Deployment** | **GitHub Pages** / Any static hosting |

---

## 📂 Repository Structure
