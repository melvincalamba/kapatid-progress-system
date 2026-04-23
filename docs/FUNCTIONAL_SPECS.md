# Functional Specifications (High-level)
## System Overview:

* Web-based application (React frontend + Node.js/Express backend + PostgreSQL)
* User authentication (login para sa mentors)
* CRUD operations para sa Kapatid records
* Simple dashboard at filtering

## Key Features in Detail:

* Authentication → Login / Logout (MVP: simple email/password or Google later)
* Kapatid Management → Create, Read, Update, Delete records
* Progress Tracking → Visual stage movement (optional progress bar or colored tags)
* Reporting → Basic counts per stage (MVP)

## Non-functional (MVP):

* Mobile-friendly (responsive design)
* Fast loading
* Data stored securely in PostgreSQL
* Docker-ready (mula Week 1)

# MVP Scope (Minimum Viable Product)
## In Scope (Gagawin sa unang version):

* User login (basic)
* Add / View / Update / Delete Kapatid records
* Fields: Name, Classification (dropdown), Progress Stage (dropdown with exact stages mo), Mentor (text or dropdown), Details (textarea)
* Simple list view with search + filter by progress or classification
* Basic dashboard (counts per stage)
* Responsive UI (React)

## Out of Scope:

* Advanced reporting / charts
* Notifications (email/SMS reminder for follow-up)
* Kapatid self-view portal
* Attachment upload (photos, documents)
* Multi-tenant (multiple churches/groups)
* Role-based access beyond basic mentor

## Success Criteria for MVP:

* Isang mentor ay makakapag-add at mag-update ng 10+ kapatids nang walang issue.
* Makikita agad ang current progress at details.
* Hindi na kailangan ng Excel o notebook para sa basic tracking.