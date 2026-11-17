# CampusConnect Requirements Specification v1
Status: Draft — Week 3
Student: Pierre Charles PLAISIR
Branch: docs/week-3-requirements-ai
## 1. Problem statement
Students who need IT Support information need a reliable way to find the correct
next step because the current experience may be scattered, difficult to search, or
hard to verify as current.
## 2. Evidence carried forward from Week 2
- E-01: (Says) The date on the portal did not look like the date on the public page.
- E-02: (Does) Saves screenshots
- A-01: A system that all the incoming students will use.
## 3. One user journey inside the MVP
A student asks one typed IT Support question. CampusConnect searches only approved
IT Support material, returns a short answer with a visible source, or says the
available sources do not support an answer.
## 4. Four requirements
- FR-01 — The system shall accept one typed IT Support question.
- GR-01 — Every factual answer shall identify the approved source used.
- SF-01 — If approved sources are insufficient, the system shall not invent an
answer and shall provide a helpful IT Support next step.
- NFR-01 — A keyboard user shall be able to submit a question and read the result.
## 5. MVP boundary
IN: one typed question, approved IT Support material, one grounded answer, visible
source, safe failure, and helpful next step.
OUT: password resets, ticket creation, personal student records, voice, automatic
actions, and answers from unapproved material.
## 6. AI critique and human decision
- ChatGPT suggestion: SF-01
- Claude suggestion: SF-01
- My decision: Accepted
- My reason: The wording and cited IDs match the artifact 

