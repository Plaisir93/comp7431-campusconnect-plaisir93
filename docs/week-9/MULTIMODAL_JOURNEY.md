# Lab09 Multimodal Journey Evidence
Branch: feature/week-9-multimodal-integration
## Journey A — Supported
- Input method used: voice
- RAG answer observed: Yes
- Citation or source observed: Yes
- Voice behavior: Only activate when the user choose to start a call. Detects when the user starts speaking. Determines when the user has finished speaking. Converts speech into text. Allows users to interrupt.
- Video remained optional: Yes
## Journey B — Unsupported
- Question used: Thanksgiving dining hall hours
- Abstention or human next step observed: Human next step observed
- Text fallback worked with video muted/skipped: Yes
## Traceability
- Requirement: one optional multimodal CampusConnect journey
- Pull request URL: https://github.com/Plaisir93/comp7431-campusconnect-plaisir93/pull/5
- Reviewer: Edwin Lemus
## Files changed (Lovable):
- src/components/campus/AskText.tsx: the text question box
- src/components/campus/VoiceCard.tsx: the "Ask by voice" card with your ElevenLabs widget
- src/components/campus/VideoCard.tsx: the "Watch the orientation" card with your HeyGen video and the "AI-generated presenter — not a live staff member." caption
- src/lib/campus-guide.ts: the approved IT guide the text box answers from
- src/lib/campus-guide.test.ts: tests that off-topic questions get referred to a human (passing)
- src/types/elevenlabs.d.ts: lets the code accept the ElevenLabs widget tag
## Known limitation: 
CampusConnect can help with questions about only three topics (Password Reset, Secure Campus Wi-Fi, IT Service Desk). For any other questions related to none of these topics, the user will be directed to contact the IT Service Desk.
