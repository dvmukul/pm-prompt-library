# 📝 Gherkin Acceptance Criteria

**Goal:** Transform high-level user stories into precise, executable acceptance criteria using the Gherkin (Given/When/Then) format.

---

### 📝 The Prompt

```text
Act as a Technical Product Manager and QA Lead. I have the following User Story:
"[INSERT USER STORY - e.g., 'As a user, I want to reset my password so that I can regain access to my account.']"

Generate a comprehensive set of Acceptance Criteria using the Gherkin format (Given, When, Then). 

Include:
1. **Happy Path:** The most common successful journey.
2. **Edge Cases:** Boundary conditions (e.g., expired links, weak passwords).
3. **Error States:** How the system handles failures (e.g., server down, incorrect OTP).
4. **UI/UX Requirements:** Specific visual or interaction feedback needed.

Format each scenario clearly:
Scenario: [Description]
Given [Precondition]
When [Action]
Then [Expected Result]
```

---

### 💡 Pro-Tip
Brevity is key in Gherkin. Keep each step focused on one action or observation to make it easier for developers to write automated tests.
