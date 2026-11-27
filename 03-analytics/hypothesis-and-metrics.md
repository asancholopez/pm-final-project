# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** Frontline fleet users - drivers
- **Goal , what this user is ultimately trying to achieve:** Close out all of today's deliveries quickly and accurately so I can end my shift on time.
- **Friction / moment of misery , the specific pain blocking their goal:** At end of shift, a dispatcher driver closing a large number of deliveries skips the compliance checks (including cost and invoice fields) because each takes 3 extra screens. Instead, he re-enters them in a Google Sheet that finance reconciles by hand.
- **Current workaround , the external tool or manual process they rely on (M2):** The users skip filling in some info that then they  re-enter in a Google Sheet that finance reconciles by hand.
- **Problem Hook , your one-sentence framing of the business crisis (M1):** We must stop mid-market fleets from churning to leaner tools by removing the unnecessary steps that slow frontline operators' daily dispatch work.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** For frontline fleet operators, we will restore fast execution on core coordination tasks while keeping enterprise compliance out of sight because operational slowdown is driving daily users off the platform and putting core revenue at risk of churning to leaner tools.

## Read your data snapshots
- **Does the funnel data confirm your M2 friction point, or does it tell a different story? Note where the numbers align with the qualitative pain you found and where they diverge.:** _(not filled in)_
- **Do the retention patterns align with the workaround your M2 persona used to find content? Note what the Mo. 0→1 drop suggests about the onboarding experience your persona described as frustrating.:** _(not filled in)_
- **Does the LTV gap and the content mix (61% trending for Wanderers) confirm the moment of misery your persona described? Note which segment your persona is in and whether the data confirms their pain.:** _(not filled in)_
- **Does the low adoption confirm your persona is burdened by tools they don’t use? Note whether the low scheduling adoption (42%) for coordinators matches your M2 moment of misery.:** Partially. Among the core features, the Compliance Checklist has the lowest driver adoption (64%), which is exactly where my persona's friction sits. 

The other core features drivers need for their job, the Live Dispatch Board and Route Optimizer, have high adoption, and the 3 low-adoption features are secondary. 

So the way I read this is that problem isn't too many tools. It's too many clicks inside one core flow, which matches my M2 moment of misery (3 extra screens per field).
- **Does the workflow data match the manual process or hack you documented in M2? Note whether the specific drop-offs or time gaps explain why your persona avoids the digital tool.:** Yes, the main drop-off happens at the Compliance Checks steps, where users go from 71% to 48%. 

The workaround consists in the users entering compliance details in a Google Sheet that finance reconciles by hand, as they skip filling in some info in the app that is very time consuming. 

Here is where there is the biggest gap as well: 11.3 minutes with RouteLogic vs 3.0 minutes in best-in-class benchmarks to complete the compliance checks.
- **Look at the CSAT heatmap. Which specific cell most directly maps to your persona’s friction? Note how the NPS trend justifies the urgency of your M1 Problem Hook.:** Compliance (2.8). It ties directly to the friction the users experience when completing the Compliance Checks. 

Other indexes for Scheduling and Reporting are below 2, but those are not critical to the core workflow for driver persona for the close-out path.

These low scores contribute to a plunge of the NPS over the last two years, from +18 to 0.2

## Step 3 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** At end of shift, a dispatcher driver closing a large number of deliveries  skips the compliance checks (including cost and invoice fields) because each takes 3 extra screens. Instead, he re-enters them in a Google Sheet that finance reconciles by hand.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** Drop-off for compliance checks goes from 71% to 48%
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** Dispatch drivers
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** Drivers skip compliance and cost fields when closing deliveries at end of shift because each takes 3 extra screens, which pushes the data into a Google Sheet that finance reconciles by hand.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** Drivers logging compliance details in the app in a seamless and quick way. It maps to retention as a faster close-out will result in fewer abandoned records, no sheets workaround, lower finance reconciliation cost, users engaged. All the above will impact in customer retention.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** Percentage of closed deliveries with compliance checks completed in the app. Baseline 48% → target ~60–65%
Plus time to complete the compliance step: 11.3 → ≤5 min.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Compliance record accuracy: audit pass rate is equal or higher than current rate. We do not have such number in the exercise.

Completion time on core dispatch flows (Dispatch Board, Route Optimizer): Dispatch Board / Route Optimizer task time does not increase more than 5%
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** After 1 quarter: ≥60% completion and ≤5 min → scale; 52–60% → iterate; <52% or a drop in accuracy → kill/pivot.
Checkpoint half-way on week 6. If completion has not moved above 52%, revisit the full design of the workflow at this point and iterate.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on dispatchers re-entering skipped compliance and cost fields into a Google Sheet at end of shift, and a funnel drop from 71% to 48% at the compliance step (11.3 min vs. a 3.0 min benchmark), we believe that cutting the compliance close-out flow to a single screen for drivers  will raise in-app compliance completion from 48% to 60%+ and median completion time to ≤5 min. We will protect compliance record accuracy and core dispatch-flow speed, and make a go/no-go decision after one quarter (checkpoint at week 6).
