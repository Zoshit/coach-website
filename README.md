# 🎉 Nataliya Dyadichenko — Event & Ticketing Platform

[![en](https://img.shields.io/badge/lang-English-blue.svg)](README.md)   [![uk](https://img.shields.io/badge/lang-Українська-yellow.svg)](README.uk.md)

> A full-featured Django-powered e-commerce platform for browsing and purchasing tickets to events. Repository contains a project overview only — source code is private under client confidentiality.

## Overview
A large-scale web platform built for selling event tickets, with a complete e-commerce flow: browsing events by category, adding them to a cart, checking out, and paying online. The project includes a custom admin-managed catalog with discount support and per-event dynamic pages.

## Features

### 🗂️ Event Catalog
- Events organized by category with full backend-driven filtering and data management
- Individual dynamic page for each event, generated from the database (e.g. `/shop/product/30/...`)

### ⭐ Reviews
- Customer review section with an auto-scrolling carousel

### 🛒 Shopping Cart
- Fully functional cart — add and remove items dynamically
- Persistent cart state across the checkout flow

### 💳 Checkout & Payment
- Dedicated order creation flow (`/orders/create/`)
- Integrated online payment processing

### ⚙️ Admin Management
- Discount system configurable through the Django admin panel
- Toggle product/event visibility on the storefront directly from the admin panel, without code changes

## Tech Stack

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

- `Django` — backend, ORM-driven catalog and category system, order and cart logic
- `Django Admin` — custom management interface for discounts and product visibility
- `JavaScript` — cart interactivity and auto-scrolling review carousel
- `HTML/CSS` — responsive storefront layout and individual event pages

## Live Site
🔗 [nataliyadyadichenko.com](https://nataliyadyadichenko.com)

---

*This repository is a showcase only — full source code is not published due to client confidentiality.*
