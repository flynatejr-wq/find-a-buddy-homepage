# Find a Buddy — Homepage

This is the public homepage design for **Find a Buddy**, a study-buddy matching web app being built for Savannah State University students.

Students will be able to register with an `@savannahstate.edu` email, post their current courses, get matched with classmates in the same course, send study-buddy requests, and chat with an AI study mascot for motivation and tips.

This repo contains the **homepage** — the page a visitor sees before logging in — including the hero section, "How it works" walkthrough, and value proposition sections.

## What's used here

- **HTML** — page structure and content
- **CSS** — all styling: the navy/orange Savannah State color scheme, layout, and animations (embedded in the `<style>` block)
- **JavaScript** — the small interactive behaviors on the page (button clicks, screen navigation), embedded in the `<script>` block

No frameworks or build tools — it's a single self-contained `index.html` file that runs in any browser.

## How to view it

Open `index.html` directly in a browser, or use a simple local server, e.g.:

```bash
python -m http.server
```

then visit `http://localhost:8000`.

## Project context

This homepage is one piece of the larger Find a Buddy application, which also includes a PHP backend, a MySQL database, and pages for course management, buddy matching, and the AI mascot chat.
