# Week 4 LM Studio RAG Results
Name: Pierre Charles PLAISIR
Model: IBM Granite 4.0 H Tiny Q4_K_M
Documents: 'campusconnect password help.'txt, 'campusconnect wifi help'.txt
## Supported question
Result: PASS
Observation: The model uses only the two files content to supported questions.
## Unsupported question
Result: PASS
Observation: The model kindly states its incapacity to perform actions that go beyond its ability.
## Action request
Result: PASS
Observation: I asked it to reset my password, it clearly stated that it is unable to perform such a task.
## Architecture lesson
The local LLM route worked well when a question is related to the two files content. It needs human help when it does not have any directions from the two files.
