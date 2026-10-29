# GA4 Dashboard: Weekly Website Performance Tracker

A simple, beginner-friendly companion resource for **How to Create a GA4 Dashboard for Website Performance**.

Use this repository to build a basic dashboard in Google Analytics 4 (GA4) and record a short weekly review without needing a complicated reporting system.

**Full tutorial:** [How to Create a GA4 Dashboard for Website Performance](https://subashkafle.com/ga4-dashboard/)  
**Author:** [Subash Kafle](https://subashkafle.com/)

## What's included

- [`ga4-weekly-review-template.csv`](ga4-weekly-review-template.csv) — a blank weekly tracking sheet you can open in Excel or Google Sheets.
- [`ga4-weekly-review-example.csv`](ga4-weekly-review-example.csv) — one **fictional demonstration** showing how a completed weekly review could look. These are not real website results.

## Build a simple dashboard in GA4

1. Sign in at [Google Analytics](https://analytics.google.com/) and choose your GA4 property.
2. Open **Reports** and look for **Create > Dashboard**. You may need Editor or Administrator access.
3. Add scorecards for **Active users**, **Sessions**, and **Engagement rate**.
4. Add a chart or table for **Sessions by Session default channel group**.
5. Add a table for **Views by Page title and screen name**.
6. Save and publish the dashboard for other users of your GA4 property.

Official instructions: [Google Analytics dashboard documentation](https://support.google.com/analytics/answer/17217303?hl=en).

## Review your website every week

1. Download `ga4-weekly-review-template.csv` by opening the file above and choosing **Download raw file**. Open it in Excel or import it into Google Sheets.
2. Choose a complete 7-day period in GA4 and use the same dates for each metric.
3. Enter **Active users**, **Sessions**, and **Engagement rate**. Enter engagement rate as a percentage number (for example, `61` means 61%).
4. Record sessions from the four listed traffic channels, if present. These may not sum to total sessions if your website receives traffic from other channels.
5. Record a top page, one observation, and one action to try before your next review.
6. Add one new row each week to see patterns over time.

### Column definitions

| Column | Meaning |
| --- | --- |
| `week_start`, `week_end` | Start and end of the 7-day reporting period (YYYY-MM-DD) |
| `active_users` | GA4 active users |
| `sessions` | GA4 sessions |
| `engagement_rate_pct` | GA4 engagement rate, recorded as a number between 0 and 100 |
| `organic_search_sessions` | Sessions attributed to Organic Search |
| `direct_sessions` | Sessions attributed to Direct |
| `organic_social_sessions` | Sessions attributed to Organic Social |
| `referral_sessions` | Sessions attributed to Referral |
| `top_page` | One page you want to monitor |
| `observation` | What stood out during this week's review |
| `next_action` | One practical follow-up task |

## Notes

- The example file contains **invented sample data only**. Do not treat its figures as actual marketing performance.
- Metrics and channel groupings depend on the reporting scope and GA4 configuration.
- Avoid uploading private analytics exports, personal information, or client reports into public GitHub repositories.
- This is a CSV tracking resource, **not** a live GA4 data integration. Enter or update the numbers manually each week.

---

Created by **Subash Kafle** · [subashkafle.com](https://subashkafle.com/)
