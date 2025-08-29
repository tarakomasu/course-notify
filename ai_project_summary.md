
# AI Project Summary: Course Notify

## Project Overview

This project, named "Course Notify," appears to be a notification system related to courses. It is in the early stages of development.

The project is structured as a monorepo with a Ruby on Rails backend and a Next.js frontend.

## Technology Stack

### Backend

*   **Framework:** Ruby on Rails 8.0.2
*   **Database:** SQLite
*   **Web Server:** Puma
*   **Key Gems:**
    *   `solid_cache`
    *   `solid_queue`
    *   `solid_cable`

### Frontend

*   **Framework:** Next.js 15.5.2
*   **UI Library:** React 19.1.0
*   **Language:** TypeScript
*   **Styling:** Tailwind CSS

## Current Status

*   **Backend:** No application-specific API routes have been defined yet. The default `/up` health check route exists.
*   **Frontend:** The frontend is currently the default Next.js template.
*   **Development Rules:** The root `README.md` contains important rules for development, which all contributing AI agents must follow.

## Development Commands

### Frontend (`/front` directory)

*   **Run development server:** `npm run dev`
*   **Create production build:** `npm run build`
*   **Start production server:** `npm run start`
*   **Lint files:** `npm run lint`

### Backend (`/back` directory)

*   **Start development server:** `bin/rails s`
*   **Run tests:** `bin/rake test`
*   **Run RuboCop for linting:** `bin/rubocop`
*   **Run Brakeman for security analysis:** `bin/brakeman`

## Next Steps

1.  Define the core features and purpose of the "Course Notify" application.
2.  Implement the necessary API endpoints in the Rails backend.
3.  Develop the user interface and functionality in the Next.js frontend.
4.  Flesh out the `README.md` with a more detailed project description.
