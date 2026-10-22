# Ticketflow

A responsive ticket-management MVP built as a fresh start in the `PROJECT-TICKETS` repository.

## What is included

- Overview dashboard with live counts derived from the demo tickets
- Ticket list with search, project and priority filters
- Tabs and sidebar views for all, open, in-progress, resolved and urgent tickets
- Create-ticket modal with title, description, project, priority, requester and due date
- Ticket detail modal with status editing
- Priority breakdown, recent activity, responsive mobile navigation
- Demo tickets and browser-local persistence using `localStorage`

## Run it

This is currently a **static frontend prototype**. Open `index.html` directly in a browser or serve the repository with any static file server.

No build step or package installation is required.

## Important limits

- Tickets are saved only in the current browser on the current device.
- There is no authentication, shared database, email/notification delivery or server-side API yet.
- The displayed activity feed and workspace usage are sample content.
- The app has not been deployed; this branch is isolated for review.

## Next sensible step

Once the interaction and visual direction feel right, choose a backend (for example, Supabase) and add authenticated users, shared tickets, permissions and migrations in a separate, tested phase.
