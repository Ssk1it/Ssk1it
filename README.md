### Hi, I'm Junyi — I build automation that deletes manual work

I design and ship AI-powered automations: **n8n / Make / Zapier** workflows, **LLM integrations**, and **offline transcription pipelines**.
Small, boring, reliable systems that keep running when nobody is watching.

---

#### What I actually build

**🔗 Workflow automation** — n8n, Make and Zapier flows that connect CRMs, spreadsheets, inboxes and APIs. Every one ships with retries, error branches and logging, so it doesn't fail silently at 2am.

**🤖 AI integrations** — GPT, Claude and Gemini wired into real business processes for triage, drafting and structured data extraction. Model output is treated as *untrusted*: schema validation first, repair-and-retry second, deterministic fallback last.

**🎙 Offline transcription** — local Whisper pipelines (faster-whisper + CUDA) with glossary-based term correction and clean paragraph output. No cloud, no per-minute billing, **36× realtime on a laptop GPU**.

---

#### Selected work

| Repository | What's inside |
| :--- | :--- |
| **[whisper-transcription-pipeline](https://github.com/Ssk1it/whisper-transcription-pipeline)** | Offline batch transcription → TXT / SRT / VTT / JSON. Resume-on-failure, glossary-driven term repair, chapter assembly, and honest CUDA-on-Windows troubleshooting notes. |
| **[n8n-form-intake-ai-triage](https://github.com/Ssk1it/n8n-form-intake-ai-triage)** | A 14-node production-shaped n8n workflow: form submission → AI triage → Google Sheets + alerts. Ships with a per-node breakdown, credential checklist and import guide. |
| **[llm-triage-classifier](https://github.com/Ssk1it/llm-triage-classifier)** | How to make unreliable model output safe to build on. Strict JSON schema, repair-and-retry loop, keyword fallback that never fails. 23 offline tests, runs with no API key. |

---

#### How I work

- You get the **exported workflow file**, a credentials setup guide and a short walkthrough. You own it — no lock-in, no monthly fee to me.
- Everything is documented, so your team can maintain it after I'm gone.
- Fixed scope, clear timeline, and I flag problems early instead of billing you for surprises.
- If automation isn't worth it for your case, I'll say so.

---

**Stack** — n8n · Make · Zapier · Python · REST APIs · OpenAI API · Google Sheets · Airtable

📬 **Open to freelance projects** — reach me on [Upwork](https://www.upwork.com/freelancers/~0137e13d534860d050)
