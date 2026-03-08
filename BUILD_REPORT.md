# Build Report – Cover Maker UU

## Project Overview

Cover Maker UU is a web-based tool that generates properly formatted assignment and lab report cover pages for Uttara University students.

The system removes the need for manually designing cover pages in Word or other editors.

---

## Motivation

Many students repeatedly create similar cover pages for assignments and lab reports. This process takes time and often results in inconsistent formatting.

The purpose of this project was to build a simple system where students can generate cover pages instantly.

---

## Development Process

The project was developed in several stages.

### 1. Planning

First, the format of the university cover page was analyzed. The required fields were identified such as:

- Course Name
- Course Code
- Assignment / Experiment details
- Student information
- Teacher information

---

### 2. User Interface Design

The UI was designed to resemble the university portal style.

Key UI features include:

- Assignment / Lab Report tab switching
- Clean form layout
- Modal based developer information
- Mobile responsive design

---

### 3. Form Handling

The form collects user input and sends the data to the backend using a POST request.

JavaScript is used to dynamically show and hide form fields depending on the selected tab.

---

### 4. PDF Generation

The backend uses the TCPDF library.

The process is:

1. Receive form data
2. Format the content
3. Generate the PDF layout
4. Render the final document

The PDF layout was carefully adjusted to match the university format.

---

### 5. Progressive Web App Features

The project also includes basic PWA functionality.

This allows the website to be installed as an app on supported devices.

Features include:

- Service worker
- Web manifest
- Install prompt

---

### 6. Deployment

Instead of using a local development environment, the project was developed and tested directly on the hosting server using the file manager.

The final deployment was done on:

https://covermaker.yzz.me

---

## Challenges Faced

Some challenges during development included:

- Aligning PDF elements correctly using TCPDF
- Handling responsive UI behavior
- Managing tab based form fields
- Implementing PWA install functionality

These issues were solved through iterative testing and adjustments.

---

## Future Improvements

Possible improvements include:

- Multiple university template support
- PDF preview before download
- Additional customization options
- Analytics for usage tracking
