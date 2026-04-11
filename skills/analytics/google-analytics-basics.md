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
Answers: *What are people doing on my site?* Check top pages, scroll depth, and events.

### Monetization Reports
Answers: *How is my site generating revenue?* Relevant for e-commerce and subscription businesses.

## Practical Tips

**Filter out internal traffic** — If you and your team visit the site regularly, your own sessions will inflate the numbers. Create an IP filter or use the internal traffic filter in GA4 Admin settings.

**Use UTM parameters** — Tag your marketing links with UTM codes so GA4 correctly attributes traffic from email, social, and ads. Without UTMs, much of this traffic shows up as "Direct."

Example UTM URL:
```
https://yoursite.com/landing-page
  ?utm_source=newsletter
  &utm_medium=email
  &utm_campaign=january-promo
```

**Compare date ranges** — Always compare to a previous period. A drop in traffic means nothing without context. Use the date comparison feature to see week-over-week or year-over-year changes.

**Don't obsess over vanity metrics** — High pageviews feel good but mean little if no one converts. Focus on metrics tied to business outcomes.

## Common Mistakes

- **Not verifying the tracking code is installed** — Use the GA4 Debugger Chrome extension to confirm data is flowing
- **Ignoring the date range** — GA4 defaults to the last 28 days; always check what period you're looking at
- **Treating all traffic equally** — 10,000 sessions from your target audience beats 100,000 from bots or irrelevant regions
- **No goals set up** — Without conversions defined, you can't measure marketing ROI

## Next Steps

Once you're comfortable with the basics:
- Learn to build **custom reports** and **explorations** in GA4
- Set up **audience segments** to compare behavior across user groups
- Connect GA4 to **Google Search Console** for SEO insights
- Explore **Google Looker Studio** to build shareable dashboards

## Resources

- [Google Analytics Help Center](https://support.google.com/analytics)
- [GA4 Demo Account](https://support.google.com/analytics/answer/6367342) — practice with real data
- [Measure School YouTube Channel](https://www.youtube.com/c/MeasureSchool) — practical GA4 tutorials
