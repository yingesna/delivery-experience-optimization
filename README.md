# Delivery Experience Optimization

Product analytics case study exploring delivery predictability, customer satisfaction, and a proactive delivery-status MVP using synthetic data.

## Problem

Customers can become frustrated when delivery estimates change or when an order is at risk of arriving late.

This project explores the relationship between delivery predictability and customer outcomes and identifies an opportunity to improve the delivery experience through proactive communication.

## Key Findings

Analysis of the synthetic dataset showed that higher ETA accuracy was strongly associated with better customer outcomes.

Late deliveries were also associated with higher support contact rates and lower repeat-purchase rates.

These findings led to a product opportunity focused on proactively communicating delivery-status changes to customers.

## Product Solution

I designed a proactive delivery-status experience that would:

- Identify orders at risk of missing their ETA
- Provide an updated delivery window
- Explain when the expected delivery time changes
- Tell customers when they will receive their next update

### Example Customer Experience

> **Your delivery time has changed**
>
> Your order is now expected between 6:30–7:15 PM. We'll update you again by 6:00 PM.

## Experiment Plan

I designed a randomized A/B test to evaluate whether proactive delivery notifications improve customer outcomes.

### Primary Metric

- Support contact rate

### Secondary Metrics

- Customer satisfaction
- Repeat purchase
- Notification engagement

### Guardrail Metrics

- Cancellation rate
- Notification opt-out rate
- Customer complaints

The experiment uses 4 weeks of enrollment followed by a 30-day follow-up period for repeat-purchase measurement.

## Project Structure

- `data/` — Synthetic dataset
- `analysis/` — Data analysis and notebooks
- `product/` — PRD, user stories, and experiment plan
- `dashboard/` — Product analytics dashboard
- `visuals/` — Product flow and mockups

## Dashboard

[View the Delivery Experience Dashboard](./dashboard/delivery_experience_dashboard.pdf)

## Data Disclaimer

This project uses synthetic data created for portfolio purposes.

It does not contain Amazon customer data, internal operational data, or proprietary information.

## Skills Demonstrated

- Product analytics
- Data analysis
- Customer/user research
- Root-cause analysis
- Product requirements
- MVP definition
- Experiment design
- KPI development
- Data visualization
- Cross-functional problem solving
