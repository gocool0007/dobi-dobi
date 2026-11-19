# DOBI-DOBI — Multi-Vendor Laundry Service Marketplace

Full-stack multi-vendor laundry marketplace connecting customers with independent laundry service providers across three dedicated interfaces: **Customer App**, **Provider App**, and **Admin Dashboard**.

## Quick Start

```bash
pip install -r requirements.txt
cd backend
uvicorn app:app --host 0.0.0.0 --port 8000
```

Open `http://localhost:8000` in your browser.

## Demo Accounts

- **Customer**: `ananya@example.com` / `Customer@123` (or Mobile OTP `+919840112233`, OTP `123456`)
- **Provider (Approved)**: `ramesh@freshfold.in` / `Provider@123`
- **Provider (Pending)**: `vikram@velacherywash.in` / `Provider@123`
- **Admin**: `admin@dobidobi.in` / `Admin@123`
