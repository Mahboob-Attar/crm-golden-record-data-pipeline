The Assignment: The "Member Cleanup" Script
Overview
Our marketing team exported a list of new members from three different landing pages. The data is a mess. We need a Python script to clean this up and prepare a "Golden Record" CSV for our CRM.

The Files
signups.xls: 

requirements.txt: Use any libraries you deem necessary (e.g., Pandas, Standard Library).

The Task
Write a Python script that outputs a cleaned members_final.csv based on these intentionally vague business rules:

Standardize Dates: All signup dates must be in YYYY-MM-DD format.

Deduplication: We don't want the same person in the file twice.

Flag "Low Quality" Leads: Identify rows that look like "test" data or "garbage" and move them to a separate quarantine.csv instead of the final list.

The "Context" Challenge: We noticed some users signed up for "Plan A" and some for "Plan B." If a user signed up for both, keep the one that happened most recently, but add a flag is_multi_plan = True.

Answer these 2 questions:
1. Explain simple words, what logic did you apply.

2. What was the most frustrating part of the data, and how would you explain to a non-technical manager why we had to delete 20% of the leads?
