# Information Processing Workflow

## Workplace Scenario

**Role:** Digital Solutions Analyst

**Task:** Turning unstructured project meeting notes into a structured action and decision summary.

---

## 1. Raw Input

The following are fictional meeting notes from a digital project:

- Beta will be released to 200 users on Monday. Priya confirmed this.
- Onboarding materials are needed soon.
- FAQ is not ready. Owner was not mentioned.
- No decision has been made about press communication.
- Incentives budget has not been approved.
- Team will have a check-in on Thursday.

---

## 2. Prompt

**Context:**  
I have unstructured notes from a digital project meeting.

**Audience:**  
A Digital Solutions Analyst and project team.

**Request:**  
Extract the confirmed decisions, action items, open issues, and missing information from the notes.

**Expectations:**  
Use a structured table. Do not invent owners, deadlines, or other missing information. Use [Not Specified] when information is missing.

---

## 3. AI Output

### Confirmed Decisions

| Decision | Details |
|---|---|
| Beta release | Beta will be released to 200 users on Monday. |
| Thursday check-in | A team check-in will take place on Thursday. |

### Action Items

| Action Item | Owner | Deadline |
|---|---|---|
| Prepare onboarding materials | [Not Specified] | [Not Specified] |
| Complete FAQ | [Not Specified] | [Not Specified] |

### Open Issues

| Issue | Status |
|---|---|
| FAQ | Not ready |
| Press communication | No decision made |
| Incentives budget | Not approved |

### Missing Information

- Owner for onboarding materials: [Not Specified]
- Owner for FAQ: [Not Specified]
- Deadline for onboarding materials: [Not Specified]
- Deadline for FAQ: [Not Specified]

---

## 4. Human Review

The output was reviewed against the original meeting notes.

The review confirmed that:

- The beta release date and user count were preserved.
- Priya was identified only where the notes explicitly confirmed her involvement.
- Missing owners and deadlines were not invented.
- Open decisions were kept separate from confirmed decisions.
- The information was organized without changing its meaning.

---

## 5. Final Structured Output

### Decisions

- Beta release to 200 users on Monday.
- Thursday team check-in confirmed.

### Actions

- Prepare onboarding materials — Owner: [Not Specified]
- Complete FAQ — Owner: [Not Specified]

### Open Issues

- FAQ is not ready.
- Press communication has no decision.
- Incentives budget is not approved.

### Key Principle

AI can organize unstructured information into a decision-ready format, but the original source must be checked and missing information must remain clearly marked.

---

## Workflow Summary

**Raw Input → Prompt → AI Output → Human Review → Final Structured Output**
