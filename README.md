# Campus Writing Assistant (prototype)

Clickable prototypes of a writing-assistant task for a study on trust in AI chatbots.

| Version | Link | What it measures |
|---|---|---|
| Without WOA | https://xinruilu24-art.github.io/writing-assistant-prototype/ | Accept / dismiss for each suggestion |
| With WOA | https://xinruilu24-art.github.io/writing-assistant-prototype/woa.html | Revise -> participant estimates the revised essay's score -> AI estimate -> final estimate, plus accept / dismiss |

- Task: revise the essay so it scores higher on a 100-point checklist rubric (codes A1 to E2).
- The original essay scores 60/100. Each of the 6 suggestions is tied to a rubric item: 4 good ones each add 10 points; 2 bad ones each cost 10 points (removing a quotation's citation breaks B1; turning "may" into "prove" breaks B2).
- In the WOA version, the AI's estimate counts only the good suggestions accepted, so it is 10 points too high for every bad suggestion accepted.
- Right: a chatbot that explains each suggestion; the participant accepts or dismisses it.
- Researcher view: switch the bot's style (machine / human-like) and spelling slips (clean / typos), show good / bad labels, and see a decision log that can be copied as CSV.
