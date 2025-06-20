# 🚀 Microsoft 365 Copilot Prompt Automation

This repository provides a scalable and customizable solution for delivering daily Microsoft 365 Copilot Chat prompts using Power Automate and SharePoint. It is designed to accelerate Copilot adoption, reduce manual effort, and empower teams with consistent, high-impact content delivery.

---

## 📌 Overview

This solution includes:

- A **Power Automate flow** that automates the retrieval and distribution of daily Copilot prompts.
- A **SharePoint import-ready Excel template** (`30 Day Copilot Chat.xlsx`) that seeds the SharePoint list with 30 days of curated prompts.
- A **framework** for customizing, tracking, and scaling Copilot enablement journeys across departments or regions.

---

## 🧠 Executive Summary: Daily Prompt Distribution Flow

This automated Power Automate flow orchestrates the retrieval and distribution of daily prompts from a SharePoint list, ensuring consistent delivery and operational reliability.

+ **Schedule**: Executes automatically on weekdays at 9:30 AM Central Standard Time.
+ **Variable Initialization**: Prepares key variables including SharePoint item ID, adaptive card JSON, and HTML email content.
+ **Prompt Retrieval**: Queries the SharePoint list to fetch the current day’s prompt and stores its identifier.
+ **Content Generation**: Builds an adaptive card for Teams and a formatted HTML email using the retrieved prompt data.
+ **Notification Delivery**: Sends the generated content via email and Teams based on configuration. In test mode, notifications are routed to the admin.
+ **Error Management**: Triggers an alert email to the admin if any issues arise during retrieval or delivery.

> ✅ This flow supports prompt consistency, minimizes manual effort, and includes built-in safeguards to ensure dependable execution.

---

## 📥 Executive Summary: SharePoint Import Process

The SharePoint import process using the `30 Day Copilot Chat.xlsx` template enables rapid deployment of a structured, customizable prompt delivery system for Microsoft 365 Copilot Chat.

+ **Template-Driven Import**: The Excel file is preformatted to align with SharePoint’s import schema, allowing for seamless list creation without manual configuration.
+ **Accelerated Setup**: Users can populate a SharePoint list with 30 days of Copilot Chat prompts in minutes, reducing setup time and eliminating repetitive data entry.
+ **Flow Integration**: Once imported, the list connects directly to the Power Automate flow, serving as the source for daily prompt retrieval and distribution.
+ **Post-Import Customization**: SharePoint’s native list features allow users to edit, reorder, or localize prompts after import to meet specific audience or business needs.
+ **Built-In Flexibility**: Columns such as prompt text, links, images, and metadata are easily configurable, supporting a wide range of use cases and delivery formats.
+ **Change Tracking & Governance**: SharePoint’s version history and permission controls provide transparency and control over edits, making it easy to audit changes and manage contributions across teams.

> 🚀 This import-driven approach empowers teams to launch and scale Copilot enablement journeys with minimal overhead, while retaining full control over content and delivery cadence.

---

## 💼 Business Value

- **Accelerates Copilot adoption** with ready-to-use, high-impact prompts.
- **Reduces operational friction** by automating delivery across Teams and email.
- **Supports localization and personalization** for different departments or regions.
- **Enables governance and auditability** through SharePoint’s native capabilities.
- **Scales effortlessly** across teams, business units, or global rollouts.

---

## 📂 Included Files

| File | Description |
|------|-------------|
| `30 Day Copilot Chat.xlsx` | Import-ready SharePoint list template with 30 curated Copilot prompts |
|'TheGreatCopilotJourneyChatEdition_1_0_0_0'| Import-ready Power Platform solution to auto-send the 30 day Copilot Journey notifications

---

## 🛠️ Getting Started

1. Import the `30 Day Copilot Chat.xlsx` into a new SharePoint list.
2. Configure the Power Automate flow to connect to your list.
3. Set up email and Teams notification targets.
4. Test using the built-in admin routing mode.
5. Go live and monitor via SharePoint and Power Automate logs.

---

## 📣 Questions or Feedback?

Feel free to open an issue or reach out to the project maintainer for support, enhancements, or deployment guidance.




## 👥 Key Contributors

| Name | Role | LinkedIn |
|------|------|----------|
| **Anthony Escobedo** | Lead Developer & Automation Architect | https://www.linkedin.com/in/anthony-escobedo |
| **Kent Tilger** | Business Strategy Lead & Solution Evangelist | https://www.linkedin.com/in/kenttilger |


