# CourseFlow — Course Progression Tracker

CourseFlow is a web prototype for tracking course and syllabus progress across campuses. It was built for the Mirai School of Technology (MSOT) Student Challenge 2, Problem 1.

## Live demo

[Open CourseFlow](https://msot-courseflow.netlify.app)

## Open the app

Open [`miraiProblem.html`](./miraiProblem.html) in a modern browser. The prototype can also be hosted as a static page; the app file is available at:

`https://msot-courseflow.netlify.app`

The live demo is hosted on Netlify. The repository contains the HTML source file and README.

## What it includes

- Course and syllabus coverage, including completed, in-progress, skipped, and remaining hours.
- Timetable-aware progress and recovery forecasting with holiday and working-Saturday rules.
- Faculty session logging, dashboard risk indicators, and early-warning views.
- Exam readiness by configured exam scope and a student-facing progress view.
- CSV import for semester and structured syllabus data.
- Optional Supabase connection for authenticated, cloud-backed data.

## Demo and data

The app includes sample data and local demo personas for walkthroughs. Demo personas are local prototype identities; they do not prove user authentication or access control. Browser-local changes stay on that device unless a properly configured Supabase connection is used.

## Supabase configuration

The HTML client must use only the Supabase project URL and a public anon/publishable key. Never put a service-role key or other server secret in this file. Cloud access also requires the matching database schema, row-level security policies, and provisioned Auth users with profile and role mappings. Email alerts need server-side secrets and a verified sender.

Live user permissions and email delivery have not been verified. Do not use this prototype for sensitive student records until those controls are configured and tested.

## Current repository contents

This repository currently contains the single-file app (`miraiProblem.html`). The full submission bundle, database migrations, automated tests, sample import files, and deployment notes are maintained separately; they are not included here.
