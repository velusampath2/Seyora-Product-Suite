# Hi, I'm Velmurugan

I build the **Seyora** product suite by **Seyora Technologies** — face attendance & HRMS, clinic / hospital operations, and retail billing — with shared SaaS patterns (plans, usage limits, demo lifecycle, integrations).

## Products at a glance

| Product | App | Focus |
|---------|-----|--------|
| **[Seyora One](#seyora-one)** | Seyora One Admin | Attendance · HRMS · Face recognition |
| **[Seyora Billing](#seyora-billing)** | Seyora Billing Admin | POS · Inventory · Parties · Finance |
| **[Seyora Clinic](#seyora-clinic-admin)** | Seyora Clinic Admin | OP clinic · Queue · Rx · Billing · IPD |

## UI Guides (full walkthrough PDFs)

Annotated screenshots of login, shell, every major page, tabs, drawers, and dialogs:

| Guide | File |
|-------|------|
| Seyora One | [docs/ui-guides/Seyora-One-UI-Guide.pdf](./docs/ui-guides/Seyora-One-UI-Guide.pdf) |
| Seyora Billing | [docs/ui-guides/Seyora-Billing-UI-Guide.pdf](./docs/ui-guides/Seyora-Billing-UI-Guide.pdf) |
| Seyora Clinic Admin | [docs/ui-guides/Seyora-Clinic-UI-Guide.pdf](./docs/ui-guides/Seyora-Clinic-UI-Guide.pdf) |

---

## Seyora One

**Attendance · HRMS · Face recognition**

### Existing features
- Dashboard and approval queues
- My workplace — attendance calendar, roster, work plan, regularization, expenses, tasks, helpdesk
- Leave & absence — leave types, holidays, leave management
- Attendance — live monitor, conflict handling
- Human resource — hiring, onboarding, letters, performance, LMS, assets, exit / clearance
- Payroll — runs, structures, loans, tax, Form 16, multi-country support
- Organization — companies, branches, departments, employees, shifts, devices
- Documents vault and bulk upload
- Reports — daily / monthly, late / OT / absent, biodata, attrition, export
- AI monitoring — unknown persons, live cameras, command center, device health
- Integrations — API keys, webhooks, finance connector

### What’s new / differentiators
- Face recognition attendance with plan-gated advanced liveness / mobile punch
- SaaS subscription access states (grace / restricted / suspended) + plan usage metering
- Super-admin **demo requests** (provision / extend / revoke)
- Multi-company / multi-branch org scope
- Live ops camera command center

---

## Seyora Billing

**Universal retail billing — Billing + Inventory + Customers + Purchases + Payments + Reports**

### Existing features
- Dashboard
- Billing — POS (new bill), bills, held bills, sales return, quotes
- Catalog — products, categories, brands, price lists, promotions
- Inventory — stock, purchases, purchase orders
- Parties — customers, suppliers
- Documents vault
- Reports and finance — GST, payments, expenses
- Organization — users, shops, branches, shop settings
- Integrations — API keys, webhooks, finance connector, offline sync
- Administration — plans, notifications, audit, API reference

### What’s new / differentiators
- Industry modules (grocery / medical / milk-dairy / wholesale, and more)
- Clinic **pharmacy inbox** + FEFO medicine batches
- Milk / dairy subscriptions
- Subscription access + plan limits (users / branches / products / bills)
- Demo requests; offline sync; mobile POS (Flutter)

---

## Seyora Clinic Admin

**OP clinic · Queue · Rx · Billing** (Hospital IPD when `org_mode` allows)

### Existing features
- Dashboard
- Front desk — queue, patients, staff, appointments
- Clinical — doctor desk, patient chart, lab orders
- Inpatient — admissions, beds & wards, ward desk, IP rounds, discharge, OT
- Billing — OP invoices, IP bills, TPA claims, packages, charge master
- Reports
- Organization — users, departments, designations, clinics, sites
- Integrations — ABDM / ABHA, face devices, API keys / webhooks
- Administration — consent / privacy, plans, SaaS billing, usage, retention, audit

### What’s new / differentiators
- **Face check-in** for returning patients
- Multi-clinic / multi-site with Clinic vs Hospital menus
- Public patient self-booking + teleconsult video
- **Pharmacy link** to Seyora Billing (care pharmacy bundle)
- Subscription access banner, plan feature toggles, demo requests
- Link out to **Seyora One** for workforce / attendance

---

## Shared platform patterns (across the suite)

- Role-based admin shells (super admin, tenant admin, staff roles)
- SaaS plans, entitlements, usage limits, and subscription access states
- Demo request lifecycle for prospect tenants
- Org scoping (company / branch or clinic / site)
- API keys, webhooks, and connector-style integrations
- Product UI screenshot guides for handoff and demos

---

## How the products connect

```text
Seyora One          ← workforce / face attendance / HRMS
        ↑
Seyora Clinic Admin ← patients, OP/IP clinical, face check-in
        ↓
Seyora Billing      ← pharmacy / retail POS inventory & bills
```

---

## Stack (high level)

- **Web admin:** React + TypeScript + MUI
- **API:** Python (FastAPI-style cloud services)
- **Ops:** Multi-tenant SaaS with plan entitlements

---

## Contact

Built by **Velmurugan** · [GitHub profile](https://github.com/velusampath2)
