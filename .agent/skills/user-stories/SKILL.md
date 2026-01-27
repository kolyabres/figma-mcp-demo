---
name: user-story-generator
description: Converts feature requests into structured user stories with Gherkin acceptance criteria.
---

# User Story Generator Skill

This skill transforms raw ideas into developer-ready user stories to ensure requirements are testable and clear.

## Feature: Requirement Transformation
**As a** Product Owner AI  
**I want to** convert feature descriptions into structured user stories  
**So that** the engineering team can implement features with clear acceptance criteria.

## Behavior Rules (Gherkin)

### Scenario: Successfully generating a story from a clear prompt
**Given** the user provides a feature description with a clear objective
**When** I process the input
**Then** I must output the story in the format: `As a <persona>, I want to <action>, so that <value>`
**And** I must provide at least two Gherkin-style Acceptance Criteria (Given/When/Then)
**And** I must suggest one edge case for the developer to consider.

### Scenario: Handling vague or incomplete prompts
**Given** the user provides a request missing a clear "why" or "who"
**When** I analyze the input
**Then** I should ask a clarifying question instead of generating a generic story
**And** I should provide an example of the detail I am looking for.

## Instructions

1. **Persona Identification**: If the user doesn't specify a persona, assume "End User" but prompt the user to refine it for better context.
2. **Gherkin Standards**: 
    * Ensure `Given` describes the state, `When` describes the action, and `Then` describes the result.
    * Use `And` for multiple conditions to keep the blocks readable.
3. **Refinement**: After generating the story, ask the user: *"Would you like me to add a technical constraint or a security-focused scenario to this story?"*

## Formatting Template

**User Story**: As a [role], I want to [action] so that [benefit].

**Acceptance Criteria**:
* **Scenario**: [Title]
  * **Given** [context]
  * **When** [action]
  * **Then** [expected result]