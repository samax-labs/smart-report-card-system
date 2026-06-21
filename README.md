# School Report Card Generator & Academic Management System
<img src="fine report.png" width="100%" alt="This is how the system should look like when its done">

> A modern, production-ready web application for managing secondary school academic records and generating professional report cards for **Senior One (S1) through Senior Six (S6)**.

## 🚀 Live Demo

The system is deployed and can be accessed online at:

**https://report-card-system--oronosamuel207.replit.app**

### Embedded Preview (HTML-enabled Markdown platforms)

> **Note:** Some platforms (including GitHub) sanitize HTML and may block or ignore `<iframe>` elements. If the embedded preview does not appear, use the direct link above.

```html
<iframe
    src="https://report-card-system--oronosamuel207.replit.app"
    width="100%"
    height="800"
    style="border:1px solid #d1d5db; border-radius:12px;"
    loading="lazy"
    title="School Report Card Generator">
</iframe>
```

---

# Features

## Authentication & User Roles

* Administrator
* Director of Studies
* Entry Clerk
* Secure login with password hashing
* Session management
* Role-based access control

---

## Student Management

Supports:

* Passport photo upload
* Full name
* Admission number
* Student number
* LIN
* Gender
* Class and stream
* Pay code
* A-Level subject combinations

Functions include:

* Add
* Edit
* Delete
* Search
* Filter
* Bulk import

---

## Academic Support

Supports all classes:

* Senior One
* Senior Two
* Senior Three
* Senior Four
* Senior Five
* Senior Six

### O-Level

* UNEB grading
* Marks
* Grades
* Remarks
* No points displayed

### A-Level

* Marks
* Grades
* Points calculation
* Teacher remarks
* Automatic summaries

---

## Report Card Generator

Produces professional A4 report cards featuring:

* School branding
* Configurable logo
* Blurred watermark
* Student photo
* Subject performance
* Academic summary
* Teacher comments
* Promotion decision
* Signature areas

---

## Bulk Excel Import

* Downloadable Excel template
* Full-class import
* Validation of missing fields
* Duplicate detection
* Score validation
* Error reporting

---

## Teacher & Subject Management

Administrators can:

* Register teachers
* Manage subjects
* Assign teachers to subjects
* Configure subjects without code changes

---

## School Customization

Editable settings include:

* School name
* Motto
* Logo
* Badge/Crest
* Contact details
* Address
* Footer text
* Report title
* Signature images

---

## Export Options

* Single report card PDF
* Combined class report PDF

---

## Local Network Support

The application can be hosted on a lightweight Python server and accessed by multiple devices over the same Wi-Fi network with QR-code-assisted discovery.

---

# Technology Stack

## Backend

* Python
* Flask
* SQLite

## Frontend

* HTML5
* CSS3
* Vanilla JavaScript

## Supporting Libraries

* openpyxl
* Pillow
* qrcode
* SQLAlchemy
* Werkzeug

---

# Project Structure

```text
school-report-card-generator/
│
├── app/
│   ├── auth/
│   ├── dashboard/
│   ├── students/
│   ├── teachers/
│   ├── subjects/
│   ├── reports/
│   ├── imports/
│   ├── settings/
│   ├── templates/
│   ├── static/
│   │   ├── css/
│   │   ├── js/
│   │   ├── svg/
│   │   ├── uploads/
│   │   └── themes/
│   └── models/
│
├── database/
├── uploads/
├── exports/
├── docs/
├── tests/
├── requirements.txt
├── run.py
└── README.md
```

---

# Design Philosophy

The interface follows an Apple-inspired design language with:

* Responsive layouts
* Rounded cards
* Soft shadows
* Clean typography
* Inline SVG icons
* Professional spacing
* Desktop, tablet, and mobile compatibility

---

# Vision

This project aims to provide schools with a reliable and scalable platform for managing academic records, automating report generation, and producing polished report cards while reducing administrative workload and improving data accuracy.
