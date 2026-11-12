# Siillora
A mobile freelance &amp; service marketplace for students built with Flutter and Supabase, featuring order tracking, QRIS payments, and revision workflows.

# Siillora — Student Freelance & Service Marketplace

![Flutter](https://shields.io)
![Supabase](https://shields.io)
![Dart](https://shields.io)

**Siillora** is a mobile-based service marketplace designed specifically for university students. It connects students who need academic, technical, or creative assistance with skilled student freelancers—featuring end-to-end order tracking, QRIS payment verification, built-in real-time chat, and structured revision workflows.

---

## Project Overview & Role
* **Product Lead & System Analyst:** [@nazrilka](https://github.com) (Product Requirement Document, User Flow, UI/UX Wireframing, Database Design, & QA)
* **Tech Stack:** Flutter (Mobile App) & Supabase (Backend-as-a-Service, Auth, PostgreSQL, & Storage)
* **Architecture Pattern:** Model-View-Controller (MVC) / State Management

---

## Key Features

### 1. Client Mode (User Role)
* **Service Catalog & Search:** Browse and search student services complete with ratings, descriptions, and pricing.
* **Detailed Service View & Portfolio:** Inspect freelancer portfolios (PDF documents or external website links) before placing an order.
* **Custom Order Submission:** Define project requirements, set target deadlines, and upload supporting task materials.
* **QRIS Payment & Verification:** Seamless payment flow with receipt upload (`png`/`jpg`) once an order is approved by the provider.
* **Real-Time Order Tracking & Revision System:** Track order progress (`Under Review` ➔ `In Progress` ➔ `Completed` / `Revision Requested`) and directly request revisions via integrated chat.

### 2. Freelancer Mode (Service Provider Role)
* **Dual-Role Switching:** Easily switch between Client Mode and Service Provider Mode within a single account.
* **Service Management:** Publish, edit, and manage offered services with custom pricing and banners.
* **Order Management Dashboard:** Review incoming requests, accept/reject orders, and deliver final or revised files.
* **Earnings & Withdrawal Wallet:** Track active balance, view transaction history, and request payouts to local banks or e-wallets.

---

## Repository Documentation
All product specifications, functional requirements, and wireframe structures are maintained in the `/docs` directory to guide development and quality assurance:
* [`/docs/PRD.md`](docs/PRD.md) — Product Requirement Document & Page-by-Page Functional Specifications.

---

## Getting Started (For Developers)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Siillora.git
   cd Siillora
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Environment Setup:**
   * Create a `.env` file in the root directory.
   * Add your Supabase project credentials (`SUPABASE_URL` and `SUPABASE_ANON_KEY`). *(Note: Never commit the `.env` file to version control).*

4. **Run the application:**
   ```bash
   flutter run
   ```

---

## Workflow & Contribution Guidelines
* All feature developments must be worked on separate feature branches (e.g., `feature/auth-login`, `feature/order-payment`).
* Submit a **Pull Request (PR)** to the `main` branch upon completion for code review and QA testing by the Product Lead.
