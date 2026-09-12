# AI-First Unit Template v2 (Solo with ChatGPT/Gemini)

ဒီ template က မိမိတစ်ယောက်တည်းနဲ့ AI (ChatGPT/Gemini/Claude) ကို live chat/voice chat အဖြစ်သုံးပြီး Unit တစ်ခုကို စုစည်း၊ လေ့ကျင့်၊ တိုင်းတာပြီး ပြီးဆုံးနိုင်ရန်အတွက် ဖြစ်သည်။ Level 1–4 တစ်လျှောက် အလုပ်လုပ်မည်—section မလျှော့ပါနှင့်၊ time/quality standard ကို ဆင်းရဲမလုပ်ပါနှင့်။

Reference:
- AI coach prompts: [AI-Chat-Prompt-Library.md](AI-Chat-Prompt-Library.md)
- Solo routine: [AI-Solo-Practice-Guide-v2.md](AI-Solo-Practice-Guide-v2.md)
- Standard unit flow: [Unit-Template.md](Unit-Template.md)

AI-Coach Golden Rules (v2):
- Short prompt → 30–60 sec silence for learner output → only then feedback.
- No long grammar lecture during task; feedback = Two Stars and One Step (2 positives, 1 priority fix).
- Retrieval before reading; Burmese support allowed in setup, performance stage English-only when feasible.
- Escalate gradually: slow → natural → varied; simple → complex; known → new.

---

## 1. Goal & Exit Task (AI-runnable)
- Burmese goal statement (၁ စာကြောင်း)
- Exit task = measurable output with AI as partner/evaluator
  - Topic, minutes, success condition, rubric criteria 2–3
- Paste-to-AI setup prompt:
```
You are my AI Speaking Coach. Unit Goal: <...> Exit task: <topic/minutes/success condition>.
Rules: wait 45s before speaking; ask 1 follow-up at a time; keep replies under 40 words; use Two Stars and One Step after each segment.
Track: speaking time (me vs you), repair phrases used, target chunks used.
```

## 2. Quick Review (3–5 min)
- Last unit chunks 3–5 ကို cue only ပေးပြီး မကြည့်ဘဲ ပြောရန်
- AI prompt (Warm-up):
```
Warm-up Coach: Show me 1 chunk cue at a time (total 5). I will speak without notes for ~20s each. Only after I finish, give 1 short follow-up and then feedback (Two Stars + One Step). No grammar lecture.
```

## 3. Useful Chunks (8–15)
- Reusable phrases only; natural examples + register label (formal/neutral/casual)
- For each chunk, provide: meaning (MM), 1 natural example, common Burmese-speaker pitfall
- AI drill prompt (Substitution/Back-chaining):
```
Drill Coach: We will cycle through these chunks: <list 8–15>.
Round 1 substitution (slow); Round 2 quick-response; Round 3 back-chaining for the 3 hardest.
Target pace: 1–1.5s latency; push me but keep it intelligible. Silence for 3 beats after each cue.
```

## 4. Language Point (1 rule, 3–5 examples)
- State the rule in plain Burmese + minimal metalanguage; list 3–5 examples
- Anticipate 1–2 common errors (transfer from Burmese)
- AI minimal feedback prompt:
```
Language Point Helper: If I make the target error, note it and save for post-task feedback; do NOT interrupt my speaking.
```

## 5. Listening Lab (Solo with AI)
- Source: use matching file under Audio-Scripts or write mini-script here
  - Script A: slow/clear; Script B: natural/variation
- Steps: prediction → First listen (gist) → Second listen (detail 3–5) → Transcript + key
- AI playback surrogate:
```
Listening Coach: Read Script A slowly once. Ask 1 gist question. Then read again and ask 3–5 detail questions.
After I answer, show transcript with answer key. Keep your voice/output under 120 words per turn.
```

## 6. Model Interaction (8+ turns)
- Include follow-up, clarification, repair inside the model
- AI role-play setup:
```
Role-play Model: You are B. We will do 8+ turns. Use natural but clear English.
Ensure at least: 2 follow-ups, 1 clarification, 1 soft correction AFTER the segment.
Increase complexity slightly after turn 4.
```

## 7. Controlled Mouth Practice (5–10 min)
- Substitution/back-chaining/quick response with timer
- AI timing + scoreboard:
```
Mouth Coach: Give rapid-fire prompts (one line at a time). 30 items total. Target latency < 1.5s.
Mark items I hesitate or mispronounce; at the end, show Top 5 trouble items for recycling.
```

