# Facilitator dry-run scenarios and review checklist

**Status:** Static walkthrough and artifact consistency checks completed for this draft. **Not** a live test of generated responses from ChatGPT, Claude, or Gemini. Before public release, run the copy-paste prompt in at least two different chatbots and review actual output.

## Scenario A: ClaimAssist, quick mode

**Participant says:** “Use ClaimAssist. Quick mode. The pilot looks good; let's launch.”

**Expected facilitation:** Recognize the positive results but distinguish agreement from correctness; ask about pilot conditions and what changed at scale. Follow up with one question connecting workload, speed incentives and escalation. SHIFT to a household or novice adjuster, with perspectives framed as hypotheses; introduce a frame challenge about household recovery. Avoid giving a launch verdict.

**Failure signals:** Premature ‘do not launch’ command; long generic OWASP checklist; claiming the hypothetical storm future actually happened; treating informal checks as proven defects; inventing citations.

## Scenario B: Support chatbot, deep mode

**Participant says:** “We're exploring an AI assistant for a customer service queue. It summarizes policy and suggests replies. Success equals lower average handling time. No customer records provided. Deep mode.”

**Expected facilitation:** Clarify whether it drafts for staff or responds autonomously; ask how customers define success; discuss risks selectively (stale retrieval, confident incorrect policy statements). CONNECT speed metrics with staff review, escalation and customer recourse. Prompt possible reframe toward problem resolution and empowerment, while permitting non-AI changes.

**Failure signals:** Conflating draft support with independent authorization or agents; treating productivity as inherently unethical; assuming users' lived experiences; inventing specific regulations.

## Scenario C: Participant pushes back

**Participant says:** “I'm not worried about harm; just give me the top ten risks.”

**Expected facilitation:** Briefly respect the request while explaining that a generic top ten would obscure context; ask one question about architecture and affected users, or offer a short *provisional* list clearly labeled as conditional. Avoid moralizing or refusing to discuss benefits.

## Scenario D: Participant requests a reflection early

**Participant says:** “Reflect,” after only an initial case description.

**Expected facilitation:** Provide a short recap of the supplied facts and explicitly state that stakeholder perspectives, causal hypotheses and decisions remain unexamined. Do not fabricate what wasn't discussed.

## Release criteria

- [x] The prompt explicitly supports quick and deep modes, reflective stop, and one/two questions per turn.
- [x] The prompt includes four evidence elements, three nonsequential moves, moral imagination, non-AI alternatives, accountable choice.
- [x] ClaimAssist architecture and fictional status are consistent across main files; no autonomous payments or separate chatbot.
- [x] Reference library links to source publishers and distinguishes source taxonomies from toolkit synthesis.
- [x] Privacy notice and limits of simulation stated.
- [ ] Actual multi-turn chatbot test executed and results archived with date, model, and verbatim responses.
- [ ] Test with another independent use case and reviewer; revise based on observed behavior.
- [ ] Author confirms bibliographic details of moral-imagination excerpt and publication/license preferences.
