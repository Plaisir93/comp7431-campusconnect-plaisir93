# Lab09 Multimodal Journey Evidence
Branch: feature/week-9-multimodal-integration
## Journey A — Supported
- Input method used: text / voice
- RAG answer observed:
- Citation or source observed:
- Voice behavior:
- Video remained optional: yes / revise
## Journey B — Unsupported
- Question used: Thanksgiving dining hall hours
- Abstention or human next step observed:
- Text fallback worked with video muted/skipped: yes / revise
## Traceability
- Requirement: one optional multimodal CampusConnect journey
## Files changed (Lovable):
- src/components/campus/AskText.tsx: the text question box
- src/components/campus/VoiceCard.tsx: the "Ask by voice" card with your ElevenLabs widget
- src/components/campus/VideoCard.tsx: the "Watch the orientation" card with your HeyGen video and the "AI-generated presenter — not a live staff member." caption
- src/lib/campus-guide.ts: the approved IT guide the text box answers from
- src/lib/campus-guide.test.ts: tests that off-topic questions get referred to a human (passing)
- src/types/elevenlabs.d.ts: lets the code accept the ElevenLabs widget tag

- Known limitation:
