# Portfolio Website with Digital Product Store

Modern portfolio website with an integrated digital product store.  
This project is built not only to showcase profile, projects, and experience, but also to support direct digital product sales in one seamless platform.

## Overview

This website combines personal branding and monetization in a single system.  
Visitors can explore portfolio content, view projects, read blog content, browse achievements, and purchase digital products directly from the store.

The main highlight of this project is the **digital product store** with a simple checkout flow and **QRIS payment integration**.

## Features

- Clean and modern portfolio interface
- Project showcase with detail pages
- Blog/content section
- Achievements section
- Store for selling digital products
- Product detail page
- Buyer details form
- Checkout flow with QRIS payment
- Payment status tracking
- Success page for delivered digital products
- Admin dashboard for managing content and store data
- Responsive layout for desktop and mobile

## Main Focus

This project is designed to be more than a regular portfolio.  
The portfolio serves as a personal and professional showcase, while the built-in store gives it real business value by enabling digital product sales directly from the same website.

## Tech Stack

- Next.js
- React
- TypeScript
- Tailwind CSS

## Database

- MongoDB

## Payment Gateway

- Pakasir QRIS

## Environment Variables

Create a `.env.local` file and configure the required variables:

```env
MONGODB_URI=
PAKASIR_API_KEY=
PAKASIR_PROJECT_SLUG=
PAKASIR_MODE=
```

## Getting Started

Install dependencies:

```bash
npm install
```

Run the development server:

```bash
npm run dev
```

Open:

```bash
http://localhost:3000
```

## Admin Panel

Admin dashboard is used to manage:

- Site settings
- Projects
- Blog posts
- Achievements
- Skills
- Store products
- Digital product variants

## Store Flow

1. User opens the store page
2. User selects a product and variant
3. User fills buyer details
4. User continues to checkout
5. User pays using QRIS
6. Payment status is checked
7. Product details are delivered on the success page

## Scripts

```bash
npm run dev
npm run build
npm run start
npm run lint
```

## Project Goal

The goal of this project is to build a portfolio that is not only visually appealing, but also functional and commercially useful.  
It is a portfolio website that can actively support digital product sales, making it both a showcase platform and a working business tool.

Demo Soon
