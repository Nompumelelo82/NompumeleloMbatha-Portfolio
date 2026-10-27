# Sprint Backlog

## What a Sprint Backlog Is
A Sprint Backlog is the plan for one sprint. It takes stories from the Product Backlog and lists the specific work the team commits to finishing in that sprint to reach the sprint goal. Our SafeGuard Soshanguve project ran across 13 sprints on Trello. Each sprint had about 5 cards, and each card had a due date, an owner and a checklist of tasks.

## Evidence: Trello Board
(Trello screenshots go here)

## Sprint Overview

| Sprint | Sprint Goal | Selected Stories | Due | Owner |
| --- | --- | --- | --- | --- |
| Sprint 1 | Set up the technical foundation | Set up Spring Boot project structure | Jul 20 | RM |
| | | Design and implement database schema | Jul 21 | TM |
| Sprint 2 | Let residents register and set up their location | Register an account using a phone number | Jul 27 | AM |
| | | Set up a home address by dropping a pin on the map | Jul 28 | RM |
| Sprint 3 | Get alerts and guard profiles working | Register a guard profile with ID number and training certificate | Aug 3 | N |
| | | Receive an emergency alert notification with resident name and location | Aug 7 | YM |
| Sprint 4 | Build the core SOS feature | Press the SOS button to trigger an emergency alert | Aug 10 | N |
| | | Hold down the SOS button to confirm and avoid accidental triggers | Aug 11 | AM |
| Sprint 5 | Keep residents updated during an alert | Receive a push notification when a guard accepts the alert | Aug 17 | N |
| | | Receive a push notification when the guard is on route | Aug 18 | AM |
| Sprint 6 | Close the loop after an incident | Rate the guard's response after an incident is resolved | Aug 24 | AM |
| | | View full personal alert history with dates, guards, and outcomes | Aug 25 | N |
| Sprint 7 | Keep the community informed | Receive community safety broadcast alerts from admin | Aug 31 | RM |
| | | View a map of recent crime hotspots in the township | Sep 1 | AM |
| Sprint 8 | Help guards respond | Navigate to the resident using in-app map routing | Sep 7 | RM |
| | | Accept an incoming alert within the required response window, decline if unavailable | Sep 8 | AM |
| Sprint 9 | Verify and approve guards | Receive notification when profile is approved/rejected by admin | Sep 15 | AM |
| Sprint 10 | Give admins control of guards | Register and approve new security guard profiles | Sep 21 | RM |
| | | Assign guards to specific patrol zones on the map | Sep 22 | AM |
| Sprint 11 | Moderate and announce | Approve or reject community incident reports before they go public | Sep 28 | AM |
| | | Post community safety announcements to residents in a specific area | Sep 29 | RM |
| Sprint 12 | Manage payments and equipment | Manage membership payments | Oct 5 | RM |
| | | Handle refunds or fee disputes | Oct 6 | AM |

## Reflection

**What I did.** For SafeGuard, our team took stories from the Product Backlog and planned them into 13 sprints on Trello. Each sprint had about five cards. Every card had a due date, an owner, and a checklist of tasks, so we could see what each person was responsible for and when it was due.

**What I learned.** A sprint backlog is different from a product backlog. The product backlog is the long list of everything we might build, and ours had 62 cards. The sprint backlog is the small piece we commit to finishing right now. Choosing only a few stories per sprint forced us to decide what mattered first. We started with the project setup and the database in Sprint 1, because nothing else could be built without them. After that, registration and the SOS button came next, because they are the heart of SafeGuard.

**Why the order mattered.** Each sprint built on the one before it. We could not send push notifications about a guard being on route (Sprint 5) before we had the SOS alert (Sprint 4), and we could not build admin approval of guards (Sprint 10) before guards could register (Sprint 3). Seeing these dependencies made me understand why sprint planning is about sequence, not only about picking tasks.

**What was difficult.** Estimating how much fits in one sprint was hard. Some cards were small, but others, like setting up a home address by dropping a pin on the map, had much longer checklists. Cards with long checklists took more effort, and that made it harder to keep sprints balanced.

**How it connects to the rest of my portfolio.** The sprint backlog comes from our user stories and product backlog. Our Agile Logbook records the stand-ups and retrospectives where we discussed how each sprint went, and our team charter set the rules we followed, such as every task having an owner.

**What I would do differently.** Next time I would write a clear sprint goal at the start of each sprint and review it at the end, so the whole team agrees on what success looks like. I would also plan smaller, more evenly sized cards so no one carries a much heavier sprint than the others.
