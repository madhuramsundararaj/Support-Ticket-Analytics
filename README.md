# Support Ticket Intelligence
SQL · Python · Operations Analytics

---

About This Project

I built this project because I lived inside this problem.

At Amazon and Sutherland I tracked SLA performance, response times and 
customer satisfaction manually every single day. CRM reports, Excel sheets, 
shift summaries. It worked but it was slow and always reactive.

I wanted to see what that same work looks like when done with proper data 
tools. Faster, visual and built to catch problems before they become complaints.

---

The Problem

A tech support team is handling 8,469 customer tickets.
Customers are frustrated. Tickets are piling up. Nobody knows which ones 
will blow up into formal complaints.

The questions I wanted to answer:

Which customers are most at risk of escalating?
Which channels are performing the worst?
Which products are causing the most frustration?
Can we predict low satisfaction before it happens?

---

What I Built

I created a Frustration Score for every ticket.
It combines ticket priority, how long it took to resolve, and customer 
satisfaction into one number. Higher score means higher escalation risk.

This is not something I copied from a tutorial. It came from watching 
patterns in real support operations and asking what actually drives 
a customer to escalate.

---

What I Found

72% of all tickets are high or critical escalation risk.
The support team is not underperforming. They are overwhelmed.

Social media is the worst channel for resolution.
32.25% resolution rate and highest frustration scores.
Email and chat handle customers better.

Dell XPS is the most problematic product.
Highest frustration score. Only 26% of tickets resolved.
Customers buying this product need a dedicated support path.

Critical tickets are being handled first which is correct.
But 65% of them are still unresolved. Capacity is the real problem.

My escalation prediction model first showed 100% accuracy.
That told me something was wrong. I had accidentally used features 
that were mathematically linked to the answer. I fixed it and got 
50% accuracy which is the honest result. Good learning moment.

---

Recommendations

Build an escalation queue. Any ticket with a Frustration Score above 20 
goes to a senior agent within 2 hours.

Move complex tickets off social media. Use email and chat instead.

Create a Dell XPS specialist team. Two people dedicated to this 
product would clear the backlog in 30 days.

---

SQL Work Done

Five queries using advanced SQL:
Resolution rate by priority using GROUP BY
Channel ranking using RANK window function
Escalation risk tiers using CTE
Product analysis using CASE WHEN
Monthly trends using LAG window function

---

Tools

Python for cleaning, analysis and prediction
SQLite for SQL query work
Jupyter Notebook for everything
GitHub for version control

---

Dataset

Kaggle Customer Support Ticket Dataset
8,469 tickets across 2020 and 2021

---

About Me

MBA in Business Analytics from SRM University Chennai.
Previously in operations at Amazon and Sutherland.
Building this portfolio to move into data analyst roles.

The operations background is not a limitation.
It is what makes my analysis actually make sense to a business.
