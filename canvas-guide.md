# The Responsible AI Design Canvas: a field guide

This guide explains the method from *Good Intentions Are Not Enough*. Use it before deployment, ideally early in product discovery with a varied group of people affected by the proposed technology. Repeat the inquiry as contexts change. The intention is to make **better choices**, not accumulate the largest list of risks.

## Begin with a well-defined use case

State the problem and *human* benefit sought, what the AI does (and cannot do), the workflow around it, how much autonomy it has, and the decision you face. Note facts, assumptions, and things you haven't learned yet. Don't supply sensitive records to public chatbots.

## Four elements: ways to bring reality into view

1. **Ground Truth — what happens on the front lines?** How do people actually work and respond? What workarounds, silent checks, edge cases, limitations, and changes in workload are hidden by the ideal process?
2. **Stakeholder POVs — how are different people affected?** Include direct users, indirectly affected groups, front-line workers, decision-makers, and people who cannot easily challenge an outcome. **Do not confuse imagined stakeholder voices with genuine research.**
3. **Risk Profiles — which known failure modes matter here?** Look at the *specific AI technology* and its known technical characteristics, plus failures that arise when that technology meets the particular workflow, incentives, institutions, and people. A model can work as intended and still contribute to harm.
4. **Past Precedent — what can we learn from analogous experience?** Examine established research, past organizational accidents, historical disparities, and verified incidents. An analogy opens a question; it doesn't prove the same outcome will recur. Distinguish established events, claims in litigation, and fictional examples.

## Three moves: change how you examine those elements

**ZOOM — broaden and narrow the view.** Move from one affected person to team, organization, industry, and society; from immediate effects to cumulative and long-term consequences. At every level, ask what evidence could validate or falsify a concern.

**SHIFT — change whose perspective is centered.** A product manager, customer, front-line worker, leader, regulator, and community member may define success or bear constraints differently. Who is missing, and who has power to contest an outcome?

**CONNECT — trace what interacts.** A model error, workload target, incentive dashboard, slow escalation route, and vague owner may seem manageable alone. What happens when they reinforce each other? Who notices, who responds, and who has authority to act? Identify mechanisms, not just alarming endpoints.

These moves are **not mandatory sequential stages**; revisit them as your understanding develops.

## The organizational systems insight

James Reason's research on system accidents distinguishes active failures from latent conditions, and describes safeguards whose weaknesses can align. In AI products, even a nominal human approval step may cease to provide meaningful scrutiny if time, incentives, information, or authority make disagreement difficult. Product teams can change those conditions. See [Reason (2000)](https://doi.org/10.1136/bmj.320.7237.768).

## Moral imagination: change the question, not just the controls

Well-intentioned organizations may inherit a narrow definition of the problem. Instead of assuming the task is to automate a status quo, ask what lives you aim to improve, whose narrative defines success, and what other ways of organizing the work are imaginable. **Automate, augment, and reimagine** are examples of different frames—*not steps, rankings, or a ladder.* Sometimes begin by reimagining. Sometimes the right boundary is *do not apply AI to this choice*.

In ClaimAssist, “settle claims faster” differs from “help people recover from loss.” Neither speed nor efficiency is valueless; the second framing broadens what counts as a good outcome.

Moral imagination is **necessary but not sufficient** for responsible decisions: perspectives must be tested with evidence; values and tradeoffs require human deliberation; accountable people must choose.

## From inquiry to product agency

Invite choices rather than dictate them: change eligibility, bound autonomy, improve evidence, protect judgment, adjust incentives, add meaningful recourse, test realistic conditions, monitor what matters, name accountable owners, and define when to intervene, pause, or stop. Specify tolerance and boundaries through appropriate organizational processes; the chatbot cannot set them for you.

Capture what changed in your understanding and what still needs investigation. Revisit when models, workloads, users, policy, incentives, or operating conditions change.

## Questions you can ask at any point

- “What's our happy-path assumption?”
- “What could go wrong **even if the model behaves as intended**?”
- “ZOOM out one level; now ZOOM into a person directly affected.”
- “SHIFT to someone with little ability to appeal.”
- “CONNECT our metrics, workload and escalation design.”
- “Which of these are facts, hypotheses, analogies, and gaps?”
- “What if we're solving the wrong problem?”
- “What would we do without AI?”
- “Who can stop deployment if reality differs from expectations?”

See [technical risks](references/technical-risk-library.md), [sociotechnical risks](references/sociotechnical-risk-library.md) and [sources](references/sources.md) for optional starting points.
