# price-list-combiner

A high-performance full-stack web application designed to automate e-commerce data management. It bridges the gap between diverse supplier price lists and OpenCart store databases.

[Live Demo](https://price-combiner.netlify.app/) | [User Guide](https://price-combiner.netlify.app/guide)

## 🛠 Business Logic & Workflow
This tool solves the "manual data entry" problem for online stores:
1. **Sync:** Fetches categories and products from an OpenCart instance.
2. **Train:** A custom UI to define parsing rules for various Excel/CSV layouts.
3. **Map:** Intelligent mapping of supplier items to existing store products.
4. **Combine:** Generates a consolidated Excel file or a **direct SQL update script**.

## 💻 Tech Stack
- **Frontend:** React 19, TypeScript, Redux Toolkit, MUI.
- **Performance:** `react-virtualized` for handling large datasets smoothly.
- **Backend (Local Node.js):** Express, `better-sqlite3` for fast persistence.
- **Data:** `SheetJS` (xlsx) for complex spreadsheet processing.

## 🔒 Project Status
The core logic of this project is currently in a **private repository** as it contains proprietary integration details. This repository serves as a documentation hub and feature showcase.
