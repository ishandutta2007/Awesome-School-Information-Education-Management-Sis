# Awesome-School-Information-Education-Management-Sis

# Awesome School Information & Education Management (SIS)

> A curated list of top School Information and Education Management (SIS) platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing student records, enrollment, grading, attendance, and school operations.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [PowerSchool SIS](#powerschool-sis)
  - [Infinite Campus](#infinite-campus)
  - [Blackbaud SIS](#blackbaud-sis)
  - [Skyward](#skyward)
  - [Veracross](#veracross)
  - [FACTS SIS](#facts-sis)
  - [Alma SIS](#alma-sis)
  - [Classter](#classter)
- [Open-Source Software](#-open-source-software)
  - [RosarioSIS](#rosariosis)
  - [openSIS](#opensis)
  - [Gibbon](#gibbon)
  - [Frappe Education](#frappe-education)
  - [OpenEduCat](#openeducat)
  - [Skuul](#skuul)
  - [Vidra](#vidra)
  - [AlekSIS](#aleksis)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted School Information and Education Management platforms. These are not open-source but are included as reference points for feature comparison.

### PowerSchool SIS
**Type:** Enterprise K-12 student information system
PowerSchool is one of the most widely deployed K-12 SIS platforms in North America, covering student records, enrollment, scheduling, gradebook, attendance, and state reporting. It is the long-standing enterprise standard for large school districts, with extensive integrations into assessment and learning tools.

### Infinite Campus
**Type:** District-wide SIS with state reporting
Infinite Campus provides a comprehensive SIS for K-12 districts, with real-time data, gradebook, attendance, behavior tracking, and state compliance reporting. Positioned for large districts needing a unified platform across schools.

### Blackbaud SIS
**Type:** SIS for independent and private schools
Blackbaud's SIS is part of its broader education management suite, targeting private and independent schools with admissions, enrollment, billing, and academic management integrated into the Blackbaud ecosystem.

### Skyward
**Type:** K-12 SIS with strong state reporting
Skyward provides SIS and ERP solutions for K-12 schools and districts, with gradebook, attendance, scheduling, and compliance reporting. Known for its focus on state-specific reporting requirements.

### Veracross
**Type:** SIS for independent schools
Veracross provides a unified SIS and school management platform for independent schools, covering admissions, academics, billing, and communications in a single system.

### FACTS SIS
**Type:** SIS with tuition management integration
FACTS SIS (formerly RenWeb) combines student information management with tuition payment processing, making it popular among private and faith-based schools needing integrated billing.

### Alma SIS
**Type:** Modern SIS for K-12
Alma provides a modern, user-friendly SIS for K-12 schools, with gradebook, attendance, reporting, and parent/student portals designed for ease of use.

### Classter
**Type:** All-in-one education management platform
Classter offers SIS, LMS, and school management capabilities in a single platform, targeting K-12 and higher education institutions with modular pricing.

---

## 🟩 Open-Source Software

Self-hosted, community-driven School Information and Education Management tools. The open-source ecosystem spans **mature K-12 SIS platforms**, **ERP-integrated education modules**, and **modern Laravel/Django-based systems**.

### RosarioSIS
**Stack:** PHP / PostgreSQL | **License:** GPL-2.0
RosarioSIS is a free and open-source Student Information System explicitly designed for K-12 schools, also suitable for academies and higher education [citation:4][citation:10]. It is a lightweight, PHP-based application (not built on a heavy ERP) offering a full range of features: student demographics and enrollment, scheduling, gradebook and report cards, attendance, discipline, student billing, and food service modules [citation:2][citation:4]. It requires only PHP and PostgreSQL, making it deployable on a $5/month VPS, and supports multi-school districts in a single installation [citation:2]. Add-ons include Moodle integration, library, hostel, and messaging [citation:4].  
**Best for:** Schools and districts wanting a proven, lightweight open-source SIS that can be self-hosted on modest infrastructure with full K-12 functionality.

### openSIS
**Stack:** PHP / MySQL | **License:** GPL-2.0 (Community Edition)
openSIS is a commercial-grade, scalable SIS designed for larger school districts, with a community edition released under GPL [citation:2][citation:6]. Features include comprehensive student records, granular role-based access control, a constraint-based scheduling engine, gradebook and transcripts, attendance, health/medical tracking, and a unique **transportation module** for bus route management [citation:2]. A REST API enables integration with LMS and payment systems [citation:2]. The community edition (v9.3) requires Apache 2.4+, MySQL 5.7/8.0, and PHP 8.x [citation:6].  
**Best for:** Larger districts wanting enterprise features like transportation management and a REST API, accepting a steeper learning curve and an older UI.

### Gibbon
**Stack:** PHP / MySQL | **License:** GPL-3.0
Gibbon is a well-established open-source school platform (since 2010) with a focus on flexibility and ease of use, suitable for both small schools and larger institutions [citation:4]. It offers student management, attendance, gradebook, timetables, and reporting, with a clean interface and active community support. It is often compared directly with RosarioSIS as a lighter-weight alternative for schools not needing a full ERP [citation:4].  
**Best for:** Schools wanting a proven, actively maintained SIS with a gentler learning curve than enterprise-focused platforms.

### Frappe Education
**Stack:** Python / ERPNext / MariaDB | **License:** GPL-3.0
Frappe Education is an education module built on the ERPNext ecosystem, providing student records, attendance, assessment, and academic term management [citation:4]. It benefits from ERPNext's broader capabilities including finance, HR, and asset management, making it suitable for institutions wanting SIS functionality integrated with a full ERP.  
**Best for:** Organizations already using or planning to adopt ERPNext, wanting education management integrated with finance and operations.

### OpenEduCat
**Stack:** Python / Odoo / PostgreSQL | **License:** LGPL-3.0 (Community)
OpenEduCat is an open-source school management platform built on the Odoo ERP framework, handling student data, attendance, grades, and academic year management [citation:3][citation:4]. It benefits from Odoo's modularity and ecosystem, allowing schools to add CRM, accounting, and other modules as needed. **Trade-off:** The ERP foundation adds complexity and maintenance overhead for small schools that only need core SIS features [citation:4].  
**Best for:** Schools or groups already using Odoo or wanting an SIS tightly integrated with a broader ERP platform.

### Skuul
**Stack:** Laravel 13 / Livewire 4 / MySQL / Redis | **License:** MIT
Skuul is a modern open-source school management system released in October 2026, built on Laravel [citation:9]. It supports multiple organizations and campuses in a single installation, with admissions waitlists, guardian links, gradebooks, exam schedules, report cards, and a finance ledger for payments and refunds [citation:9]. It uses Spatie Permission for **team-scoped roles** (permissions apply to one campus at a time) and includes a **family portal** for students and guardians to view results, attendance, invoices, and notices [citation:9]. **Current limitations:** No public REST API (tokens disabled), Stripe integration exists but checkout is not wired, and the grade calculator can miscount blank marks as zero [citation:9].  
**Best for:** Schools or small groups wanting a modern, MIT-licensed Laravel-based SIS with multi-campus support and a clean family portal, accepting that some integrations are still in development.

### Vidra
**Stack:** Django / Python | **License:** Open Source (with paid customizations)
Vidra is an open-source school management system built on Django, with a broad feature set covering student management, staff/teacher records, class and section management, subjects and curriculum, attendance, exams and grades, fees and finance, timetables, RBAC, and hostel/transport/facility management [citation:7]. It explicitly offers free core features with **optional paid customizations** for advanced modules like library, alumni, and grievance management [citation:7].  
**Best for:** Django/Python-centric teams wanting a feature-rich SIS foundation with the option to pay for extended modules, accepting that the project's maturity and community size should be evaluated before production use.

### AlekSIS
**Stack:** Python / Django | **License:** Open Source
AlekSIS is a Python-based school information system established in 2020, included in comparisons of self-hosted school management platforms [citation:4]. It provides core SIS functionality with a focus on the academic year model and role permissions. It is actively developed but has a smaller community and ecosystem than RosarioSIS or Gibbon [citation:4].  
**Best for:** Python/Django-oriented schools or developers wanting a modern codebase to build upon, accepting a smaller ecosystem.

---

## 📊 Comparison at a Glance

| Software | License | Stack | K-12 Focus | Parent Portal | Self-Hosted | Best For |
|----------|---------|-------|------------|---------------|-------------|----------|
| **PowerSchool** | Proprietary | Cloud | ✅ | ✅ | ❌ | Large K-12 districts |
| **Infinite Campus** | Proprietary | Cloud | ✅ | ✅ | ❌ | District-wide SIS |
| **Blackbaud SIS** | Proprietary | Cloud | (Private) | ✅ | ❌ | Independent schools |
| **RosarioSIS** | GPL-2.0 | PHP/Postgres | ✅ | ✅ | ✅ | Lightweight K-12 SIS |
| **openSIS** | GPL-2.0 | PHP/MySQL | ✅ | ✅ | ✅ | Enterprise features + transport |
| **Gibbon** | GPL-3.0 | PHP/MySQL | ✅ | ✅ | ✅ | Proven flexible SIS |
| **Frappe Education** | GPL-3.0 | Python/ERPNext | (Check) | (Check) | ✅ | ERPNext ecosystem |
| **OpenEduCat** | LGPL-3.0 | Python/Odoo | (Check) | (Check) | ✅ | Odoo ecosystem |
| **Skuul** | MIT | Laravel/MySQL | (Check) | ✅ | ✅ | Modern Laravel + multi-campus |
| **Vidra** | Open Source | Django | (Check) | (Check) | ✅ | Django feature breadth |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source School Information or Education Management (SIS) tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **purpose-built K-12 SIS platforms** (RosarioSIS, openSIS, Gibbon), **ERP-integrated education modules** (Frappe Education, OpenEduCat), and **modern framework-based systems** (Skuul on Laravel, Vidra on Django). **RosarioSIS** is the strongest lightweight choice for K-12 with minimal infrastructure requirements [citation:2], **openSIS** offers the most enterprise features (including transportation) for larger districts [citation:2], and **Gibbon** provides a proven, flexible middle ground [citation:4]. For teams wanting a modern MIT-licensed Laravel codebase, **Skuul** is a notable recent entrant, though some integrations are still maturing [citation:9].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
