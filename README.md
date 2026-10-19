# marketings-automation-system
MARKET AUTO - Marketing Automation System (CRM)

A modern, responsive, single-page Marketing Automation & CRM Web Application built with HTML5, Tailwind CSS, JavaScript (Vanilla ES6+), and Chart.js.

📌 Table of Contents

Overview

Key Features

Tech Stack & Libraries

Project Architecture

Getting Started

Data & State Management

License

🚀 Overview

MARKET AUTO is an intuitive web-based CRM and Marketing Automation platform designed for managing email and SMS campaigns, subscriber audiences, automation workflows, templates, and analytics.

The application operates entirely client-side, featuring persistent state management via localStorage, dynamic visual analytics charts, interactive modals, responsive sidebar navigation, dark mode support, and seamless CSV data exports.

✨ Key Features

Interactive Dashboard:

Real-time KPI metric calculation (Total Campaigns, Active Subscribers, Avg Open Rate, Avg Click Rate).

Visual charts powered by Chart.js (Subscriber Growth line chart & Campaign Status doughnut chart).

Quick-view overview table for recent marketing campaigns.

Campaign Management:

Filter campaigns by status (In Progress, Scheduled, Completed, Draft, Cancelled).

Live search input filter.

Create, edit, and delete campaigns using an embedded modal form.

Live metric updates on campaign modification.

Subscriber & Contact Management:

Audience management with active/unsubscribed status toggling.

Filter by status or search by name/email.

Export subscribers to CSV (subscribers_export.csv).

Email Templates & Previews:

Responsive template gallery.

Interactive preview modal for inspecting email headers, snippets, and HTML bodies.

Deep Dive Campaign Analytics:

Comparative Bar Chart analyzing Open vs. Click rates across active campaigns.

Interactive marketing conversion funnel breakdown.

Automation Workflows & Landing Pages:

Visual sequence builder views for welcome sequences, abandoned cart recovery, and trigger rules.

Landing page performance tracking and preview interfaces.

Reports & Data Export:

Campaign ROI executive summary with total spend, revenue, and calculated ROI metrics.

PDF/CSV report generation.

UI/UX Highlights:

Dark Mode Support: Fully tailored dark theme powered by Tailwind CSS class switching.

Collapsible Sidebar & Header Nav: Mobile-friendly layouts and quick notification popovers.

Local Storage Persistence: All dynamic updates, created contacts, and edited campaigns persist locally across browser reloads.

🛠️ Tech Stack & Libraries

Markup & Structure: HTML5

Styling & UI: Tailwind CSS (via CDN with custom color configurations)

Icons: FontAwesome 6.4.0

Data Visualization: Chart.js

Scripting & Logic: Vanilla JavaScript (ES6+, DOM Manipulation, LocalStorage API)

📁 Project Structure

This application is built as a self-contained Single Page Application (SPA):

.
├── index.html          # Main HTML structure containing styles, UI views, modals, and JS logic
└── README.md           # Documentation file


🏁 Getting Started

Because MARKET AUTO runs purely in the browser with no required backend compiler or node modules, setup is instant:

Clone or Download the repository.

Open index.html directly in any web browser (Chrome, Firefox, Edge, Safari).

(Optional) Use a local server extension such as Live Server in VS Code for live hot-reloading during editing.

💾 Data & State Management

The application initializes with standard default datasets:

Initial Campaigns

Initial Subscribers

Email Templates

Automation Workflows

Any modifications, creations, or deletions made during user interactions are immediately written to localStorage under the following keys:

market_campaigns

market_subscribers

market_templates

market_workflows

To reset the app back to its default demo dataset at any time, navigate to Settings and click Reset Demo Data.

📄 License

This project is licensed under the MIT License — feel free to modify and expand upon it.
