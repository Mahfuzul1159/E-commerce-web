# ToGoFlow — Lightweight E-commerce Website

**ToGoFlow** is a clean, responsive single-page e-commerce web built with plain HTML, CSS and JavaScript.  
It includes product listing, product detail, cart UI, contact & order forms and integration points for Google Sheets (Google Apps Script) to collect orders and contact messages.  

> Live demo: **[togoflow.netlify.app](https://togoflow.netlify.app/)**  
> **Developed by:** [Sheikh Mahfuzul Islam Rafi](https://mahfuzul-islam-rafi-portfolio.netlify.app/#home)

---

## Table of contents

- [Project overview](#project-overview)  
- [Features](#features)  
- [Tech stack](#tech-stack)     
- [Folder structure](#folder-structure)  


---

## Project overview

**ToGoFlow** is a lightweight, responsive e-commerce web designed to showcase products and capture customer interactions without the complexity of a full backend system.  
It provides a clean and modern shopping experience — featuring product catalogs, detailed views, a shopping cart, and checkout flow.  

Form submissions (orders and contact messages) are seamlessly integrated with **Google Sheets via Google Apps Script**, enabling simple order management and record-keeping directly in spreadsheets.  

This project is ideal for:  
- Small businesses wanting a static website with lightweight order handling   
- Anyone seeking a customizable starting point for a minimal e-commerce solution  

---

## Features

- Responsive product grid + product detail page.  
- Add to cart, quantity update, remove item and checkout modal. 
- Order form (Cash on Delivery flow) and contact form.
- Sends orders and contact messages to Google Sheets via Google Apps Script web apps (two endpoints). 
- No external frameworks — easy to customize and deploy.

---

## Tech stack

- HTML5, CSS3 (single file)  
- Vanilla JavaScript (DOM manipulation, fetch)  
- Google Apps Script (backend for form submissions -> Google Sheets) —  no server required.

---
## Folder structure

.
├── index.html         
├── Product image/
│   ├── images/
│   
├── README.md
