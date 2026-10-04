# Project Atlas

**A work in progress exploring personalized athlete training, starting with hockey.**

Project Atlas grew out of my experience as an athlete and fitness enthusiast. I wanted to explore how software could make training more personal: accounting for someone's background, goals, schedule and available equipment, then using their recorded work to guide what comes next.

I'm developing and testing the project locally. It is not a finished product or a publicly available training service.

## What I'm building

- A guided account and athlete-profile setup.
- Training programs that use the athlete's goals, experience, schedule and equipment.
- A workout experience with set logging, previous-set values, rest timers and clear session completion.
- Weekly reviews that account for recorded training and changing circumstances.
- Progress views and an illustrative body map showing training coverage.

The initial training package focuses on hockey off-ice performance. The broader architecture separates the shared platform from sport-specific rules.

## My role and approach

I lead the product direction, draw on my athletic experience, test the workflows and refine the requirements. I'm learning software development through the project and use AI coding tools, including Codex, to help implement and investigate changes.

Much of the work has involved asking practical questions: Does this workout suit the person who received it? Does each profile question serve a purpose? Can a new user understand what to do next? Those questions shape both the interface and the planning logic.

## Technology

- Next.js, React and TypeScript.
- Supabase authentication and PostgreSQL, running locally during development.
- Rule-based planning and adaptation; the application does not use runtime AI to generate workouts.
- Automated checks alongside hands-on workflow testing.

## Current stage

Account setup, planning, workout logging and weekly continuation are implemented locally and still being tested and refined. Training rules remain experimental. Qualified programming review, broader usability testing and release preparation are still ahead.

This repository is a project showcase rather than a release of the application. It contains the project overview; screenshots or selected code examples may be added after they have been reviewed for sharing.
