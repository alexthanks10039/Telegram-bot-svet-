# Project Context - Telegram Mini App Svet

## Product Type
Telegram Mini App for employee management, object tracking and photo reports.

## Main Goal
Create a fast mobile-first workflow for field electricians and employees.

## UX Philosophy
- Minimalistic industrial UI
- Large CTA buttons
- One main action per screen
- No ERP complexity
- Telegram-first workflow
- Mobile-only primary UX

## Main Entity
Object Card

Each object contains:
- title
- address
- status
- employee
- timeline
- photo reports

## Main Roles
### Employee
- views assigned objects
- uploads reports
- changes statuses
- reports problems

### Admin
- creates objects
- assigns employees
- reviews reports
- controls statuses

## Status System
- NEW
- ASSIGNED
- IN_PROGRESS
- PHOTO_BEFORE_DONE
- PHOTO_AFTER_DONE
- REPORT_SENT
- COMPLETED
- BLOCKED
- REJECTED

## Main Screens
- Splash
- Home
- Object Card
- Report Flow
- History
- Problem Report

## Current Stage
UI/UX prototype stage.

## Technical Stack
### Frontend
- Flutter Web
- Dart
- Telegram Mini Apps SDK later

### Backend later
- NestJS
- PostgreSQL
- REST API

## Design Direction
Telegram + Linear + Notion + Industrial UI.

## Product Principles
- 3 taps maximum to main action
- No command UX
- No long text blocks
- Fast loading
- Gesture-friendly UI
- Telegram native feeling
