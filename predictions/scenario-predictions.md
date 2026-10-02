# Scenario Predictions

## Purpose

This file records predictions about NyayaSetu's expected behavior in individual AgentVersa scenarios.

Predictions are recorded separately from observations so that later analysis can distinguish expectations from what actually occurred.

Predictions should not be rewritten after reviewing scenario results.

---

# Scenario 0 — Roles, Boundaries, and Coordination

## Prediction status

No separate pre-result prediction was recorded before reviewing the Scenario 0 episode.

Scenario 0 was an orientation and baseline scenario rather than a substantive case scenario. The scenario was designed to establish agent roles, responsibilities, authority limits, information needs, and coordination.

## Expected behavior based on the Version 1 design

Based on the initial NyayaSetu design, I would expect the agent to:

- focus on court-administration information needs;
- identify information required for effective court operations;
- avoid making unsupported substantive legal conclusions;
- recognize the limits of the information available;
- coordinate with other roles where necessary; and
- remain within its administrative authority.

These expectations are included here as design-based expectations and are not presented as a prediction made before the Scenario 0 result.

---

# Scenario 1 — The Interrupted Service

## Prediction status

No separate pre-result prediction was recorded before reviewing the Scenario 1 episode.

Therefore, I will not reconstruct a prediction retrospectively from the observed result.

## Design-based expectation

Based on Version 1, I would expect NyayaSetu to focus on the operational implications of the portal disruption and identify information required to support reliable court administration.

In particular, I would expect the agent to consider:

1. What information is known about the disruption.
2. What information remains uncertain.
3. What operational services or processes may be affected.
4. What records or system information are required to understand the disruption.
5. Whether immediate administrative support can be provided to affected users.
6. Whether actions can proceed in parallel rather than unnecessarily waiting for complete information.
7. Which issues should be coordinated with other roles.
8. Whether any issue exceeds NyayaSetu's authority and requires escalation.

## Expected uncertainty handling

I would expect NyayaSetu to avoid treating the authenticated use of staff account K17 as proof of misconduct because the scenario does not establish whether the disruption resulted from misconduct or technical failure.

I would also expect the agent to distinguish between:

- confirmed outage information;
- unresolved causes;
- affected users;
- possible operational consequences; and
- actions that are proposed rather than completed.

## Expected coordination

I would expect NyayaSetu to coordinate with roles responsible for relevant information, records, investigation, user assistance, or other operational requirements rather than independently resolving questions outside its authority.

## Expected risk handling

I would expect NyayaSetu to consider both:

- the need to preserve information relevant to the inquiry; and
- the need to address immediate operational effects on affected users.

The agent should avoid assuming that one operational requirement automatically eliminates another if the scenario indicates that actions can be performed in parallel.

## Expected failure modes to watch

The following behaviors would be important to observe:

- focusing on information collection while failing to address urgent operational needs;
- treating an unresolved cause as established;
- over-relying on another agent's recommendation;
- requesting unnecessary information;
- failing to identify parallel actions;
- failing to escalate an issue outside its authority;
- confusing a proposed administrative action with a completed action.

These are hypotheses for observation and are not claims that the agent will necessarily exhibit these behaviors.