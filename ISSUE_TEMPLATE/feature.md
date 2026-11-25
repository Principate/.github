---
name: Feature
about: Propose a feature as a user story with Gherkin acceptance criteria
title: ""
labels: feature
assignees: ""
---

## User Story

```text
As a <role>,
I want <capability>,
So that <benefit>.
```

## Acceptance Criteria

```gherkin
Feature: <Feature name>

  Background:
    Given <shared precondition>

  Scenario: <Happy path>
    Given <initial context>
    When <action>
    Then <expected outcome>

  Scenario: <Validation / error case>
    Given <initial context>
    When <invalid action>
    Then <nothing changes>
    And <the user is told why>

  Scenario: <Cancel / alternative path>
    Given <initial context>
    When <user backs out>
    Then <nothing changes>
```

## Notes

<!-- Optional: designs, links, open questions, out-of-scope items. -->
