# Competitive Analysis & Journey Map

> **Module 2 · Lab 2 — ★ Deliverable 2.** Repo file `02-discovery/competitive-and-journey.md` — part of your submission.
> Do the lab in the **Module 2 · Exercise 2 Guide** (linked from the Module 2 deck), then click **⬇ Download .md** — it saves as this exact file. Commit it here.
> It becomes the **Competitive Analysis & Journey Map** slide of your Module 6 final deck. Builds on your `ai-synthesis.md` and your Module 1 `problem-hook.md`.

## Responses

- **Role, who are you solving for? (the specific user segment or profile):** Experienced delivery drivers who run long routes (40+ stops) on Android phones, using the app all day, every day.
- **Goal, what is this user ultimately trying to achieve?:** Finish every stop quickly and leave a delivery record they don't have to double-check, logging each delivery in the system with the information needed to complete the job.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** The core actions are slow and unreliable. "Mark delivered" takes three taps across three screens, and "Start Route" sits 2–3 menu levels deep even though it is used about 30 times a day. On top of that, proof-of-delivery photos fail silently on weak signal (~35% of the time), and routes over ~40 stops crash the app on Android 12/13, wiping the rest of the route.
- **External tools, the outside platforms or tools the user is forced to use:** SMS / WhatsApp messages to the dispatcher (the dispatcher's WhatsApp group is "the real system"), paper manifests, phone calls to the office, and screenshots of the stop list (rural routes, offline).
- **The process, the 3 to 5 manual steps the user takes to get the job done:**
  1. Before the shift, copy the stop list onto a paper manifest in case the app fails.
  2. At each stop, skip the three-screen "Mark delivered" flow and text or WhatsApp the dispatcher that the stop is done.
  3. Take the proof-of-delivery photo, get no confirmation, and retake it up to three times hoping one uploads.
  4. When the app crashes past ~40 stops, call the office and have someone read the remaining stops aloud (~20 minutes).
  5. Finish the rest of the route from the paper manifest and messages, outside the app.
- **Core frustration, the exact moment the process feels most “broken”:** The crash mid-route on a long route. In one moment the driver loses the rest of their stops, has to stop driving to phone the office, and spends the rest of the day working from paper. It hits the most experienced drivers hardest because they run the longest routes, and it teaches them the app can't be trusted.
- **The evidence, a specific quote or behavior from the research that proves this:** 5 of 7 focus-group drivers keep a paper manifest specifically in case the app fails. "Mark delivered" (three taps, three screens) is the top frontline complaint and has directly pushed drivers to text dispatchers instead. A dispatcher called the WhatsApp group "the real system." All seven focus-group drivers said core action speed matters more than any new feature.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** `02-discovery/journey-map.html` (4-stage future-state journey)
