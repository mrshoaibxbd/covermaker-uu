# System Architecture

## Overview

The system follows a simple client-server architecture.

User input is processed on the server and converted into a formatted PDF document.

---

## Architecture Flow

User → Web Interface → PHP Backend → TCPDF Engine → Generated PDF

---

## Frontend

The frontend handles:

- User input forms
- Tab switching between Assignment and Lab Report
- Responsive layout
- Modal interactions

Technologies used:

- HTML
- CSS
- JavaScript

---

## Backend

The backend is responsible for:

- Receiving form data
- Processing input fields
- Formatting content
- Passing formatted content to TCPDF

Language used:

- PHP

---

## PDF Engine

The TCPDF library is used to generate the PDF.

It allows precise control over:

- Text alignment
- Layout
- Page formatting
- Font handling

---

## Deployment Environment

The project is hosted on a shared hosting server.

The website is accessible at:

https://covermaker.yzz.me

No database is used in this project since all data is processed temporarily during PDF generation.
