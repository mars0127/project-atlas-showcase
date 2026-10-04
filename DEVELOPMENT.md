# What is behind the screenshots?

Project Atlas has a working local application and database behind these screens. This public showcase presents selected real browser captures and a project explanation; it does not provide an account or a hosted copy of the application.

## Explore the development work

- [Development repository](https://github.com/mars0127/project-atlas).
- [Existing commit history](https://github.com/mars0127/project-atlas/commits).

The repository includes earlier implementation milestones. The most recent local development shown in the screenshots may be ahead of its published commits. The showcase has a separate history so internal testing records and local credentials are not copied into this gallery.

## Implemented and being refined

| Area                | Working local behavior                                                                                          |
| ------------------- | --------------------------------------------------------------------------------------------------------------- |
| Account setup       | Invitation and email-code verification, followed by guided profile setup.                                       |
| Athlete context     | Training background, goals, schedule and separate locations with their own equipment and usable space.          |
| Program lifecycle   | Athlete-selected 1–4-week programs, accepted inputs, fixed duration and explicit cancellation or completion.    |
| Workout logging     | Strength reps/load, task completion, previous-set suggestions, rest timing and session summaries.               |
| Weekly continuation | A new proposal based on saved work, weekly feedback and changed circumstances; earlier history stays preserved. |
| Progress            | Saved training records and an illustrative view of planned versus recorded training coverage.                   |

The platform separates shared account, scheduling and recording concepts from sport-specific rules. Hockey off-ice performance is the first training package being explored, rather than a claim that the same rules already serve every sport or population.

## A few engineering problems I have worked through

**Signup recovery.** A valid email code was being rejected because the separate Atlas invitation had expired. The application now identifies inactive access after verifying identity, while keeping invalid-code responses generic and requiring accepted access before saving a browser session.

**Preserving what actually happened.** A planned set and a recorded set are different facts. Completing a workout cannot silently turn missing work into completed work. Corrections and new programs must preserve the earlier record.

**Using the profile meaningfully.** Equipment, available space, training background, goals and the athlete's week need to affect eligibility, scheduling and training choices. A longer list of profile questions is not useful by itself.

**The whole workflow.** Save-and-continue must actually advance setup. Finishing a week should lead to review and continuation. During a workout, the athlete needs clear targets and useful controls with minimal distraction.

## How I verify changes

The project uses TypeScript checks, source-rule checks, automated scenario/component tests, database checks and hands-on browser walkthroughs. Recent verification included program lifecycle examples for all four supported durations and focused signup/access checks. These checks help catch software mistakes; they do not establish training effectiveness or replace professional review.

I lead the product direction and testing, drawing on my athletic experience. I use AI coding tools, including Codex, while learning development and refining the requirements. The application itself uses rule-based planning rather than runtime AI-generated workouts.

## Still in progress

Training rules and workload recommendations remain experimental. Qualified programming review, broader device/usability testing and public release preparation are unfinished. The gallery's fictional test records are demonstrations of software behavior, not results from real athletes.

A live demo or screen-recorded walkthrough could be added later. At present, the screenshot gallery and development links are the public demonstration.
