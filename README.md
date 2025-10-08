Chris's Notes: Physics Study Guide Store
This repository hosts a one-page e-commerce storefront for selling physics study guides (PDFs) created by Chris. It features a modern, dark-mode design built with Tailwind CSS and integrates an interactive AI Tutor powered by the Gemini API.

🚀 Deployment & Usage
This application is designed to run as a single-page website.

File Placement: Ensure this README.md and the website file (index.html) are placed in the root directory of your GitHub repository.

Hosting: Deploy using GitHub Pages (Settings -> Pages -> Branch: main or master / Folder: / (root)).

💰 CRITICAL: Update Payment Links
The pricing buttons currently use placeholder URLs (https://example.com/checkout?...). The site will not generate sales until you replace these placeholder links with your actual hosted payment links (e.g., from PayPal, Stripe, or Gumroad).

Look for the href attributes in the <section id="pricing"> of the index.html file and update them:

<!-- Example of link to update: -->
<a href="YOUR_ACTUAL_PAYPAL_OR_STRIPE_URL_HERE" target="_blank" ...>
    Pay with PayPal ($1.00)
</a>

✨ Key Features
Single-Page E-commerce: Fully responsive layout for viewing study guide pricing and benefits on any device.

Tailwind CSS: Professional, dark-mode theme with an academic blue accent.

Physics Quick Assist (Gemini Integration): An interactive tutor that uses the Gemini API (Google Search Grounding enabled) to answer complex physics questions with expert, grounded explanations.

Custom Notification System: Replaces browser alerts with non-intrusive UI messages.

Mobile-Ready: Includes a responsive navigation menu.