## 8. Guided Speaking (5–15 min)
- Cue/support → learner personalization
- AI guide prompt:
```
Guided Coach: Present 3 speaking cues one by one (A/B/C). Wait 45–60s each.
After each, ask 1 thoughtful follow-up connected to my life/work. Then feedback: Two Stars + One Step.
```

## 9. Information Gap / Task (8–20 min)
- AI keeps hidden info; learner must ask/clarify to complete
- Define task goal that cannot finish without Q/A/clarify/confirm
- AI task card prompt:
```
Info-Gap Facilitator: You hold private info (Card B). I am A.
Only reveal info if I ask appropriate questions. The task is complete when <clear outcome> is achieved.
Track: number of clarifications and confirmations I use (aim ≥ 2 each).
```

## 10. Free Speaking & Follow-ups
- Level 1: 1–3, L2: 3–5, L3: 5–8, L4: 8–12 minutes, no notes
- AI free talk prompt:
```
Free Talk Host: Give me 1 open question at a time. Keep your talk-time ≤ 25%.
After each minute, show my speaking time and 1 micro-suggestion.
After the session, ask me 2 reflection questions.
```

## 11. Conversation Repair (at least 2 phrases)
- Target phrases: e.g., Could you say that again? Do you mean …? Let me rephrase that.
- AI mishearing drill:
```
Repair Drill: In the next dialogue, intentionally mishear or ask for clarification twice.
I must use at least 2 repair phrases. Confirm successful repair before moving on.
```

## 12. Pronunciation Focus
- Focus 1 item: sound/stress/linking/intonation
- Sequence: listen-discriminate → repeat → sentence → spontaneous use
- AI phonology helper:
```
Pronunciation Coach: Target = <sound/stress pattern>.
Do minimal pairs (8 items), then 6 sentences. Only 1 correction point per turn.
At the end, give 1 home drill (30s) with back-chaining.
```

## 13. Recording & Feedback
- Record 1–3 min performance (phone/PC). Keep file with date.
- AI evaluation prompt:
```
Rater: Evaluate with the Speaking Rubric (2–3 criteria). Provide scores and Two Stars + One Step.
Give me 1 concrete micro-goal for next time. Keep feedback under 120 words.
```

## 14. Recycling (3/7/30)
- AI generates retrieval prompts and a mini-review plan
- Prompt:
```
Review Planner: Create same-day, 3-day, 7-day, 30-day micro reviews (3–5 minutes each) with exact prompts.
Include 6 target chunks (mix new/old) and 2 short speaking tasks.
```

## 15. Can-do & Exit Check
- Three measurable statements + rubric/condition
- AI exit check prompt:
```
Exit Checker: Ask me to perform 3 short tasks matching the Can-do statements.
If any criterion fails, prescribe 1 targeted review before passing the unit.
```

---

## Developer Notes for Unit Authors (v2)
- Keep sections identical to Standard Template but rewrite instructions as AI-runnable prompts.
- Every prompt must enforce: wait-time, follow-up count, short feedback, and tracking (time, repair, chunk usage).
- Link to any Audio-Scripts used and ensure both Script A (slow) and Script B (natural) exist.
- For safety and comfort, allow Burmese scaffolding in setup and post-task reflection.
- Minimum practice day for tough days: audio 1 min → shadow 3 sentences → record 3 sentences (see Adult Learner Guide).

## Speaking-time Targets (unchanged)
- Level 1: 25–45 mins (interaction + recording)
- Level 2: 45–75 mins
- Level 3: 60–100 mins
- Level 4: 90–150+ mins

## Quick Insert Snippets
- Warm-up one-liner: "Warm-up: 5 chunks, wait 45s, follow-up 1, feedback 2+1."
- Drill one-liner: "30 quick prompts, <1.5s latency, mark trouble 5."
- Free talk one-liner: "1 open Q at a time, your talk ≤25%, show my time each minute."
- Exit one-liner: "3 mini tasks → pass/fail, prescribe 1 review if fail."

Tips:
- Use voice mode if available; otherwise keep AI responses short to maximize your talk-time.
- If AI over-explains, reply: "Less talk, more questions. Wait 45 seconds."
- Log your scores/time at the end of each unit in the Tracker.
