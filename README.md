# Lusail — Home Services Platform for Clients and Staff

**Ask for the service, get a quote, follow it through.** Lusail is a home-services platform: a client requests the service they need, receives a quote, pays, and follows the work in a conversation with the right department, while the operations team runs everything from one admin panel.

> This repository is a project showcase. It contains documentation only — the production source code is private.

---

## Overview

Home services run on coordination: a request, a price, a schedule, a conversation and a payment. Lusail puts those in one system, with a client-facing experience and an operations side behind it.

- **Clients** request services, receive and accept quotes, pay, chat with the team, keep their documents in one place and give feedback.
- **Operations** works from a single admin panel: departments, branches, partners, services, requests, quotes, conversations and payments.

## My role

**Senior Laravel Backend Engineer**

- Designed and built the backend: domain model, service-request and quote lifecycle, payments and wallet ledger.
- Built the messaging layer, including conversations, staff canned replies and message reporting.
- Built the Filament admin panel and the mobile API.
- Owned roles and permissions, activity logging, PDF documents and Excel import/export.

## Tech stack

| Area | Stack |
| --- | --- |
| Language & framework | PHP 8.4+, Laravel 13, MVC, Eloquent ORM |
| Admin panel | Filament 5, Livewire 4 |
| Real time | Laravel Reverb (WebSockets) |
| Mobile API | RESTful API, Laravel Sanctum |
| Data | Eloquent, Redis for cache and queues |
| Access control | Spatie roles and permissions |
| Documents & exports | dompdf (PDF), Laravel Excel |
| Localisation | Arabic / English (translatable fields) |
| Delivery | Git, CI/CD, Linux, Nginx |

## Key features

**Service requests and quotes**
- A service catalogue, with a request raised by the client for the service they need.
- Quotes issued against a request, and requests that can be transferred between departments or partners.

**Payments and wallet**
- Payment records tied to the request and the client.
- A wallet with a transaction ledger per client.

**Conversations, not tickets**
- Threaded conversations between the client and the responsible department.
- Canned replies for staff, message reporting, and conversation drafts.

**Client documents**
- Files and documents attached to the client profile, with per-document flags.

**Access and identity**
- OTP-based sign-in and device tokens for push notifications.

**Feedback and content**
- Surveys after the service, onboarding slides in the app, and static pages managed from the panel.

**Operations**
- Departments, branches, partners, services and settings in one admin panel.
- Roles and permissions, activity log, Excel import/export, PDF documents.
- Website inquiries captured in the same place the team works.

## About this repository

This is a documentation-only showcase of a production product. It contains no client code, customer data or infrastructure details.

**Mohamed Karem Tawfik** — Senior PHP / Laravel Developer, Backend Team Lead
[GitHub](https://github.com/mkarem4) · [LinkedIn](https://linkedin.com/in/mohamed-karem93)
