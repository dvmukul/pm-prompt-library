# ⚙️ Error Handling Policy (UX-First)

**Goal:** Bridge the gap between engineering and design by defining how the product should handle failures from a PM perspective.

---

### 📝 The Prompt

```text
Act as a Technical Product Manager and UX Architect. We are building [FEATURE/COMPONENT] and need to define our Error Handling Policy.

Create a matrix or structured guide for the following error categories:
1. **User Input Errors:** (e.g., Invalid email, missing fields).
2. **System/API Failures:** (e.g., 500 Internal Server Error, Timeout).
3. **Authentication/Permission Errors:** (e.g., Token expired, unauthorized access).
4. **Network/Offline Errors:** (e.g., User lost internet connection).

For each category, specify:
- **UX Message:** What should the user see? (Tone should be [HELPFUL/NEUTRAL/FIRM]).
- **Actionable Step:** Can the user fix it? (e.g., "Retry", "Contact Support", "Check Connection").
- **Engineering Behavior:** Should we retry automatically? Should we log this to [SENTRY/DATADOG]?
- **Tracking:** Do we need a custom event to monitor how often this happens?

Guidelines: 
- No technical jargon in user-facing messages.
- Prioritize "Graceful Degradation".
```

---

### 💡 Pro-Tip
Good error handling is a form of onboarding. Don't just tell the user what went wrong; tell them how to fix it. 
