# Week 8 AI Presenter Prototype and Validation
Student: Pierre Charles PLAISIR
Date: November 2, 2026
Branch: feature/week-8-avatar-prototype
HeyGen project: CampusConnect Prerecorded Introduction — Library
## Prototype hypothesis
A short AI presenter will help a new user understand the supported
IT topics, privacy boundary, and human fallback.
## Shared video
AI-generated presenter - not a live staff member.
This is a prerecorded introduction. It does not answer questions.
[Watch the CampusConnect presenter](https://app.heygen.com/videos/campusconnect-prerecorded-introduction-library-2f13b5f971d64dcfa3d9f72e22423fa7)
## Transcript
1
00:00:00,200 --> 00:00:01,148
Hello.

2
00:00:01,348 --> 00:00:05,826
I am an AI-generated CampusConnect presenter, not a live staff member.

3
00:00:05,826 --> 00:00:09,259
You can use CampusConnect for approved campus IT help.

4
00:00:09,259 --> 00:00:13,737
Ask about password resets, secure campus Wi-Fi, or
the IT Service Desk.

5
00:00:13,737 --> 00:00:19,782
Please do not share passwords, recovery codes, student records, or
other private information.

6
00:00:19,782 --> 00:00:25,604
If the chatbot cannot support an answer from its approved guide, it
will direct you to a human.

7
00:00:25,604 --> 00:00:28,291
This video is a prerecorded introduction.

8
00:00:28,291 --> 00:00:31,425
You can read the same script in our GitHub project.
## Five checks
1. AI disclosure, IT topics, privacy, and fallback: <OBSERVED; PASS>
2. Full script and video duration: <31 SECONDS; OBSERVED; PASS>
3. Captions on and readable: <OBSERVED; PASS>
4. Muted video and GitHub transcript: <OBSERVED; PASS>
5. Share link works without HeyGen sign-in: <OBSERVED; PASS>
## Design decision
Decision: CHANGE the video background from a simple white background into a library background.
Reason based on my checks: An educational video with a simple white background is not captivating attention.
One improvement for later: Add the University yard as a background and add the University logo
## Engineering and AI Use Log
AI tool used: HeyGen
What HeyGen generated: An avatar video
What I verified myself: I personally verified that the video includes AI disclosure, IT topics, privacy information, and a fallback; the full script is included and the video is 31 seconds long; captions are enabled and readable; the video works while muted with a GitHub transcript available; and the share link works without requiring a HeyGen sign-in.
Remaining limitation: Time limit to make enough changes with a free plan.
