# SuperSet Report — Self-Service Voice Bot Analytics

A browser-based reporting dashboard that turns raw voice-bot campaign exports into usable performance views, without rebuilding Excel charts for every campaign.

## Why I built it

The voice-bot product team could access raw calling data but lacked an easy, repeatable way to explore campaign performance. I built this tool to make campaign diagnostics self-service for product reviews and client conversations.

## What it helps analyze

- **Reach and response:** Answered vs. unanswered cases, case-level connectivity, and response categories.
- **Disposition outcomes:** Positive, negative, neutral, non-contact, escalation, and detailed call dispositions.
- **Calling strategy:** Results by campaign template, language, day of week, and time of day.
- **Engagement:** Call durations, attempt counts, and daily outcome trends.
- **Decision support:** Performance patterns that warrant further investigation or changes to campaign strategy.

## Typical workflow

1. Export the campaign data in the format expected by the dashboard.
2. Open `index.html` in a browser and load the data.
3. Review the generated performance breakdowns and trends.
4. Use the findings to guide follow-up analysis and client discussions.

## Repository contents

- `index.html` — main browser-based dashboard.
- `Voicebot_Workspace.html` — additional workspace interface.

## Product principles

- **Self-service:** Make operational analytics accessible without BI dashboard authoring access.
- **Repeatability:** Use consistent definitions and visualizations across campaign reviews.
- **Clarity:** Distinguish case-level reach, call-level performance, and disposition outcomes.

## Responsible use

Use **synthetic or explicitly authorized anonymized data** for public demonstrations. Never publish identifiable borrower/customer data, private client exports, secrets, or credentials. Reported associations and trends are not proof that a specific product change caused an outcome.
