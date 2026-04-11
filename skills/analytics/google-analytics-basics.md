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
Shows activity in the last 30 minutes. Useful when you've just sent an email blast or published a post and want to see immediate traffic.

### Acquisition Reports
Answers: *Where is my traffic coming from?* Use this to evaluate which marketing channels are performing.

### Engagement Reports
Answers: *What are people doing on my site?* Check pages per session and average engagement time to gauge content quality.

### Retention Reports
Answers: *Are people coming back?* Useful for subscription-based or content-heavy sites. <!-- personal note: I find this one underrated — worth checking weekly if you run a blog -->

### Conversion / Key Events Reports
Answers: *Are people completing the actions I care about?* This is the bottom line for most campaigns.

## Common Mistakes to Avoid

- **Not filtering out your own traffic** — add an internal traffic filter under Admin so your visits don't skew the data
- **Ignoring the date comparison feature** — always compare to a prior period to spot trends
- **Treating bounce rate as always bad** — a high bounce rate on a contact page where users grab a phone number is fine
- **Setting up zero conversions** — GA4 is much less useful without at least one key event defined
