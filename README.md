# TallyPrime Web ERP (Release 7.0 Cloud Edition)

A complete, keyboard-first web-based ERP replica of **TallyPrime** featuring double-entry bookkeeping, weighted-average inventory valuation, Indian GST compliance (`GSTR-1`, `GSTR-3B`, `e-Invoice IRN/QR`), Prime Banking (`BRS`), visual analytics dashboard, and an integrated **10-Agent Engineering & QA Command Center**.

## Key Features
- **Gateway of Tally & Universal `Alt+G` Go-To Bar**: Instant keyboard-driven navigation across Masters, Vouchers, Reports, and Statutory modules.
- **Complete Voucher Engine (`F4`–`F9`, `Alt+F5`, `Alt+F6`)**:
  - `F4`: Contra | `F5`: Payment | `F6`: Receipt | `F7`: Journal | `F8`: Sales | `F9`: Purchase | `Alt+F5`: Debit Note | `Alt+F6`: Credit Note.
  - Supports both **Item Invoice Mode** (auto-computing CGST/SGST/IGST & HSN summary) and **Accounting Double-Entry (`Dr/Cr`) Mode** (`Ctrl+H`).
- **Real-Time Financial & Inventory Statements**:
  - **Balance Sheet** (Schedule III & Horizontal), **Trading & Profit & Loss A/c**, **Trial Balance**, **Day Book**, **Stock Summary**, **Ratio Analysis**, and **Ledger Vouchers**.
- **Connected GST & Prime Banking**:
  - Live `GSTR-1` & `GSTR-3B` computation, JSON export for GST Offline Tool, printable GST Tax Invoices with QR Code & IRN, and Bank Reconciliation (`BRS`).
- **Multi-Agent Engineering Team Hub**:
  - Built-in 12-point automated QA test runner and continuous improvement toggle board.

## Live Deployment on GitHub Pages
Push this repository to `https://github.com/sksanjutiwari/tally-prime-web` and enable **Settings -> Pages -> Source: GitHub Actions** to publish live at `https://sksanjutiwari.github.io/tally-prime-web/`.
