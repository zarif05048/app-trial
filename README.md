# App Trial - Contact Form

A premium, responsive, and mobile-friendly contact form that posts to a Google Apps Script web app endpoint.

## Features

- **Modern Glassmorphic UI:** A dark space-themed background with soft purple-indigo glows and backdrop blur cards.
- **Micro-interactions:** Interactive hover states, focus glowing inputs, and active button scaling.
- **Apps Script POST Integration:** Submits name, email, and message as a JSON string via `mode: 'no-cors'` fetch to prevent CORS blocks.
- **Auto-Reset:** Automatically resets the form and displays a beautiful success alert message upon submission.

## Setup & Configuration

To integrate with your Google Apps Script Web App:
1. Open [form.html](form.html).
2. Locate the configuration variables in the `<script>` tag:
   ```javascript
   const DEPLOYMENT_ID = "YOUR_DEPLOYMENT_ID_HERE";
   const URL = "YOUR_APPS_SCRIPT_URL_HERE";
   ```
3. Replace them with your actual Google Apps Script Deployment ID and Web App URL.
