# Business Problem

## Context

Benchline Analytics sells data analytics and BI dashboards to small businesses, mainly K-12 schools and small medical practices. Landing a client isn't a single event — it's a pipeline: a prospect gets identified, qualified, quoted, negotiated, and either signed or lost. Without a system tracking that pipeline, it's hard to answer basic questions a business needs to run itself: how many deals are open right now, how far along is each one, and how long does a typical deal take to close.

## The Problem

A consulting business with an informal or spreadsheet-based pipeline runs into the same issues repeatedly:

- No single view of every open opportunity and what stage it's in
- No way to see conversion rate stage-to-stage — where prospects actually drop off
- No visibility into how long deals sit at each stage, which makes forecasting close dates guesswork
- No automated follow-up when a deal's stage changes, so next steps depend on someone remembering to act

## The Approach

This project builds Benchline's own client-acquisition pipeline directly in Salesforce Sales Cloud, using synthetic small-business prospects standing in for real clients across the verticals Benchline actually sells into: medical and dental practices, veterinary and physical therapy clinics, home-services businesses, professional-services firms, and retail. Each Opportunity represents one specific analytics deliverable being pitched to that account (a patient-retention dashboard, a job-costing report, an inventory-and-sales dashboard), not a generic "Opportunity 1."

On top of that data model:
- **Reports** answer the specific questions above: how many opportunities per stage, what percentage convert stage-to-stage, and how long each deal has been sitting where it is.
- **A dashboard** puts all three reports on one page, so a stakeholder can see pipeline health at a glance instead of opening three separate reports.
- **A Flow** automates the one manual step that's easy to forget: when an Opportunity's stage changes, something fires automatically instead of depending on someone remembering to follow up.

## Why Salesforce

Salesforce is the CRM most small-to-midsize businesses either already run on or are evaluating, and CRM administration (report building, dashboard assembly, and declarative automation with Flow) is a distinct, in-demand skill set from software development. This project demonstrates that skill set at the admin/analyst level — the same level Benchline would need to configure a client's own Salesforce pipeline, not the level of writing Apex code.
