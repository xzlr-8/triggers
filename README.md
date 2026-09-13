# triggers

A reference dataset of student emotional/stress scenarios paired with associated "trigger words" — phrases someone in that situation might type or say.

## What it does

The repo is a single text file organized into categories (e.g. academic pressure, peer pressure, bullying, general emotional wellbeing), each with ~100 short scenario descriptions and a matching set of trigger words. It reads like reference/seed data for a system that needs to recognize *why* a student might be stressed, upset, or struggling, based on the language they use — for example, a chatbot, moderation tool, or wellbeing check-in feature that flags when a student may need support.

## Important note

Some categories touch on serious topics, including bullying, depression, and self-harm ideation. If this data feeds into a real detection or moderation system, it should be paired with a clear escalation path to a real person (counselor, teacher, crisis line) — pattern-matching on keywords alone is not a substitute for genuine support, and false positives/negatives both carry real risk.

## Structure

Categories are numbered (e.g. "2. Social/Peer Pressure", "4. Bullying and Peer Issues", "5. Academic Challenges and Pressures"), each scenario followed by a `Trigger words:` line listing a few representative phrases.

## Suggested next step

Consider converting this from a loose text file into structured data (JSON/CSV) with category, scenario, and trigger-word fields, so it's easier to load programmatically.
