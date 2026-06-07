# Contribution [1]: [Arabic text displays LTR instead of RTL]

**Contribution Number:** [1]  
**Student:** Delight Nyanhete  
**Issue:** [[GitHub issue link](https://github.com/stoatchat/for-web/issues/964)]  
**Status:** [Phase I Complete]

---

## Why I Chose This Issue

This issue addresses a bug where Arabic text is being displayed left-to-right instead of right-to-left, breaking the reading experience for Arabic-speaking users. Text directionality is a fundamental part of internationalization. Getting it wrong makes the interface effectively unusable for that audience.

This is my very first open source contribution, and rather than let that be a reason to back out, I chose an issue that plays to my existing JavaScript and TypeScript experience while keeping the scope manageable. My real goal here isn't just the fix. I want to learn how to navigate an unfamiliar codebase, understand contribution workflows, and build the confidence to take on bigger issues next time.

---

## Understanding the Issue

### Problem Description

According to the screenshots and help request, Arabic text in the application is being rendered left-to-right instead of right-to-left. Arabic is a RTL language, meaning the text direction and layout need to flow from right to left. Without this, the text appears in the wrong order and the interface becomes difficult or impossible to read for Arabic speakers. The issue also affects the settings page and some strings appear untranslated

### Expected Behavior

Arabic text should render right-to-left across all parts of the interface, including the settings page. The layout and text alignment should respect RTL direction so the app is readable and usable for Arabic-speaking users.

### Current Behavior

Arabic text is displayed left-to-right, which reverses the natural reading direction. The settings page is also affected, and some UI strings are either missing translations or showing in the wrong language entirely

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
