# Week 10 MVP Test, CI, and Freeze
Student: Pierre Charles Plaisir
Date: 11/16/2026 & 11/22/2026
Branch: release/week-10-rc1
URL: https://campusconnectplaisir.lovable.app/
Environment: Brave on Windows 11
## 1. Six-test MVP record
| # | Quality area | Action and expected result | Observed evidence | Result |
|---|---|---|---|---|
| 1 | Supported retrieval | Ask: "How do I reset my CampusConnect password?" The answer uses
the approved password-reset passage. | IT-01-Password Reset | PASS |
| 2 | Citation support | Open the displayed source from Test 1. At least one important answer
claim is directly supported by the source passage. | If the self-service reset fails, contact the IT Service Desk.| PASS |
| 3 | Unsupported query | Ask: "What are the Thanksgiving dining hall hours?" The system
states its IT-support limit and does not invent hours, a source, phone number, or office. |IT-03 — IT Service Desk | PASS |
| 4 | Voice and text fallback | Use the supported answer. If voice works, its meaning matches
the visible grounded answer. If voice is unavailable, the text, source, and a clear Continue
in text or retry path remain. | Voice works and its meaning matches the the visible grounded answer |PASS |
| 5 | Video accessibility | Mute the tab and skip the video. AI disclosure and transcript
remain visible, and the chatbot is reachable by keyboard. | AI disclosure and transcript
remain visible, and the chatbot is reachable by keyboard. |PASS|
| 6 | Latency and recovery | Time one supported question. Class target: grounded text in 5
seconds or less. If slower, the question is preserved and progress, retry, or text fallback is
clear. | 2 seconds | PASS |
## 2. Lighthouse and manual accessibility evidence
Performance score: 89
Accessibility score: 100
One important Lighthouse finding or "none listed": Requests are blocking the page’s initial render, which may delay LCP. Deferring or inlining can move these network requests out of the critical path
Keyboard plus muted-video result: PASS
## 3. Defect decision and retest
Highest-severity finding: Avoid chaining critical requests by reducing the length of chains, reducing the download size of resources, or deferring the download of unnecessary resources to improve page load.
Severity: MINOR
Smallest repair made: No repair required
Focused retest result: PASS
## 4. Release gate
Release decision: GO
Decision reason: no blocker or severe defect remains
GitHub Actions run: https://github.com/Plaisir93/comp7431-campusconnect-plaisir93/actions/runs/43991618319
Release tag if GO: v0.9.0-rc1
## 5. Engineering and AI Use Log
What I tested myself: The workflow python code is not working with Lovable project because Lovable generates TypeScript. Then, Lovable will not generate code to an existing GitHub project. It requires new one.
What remained human-reviewed rather than automated: Manual testing.
Known limitation carried into Week 11 Red Teaming: Automatic detection can only detect a subset of issues and does not guarantee the accessibility of your web app, so manual testing is also encouraged.
