# Renewal Desk: Product Case Study

## At a glance

Renewal Desk is an independent product initiative focused on software-licence and subscription lifecycle management. Its central premise is that a renewal is a decision with a deadline, not merely a date to remember.

**Status:** Working product, under active development.  
**Application source:** Maintained separately in a private repository.  
**Public demo:** Not yet published.

## The problem

A spreadsheet can record a renewal date and a calendar can send a reminder. Neither, by itself, ensures that a named person owns the decision, that the person confirms whether the service is still needed, that unanswered requests remain visible, that there is enough time to act before a notice period expires, or that the decision can be understood later.

Renewal Desk treats a renewal as a decision workflow rather than a date-only reminder.

## Product approach

1. **Make the decision deadline visible.** Account for the renewal date and notice period so the last day to cancel or change terms remains visible.
2. **Ask the owner early.** Ask the person responsible whether the subscription is still required.
3. **Keep following up.** Unanswered requests remain open and visible. Silence is not silently interpreted as approval.
4. **Record the outcome.** Preserve the response, decision and relevant history for later reference.

## Core workflow

1. Confirm whether the subscription is still needed.
2. Follow up on outstanding requests.
3. Record whether to renew, cancel, replace or change.
4. Protect the last day to cancel or change terms.

## Product surface

The working product includes a subscription and vendor registry, owner responses, reminders and follow-up, approval status, snooze, a calendar feed, reporting and export, and a twelve-month timeline called Runway.

The public showcase uses selected screenshots from the fictional-data demo. They are illustrative captures dated 12 November 2026 and do not represent customer records.

## My contribution

I initiated the product and am responsible for its product direction and development process, including problem framing, product concept, requirements, workflow design, scope and prioritisation, architecture decisions, direction of AI-assisted implementation, review and validation.

This is not a claim that every line of code was written manually. AI-assisted development is part of the build process; product direction, review and validation remain my responsibility.

## Technology

- Next.js and React
- TypeScript
- PostgreSQL
- Drizzle ORM
- Docker and Docker Compose

## What comes next

- Continue product development and validation.
- Complete the dedicated public-demo safety review.
- Deploy a controlled demo using fictional data only.
- Test access controls, reset behaviour and disabled outbound integrations.
- Publish a demo link only after external-access checks pass.

## Product and source separation

This public repository shares the product story, selected capabilities and illustrative interface screenshots. It does not contain the application source code, internal product briefs, operational configuration, environment values or deployment secrets.
