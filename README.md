# Public Service Request System
Citizens report civic issues (streetlights, water, garbage); admins triage and track them.

## Run
Open `index.html` in any browser. No install needed (data saved in localStorage).

## Accounts
- Citizens: self-register from the login screen.
- Admin: username `admin`, password `admin123`.

## Flow
Pending → In Progress → Resolved (statuses only advance one step at a time).

## Features
Registration/login · categorized requests with photo · admin dashboard ·
status tracking · open-vs-resolved analytics + resolution rate.

## Structure
- Storage layer (localStorage) · Auth · Views · Router
