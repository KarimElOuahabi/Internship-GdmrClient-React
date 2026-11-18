# GDMR Frontend

Web client for **GDMR**, an occupational health visit management platform, with role-specific dashboards and live notifications. Built during my internship at SQLI.

## Features

- **Role-based UI:** `ADMIN`, `HR`, `DOCTOR` and `EMPLOYEE` each get their own pages, sidebar and route guards.
- **Visit workflow:** request, propose, confirm or reject, schedule, run and complete visits, with a negotiation history.
- **Live notifications:** a bell with an unread count, updated through Server-Sent Events.
- **Medical records:** patient history and documents for doctors, and an upload page for employees.
- **Staff and user management:** list, search, filter, edit and delete.
- **Auth:** automatic token refresh and retry.

## Tech stack

React 19 · TypeScript · Vite · Redux Toolkit (RTK Query) · React Router 7 · Tailwind CSS 4 · react-hook-form · Zod · TanStack Table

## Related project

[Internship-GdmrApi-SpringBoot](https://github.com/KarimElOuahabi/Internship-GdmrApi-SpringBoot): the API for this client.
