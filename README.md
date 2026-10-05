# Awesome-Field-Service-Management-FSM

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.

Here is the complete, ready-to-paste README.md for **Awesome-Field-Service-Management-FSM**.

---

# Awesome-Field-Service-Management-FSM

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Work Orders, Dispatch, Scheduling, Mobile Technicians & Invoicing*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Field Service Management (FSM)**. These tools help service businesses dispatch technicians, schedule jobs, track work orders, manage parts inventory, and invoice customers—from residential HVAC and plumbing to commercial facility maintenance.

**Examples** include Microsoft Dynamics 365 Field Service, ServiceMax, Salesforce Field Service, Jobber, Housecall Pro, Simpro, IFS Field Service Management, Praxedo, ServiceTitan, and Zinier (the category leaders).

**Open-source emphasis**: The open-source FSM ecosystem is **focused and purpose-built for specific workflows**. **FlexDesk** is the most complete open-source FSM built specifically for HVAC, plumbing, electrical, and landscaping contractors, with offline-first mobile support, Stripe payments, and a modern React/Next.js stack . **Odoo Field Service** provides a dedicated FSM module within a full ERP suite, connecting dispatch to CRM, invoicing, and inventory . **Grash CMMS (Atlas CMMS)** is a self-hosted CMMS with 345+ GitHub stars, covering work orders, preventive maintenance, and asset management . This section documents these focused solutions honestly.

## 📖 Table of Contents

- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)

## ☁️ SaaS/Hosted Platforms

> **📊 Market Context**: The global field service management market is estimated at **~$5.5B in 2026**, growing toward **~$15B by 2032**. The sector is **moderately fragmented** — **ServiceTitan** dominates the trades and residential services segment, **Salesforce** and **Microsoft** lead the enterprise tier through CRM/ERP integration, and **Jobber** and **Housecall Pro** compete aggressively on SMB pricing and ease of use. **Pricing varies dramatically**: Jobber starts at **$39/month** for 1 user, Housecall Pro at **$79/month** for up to 5 users, ServiceTitan requires a **custom quote** (typically $400–$500/month per technician for full platform), and Salesforce Field Service starts at **$25/user/month** (Salesforce Essentials) but enterprise editions with add-ons run **$100–$200+/user/month** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.

| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Dynamics 365 Field Service](https://dynamics.microsoft.com/en-us/field-service/)** | **Microsoft's enterprise FSM.** Work orders, scheduling, IoT integration, and remote assistance within Dynamics 365. | **$105/user/month** (Field Service); **$195/user/month** (Field Service Premium) . | **None** — 30-day trial via Dynamics 365 trial. | **~$281B revenue (Microsoft FY2025)** |
| **[Salesforce Field Service](https://www.salesforce.com/service/field-service/)** | **Enterprise FSM within Salesforce Service Cloud.** Scheduling, dispatch, mobile app, and asset management. | **Starter**: **$25/user/month** (Salesforce Essentials) . **Enterprise editions** with Field Service add-on typically run **$100–$200+/user/month** . | **None** — 30-day trial available. | **~$37.9B revenue (Salesforce FY2025)** |
| **[ServiceTitan](https://www.servicetitan.com/)** | **The dominant platform for residential trades.** HVAC, plumbing, electrical, and garage door contractors. | **Custom quote required** — typically **$400–$500/month per technician** for the full platform . | **None** — demo required. | **Private (~$9B valuation est.)** |
| **[ServiceMax](https://www.servicemax.com/)** | **Enterprise FSM for asset-intensive industries.** Field service, depot repair, and contract management. | **Custom enterprise pricing** — quote required. | **None** — demo required. | **Part of PTC** |
| **[Jobber](https://getjobber.com/)** | **SMB-focused FSM for home service businesses.** Scheduling, invoicing, and client management. | **Core**: **$39/month** (1 user). **Connect**: **$129/month** (up to 5 users). **Grow**: **$249/month** (up to 10 users) . | **14-day free trial** . **No perpetual free tier**. | **Private (~$100M+ ARR est.)** |
| **[Housecall Pro](https://www.housecallpro.com/)** | **Home service FSM.** Scheduling, dispatch, invoicing, and payments for residential contractors. | **Basic**: **$79/month** (up to 5 users). **Essentials**: Higher tiers . | **14-day free trial** . **No perpetual free tier**. | **Private (~$1B+ valuation est.)** |
| **[Simpro](https://www.simprogroup.com/)** | **FSM for commercial trades and service contractors.** Job management, scheduling, and inventory. | **Custom pricing** — quote required. | **Demo** required. | **Private (~$300M+ revenue est.)** |
| **[Praxedo](https://www.praxedo.com/)** | **European FSM platform.** Scheduling, dispatch, and mobile technician tools. | **Custom pricing** — quote required. | **Demo** required. | **Private (Praxedo)** |

## 🔓 Open-Source GitHub Projects

Sorted by relevance to field service workflows. Star badge links to each repo's stargazers page.

| Repo | Description | Stars |
|------|-------------|-------|
| **[Grash CMMS (Atlas CMMS)](https://github.com/grashjs/cmms)** — **The most complete self-hosted open-source CMMS for field service.** **345+ stars, 74 forks, actively maintained** . **TypeScript-based** web and mobile application . **Feature set**: Work orders with time logging and priorities, preventive maintenance with automatic triggers, asset management with hierarchies and service history, inventory with stock alerts and purchase orders, analytics with compliance and cost tracking, Google Maps integration for locations, and customizable user roles and workflows . **Dual-licensed**: GPLv3 open-source core with optional commercial license for white-labeling or SSO . **Docker deployment** . | [![Stars](https://img.shields.io/github/stars/grashjs/cmms?style=social&color=white)](https://github.com/grashjs/cmms/stargazers) | ~345 |
| **[Odoo Field Service](https://github.com/odoo/odoo)** — **Dedicated FSM module within a full ERP suite.** **Community Edition is free and open source (LGPLv3)** . **Key advantage**: Service calls connect directly to CRM, sales orders, inventory, and accounting within the same system . **Features**: Scheduling, map-based dispatching, mobile app for technicians, work order tracking, invoicing, and inventory management . **Tradeoff**: Setup requires technical expertise, and the free Community Edition is largely self-supported; the Enterprise edition (not open source) adds paid support and extra features . **Best for**: Businesses wanting a single source of truth for their entire operation . | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | ~45,000 |
| **[FlexDesk](https://github.com/Paulo-BatistaFerraz/flexdesk)** — **Open-source FSM built for HVAC, plumbing, electrical, and landscaping contractors.** **Modern tech stack**: NestJS backend, React 18/Next.js frontend, React Native mobile, PostgreSQL, Prisma ORM . **Features**: Job management with status tracking and priority levels, client CRM with leads pipeline, invoicing with Stripe payments, team scheduling with drag-and-drop weekly calendar, role-based access (Admin/Dispatcher/Technician), Google Maps routing, **offline-first** mobile support, multi-tenant with row-level security, SMS/email via Twilio/SendGrid . **Monorepo** with pnpm workspaces + Nx . | [![Stars](https://img.shields.io/github/stars/Paulo-BatistaFerraz/flexdesk?style=social&color=white)](https://github.com/Paulo-BatistaFerraz/flexdesk/stargazers) | ~200 |
| **[Nexus Field Service](https://github.com/azaharizaman/nexus-field-service)** — **Framework-agnostic FSM engine for work orders, dispatch, and SLA tracking.** **Tiered feature set**: **Tier 1 (Basic)**: Manual work order creation, technician scheduling, parts consumption, customer signature capture (SHA-256 hash), PDF service reports. **Tier 2 (Contracts)**: Service contract management, SLA deadline tracking and breach alerts, automated preventive maintenance scheduling, checklist templates. **Tier 3 (Enterprise)**: ML-powered technician assignment, VRP route optimization, RFC 3161 cryptographic timestamp signing, event sourcing for compliance . **Tech**: PHP/Composer package. **Dependencies**: Requires Nexus ecosystem packages (Party, Backoffice, Inventory, Warehouse, Scheduler, etc.) . | [![Stars](https://img.shields.io/github/stars/azaharizaman/nexus-field-service?style=social&color=white)](https://github.com/azaharizaman/nexus-field-service/stargazers) | ~50 |
| **[Fieldboard](https://www.npmjs.com/package/fieldboard)** — **React dispatch board component for field service work.** **MIT licensed**, React 19 + Tailwind v4, **no backend required** . **What makes it FSM-specific**: **Travel-aware scheduling** (won't offer slots the crew can't drive to in time), **skill matching** (flags unticketed assignments), **unassigned backlog** (virtualized for 500+ jobs), **risk detection** (double-booked, late, unticketed—ranked by severity), **shift boundaries** with capacity bars, **bulk assignment** ("Fill this technician's day"), **locale-aware** time formatting, and **undo that names itself** . **Use case**: Embed a dispatch board into an existing field service app. | [![Fieldboard](https://img.shields.io/badge/Fieldboard-NPM-blue)](https://www.npmjs.com/package/fieldboard) | N/A |

**Additional open-source options worth exploring:**

| Repo | Description |
|------|-------------|
| **[openMAINT](https://github.com/tecnoteca/openmaint)** — Open-source CMMS/IWMS for buildings, facilities, and asset portfolios. Best when "field" means facilities and equipment, not outside customers . |
| **[WCC CMMS](https://github.com/devdave-online/WCC_CMMS)** — Free unlimited-seat CMMS with 34 languages, offline Android companion, and AI agent support. PHP/MySQL. Apache 2.0 + Commons Clause (free for own use, cannot sell as hosted service) . |
| **[SuperCMMS](https://github.com/SuperCMMS/Open-Source-CMMS)** — Open-source CMMS backend codebase with asset management, work orders, preventive maintenance, checklists, QR codes, and inventory. **Note**: Work in progress, not yet production-ready . |
| **[Tangleout](https://wordpress.org/plugins/tangleout/)** — WordPress plugin for work order management. Free tier limited to 10 active jobs; Pro removes limits. Works for plumbers, electricians, and tradespeople . |

## 🤝 How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Field service platforms handle sensitive customer, payment, and location data; ensure compliance with GDPR, CCPA, and applicable data protection regulations.
- **Open-source reality**: The open-source ecosystem for FSM is **focused and purpose-built for specific workflows**. **FlexDesk** is the most complete open-source FSM built specifically for contractors . **Odoo Field Service** provides a dedicated FSM module within a full ERP suite with deep integration to accounting and inventory . **Grash CMMS** delivers a self-hosted CMMS with 345+ stars and active development . However, **commercial platforms** (ServiceTitan, Jobber, Housecall Pro, Salesforce) provide **polished mobile apps, mature dispatch boards, trade-specific features (flat-rate pricebooks, memberships), and enterprise support** that open-source alternatives require significant configuration to match . The open-source path is **genuinely viable** for organizations with strong IT capacity or a reliable implementation partner.
- **Key distinction**: **Unibody CMMS** (Grash, openMAINT) manage internal maintenance of assets and facilities. **Contractor FSM** (FlexDesk, Odoo Field Service) manages dispatching technicians to outside customers with CRM, estimates, and invoicing . Choose based on whether your "field" means your own facilities or your customers' locations.

---

**Made for service contractors, field operations managers, facility maintenance teams, and IT administrators.**
Let's make field service management more open, transparent, and accessible.
