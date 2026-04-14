---
title: Google Analytics Basics
category: analytics
tags: [analytics, data, tracking, metrics, google-analytics]
difficulty: beginner
readTime: 8 min
author: marketingskills
contributors: []
createdAt: 2024-01-15
updatedAt: 2024-01-15
status: published
---

# Google Analytics Basics

Google Analytics is the most widely used web analytics platform, giving marketers insight into how users find and interact with their website. Understanding the fundamentals helps you make data-driven decisions instead of guessing what's working.

## What You'll Learn

- How to navigate the Google Analytics 4 (GA4) interface
- Key metrics every marketer should track
- How to set up basic goals and conversions
- Reading and interpreting standard reports
- Common mistakes to avoid

## Core Concepts

### Sessions vs. Users

**Users** are individual people who visited your site. **Sessions** are individual visits — one user can have multiple sessions. Confusing these two is one of the most common beginner mistakes.

- A **new user** is visiting your site for the first time (based on browser cookies)
- A **returning user** has visited before
- One user can generate many sessions across different days or devices

### Key Metrics to Track

| Metric | What It Tells You |
|--------|------------------|
| Sessions | Total number of visits |
| Users | Unique visitors |
| Bounce Rate | % of single-page visits |
| Avg. Session Duration | How long people stay |
| Pages/Session | Depth of engagement |
| Conversion Rate | % completing a goal |
| Engaged Sessions | Sessions with 10s+ activity or 2+ pageviews — more reliable than bounce rate in GA4 |

> **Personal note:** I've found that Avg. Session Duration can be misleading — GA4 only counts time on the *last* page if there's no further interaction, so it often underreports. Take this metric with a grain of salt and pair it with Engaged Sessions instead.

> **Another personal note:** Bounce Rate in GA4 is actually the *inverse* of Engagement Rate (i.e., % of sessions that were NOT engaged). This is a different definition than old Universal Analytics, so don't compare the two directly if you're migrating.

### Traffic Sources (Acquisition)

GA4 organizes where your traffic comes from into channels:

- **Organic Search** — visitors from unpaid search results (SEO)
- **Direct** — typed your URL or used a bookmark
- **Referral** — clicked a link on another website
- **Organic Social** — unpaid social media posts
- **Paid Search** — Google Ads and other PPC
- **Email** — links in email campaigns

Always check your acquisition report first. If organic search is dropping, that's an SEO issue. If direct traffic spikes, you may have run an offline campaign.

## Setting Up Goals / Conversions

In GA4, conversions are called **key events**. You need to define what a "conversion" means for your business:

1. Go to **Admin → Events**
2. Find or create the event you want to track (e.g., `form_submit`, `purchase`)
3. Toggle **Mark as key event**

Common conversions to track:
- Form submissions / lead captures
- Product purchases
- Newsletter sign-ups
- File downloads
- Phone number clicks

## Reading the Reports

### Reports Snapshot
Your home dashboard. Good for a quick daily health check — sessions, conversions, revenue if applicable.

### Realtime Report
Shows activity in the last 30 minutes. Use
