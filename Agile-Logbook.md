

# Agile Logbook

## What an Agile Logbook Is
An Agile logbook is a record of what the team planned, what it completed and what is coming next. For SafeGuard Soshanguve, this logbook covers all 16 sprints, from 20 July to 30 October 2026. It is built from our Trello board, where every card has an owner and a due date, and each finished card sits in our "Sprint | Completed" column. Owners are shown by their Trello initials, and the dates are the due dates on the cards.

## Evidence: Trello Board

**Sprints 1 to 5 (the start of the project)**
<img width="1279" height="487" alt="image" src="https://github.com/user-attachments/assets/287e8f5f-fd93-4e3a-b0a4-bf5fbc09afe4" />


**Sprints 13 to 16 and the Sprint | Completed column (82 finished cards)**
<img width="1334" height="491" alt="image" src="https://github.com/user-attachments/assets/40ef87dd-7074-4df9-90cd-afa8a0ae4fcc" />

## How We Logged Our Work
At the start of each sprint we selected about five cards from the Product Backlog and gave each one an owner and a due date. At our stand-ups we answered the same three questions: what did I complete since the last stand-up, what am I planning to do next, and what is blocking me. Each entry below shows what the team completed in that sprint and what we planned next.

## Sprint Log

| Sprint | Dates | Completed | Planned next |
| --- | --- | --- | --- |
| Sprint 1 | 20 to 24 Jul | Set up Spring Boot project structure (RM), database schema (TM), JWT authentication and role-based authorization (AM), FCM push notifications (N), React project structure (RM), geolocation "nearest guard" query (YM) | Resident registration, emergency contacts and OTP verification |
| Sprint 2 | 27 to 31 Jul | Register an account using a phone number (AM), set up a home address by dropping a pin on the map (RM), add up to 3 emergency contacts (N), edit or remove emergency contacts (TM), verify identity via OTP (YM) | Guard profiles, shift check-in and check-out, and emergency alert notifications |
| Sprint 3 | 3 to 7 Aug | Register a guard profile (N), log shift start (AM), log shift end (TM), view assigned patrol zone (RM), receive an emergency alert notification with resident name and location (YM) | The SOS button and live location sharing |
| Sprint 4 | 10 to 14 Aug | Press the SOS button (N), hold down the SOS button to confirm (AM), share live GPS location when SOS is activated (RM), live map of the responding guard (TM), estimated time of arrival (YM) | Push notifications during an alert, false alarm cancellation and incident details |
| Sprint 5 | 17 to 21 Aug | Push notification when a guard accepts the alert (N), is on route (AM) and has arrived (TM), cancel a false alarm (YM), view full details of a resolved incident (RM) | Guard ratings, alert history and community reporting |
| Sprint 6 | 24 to 28 Aug | Rate the guard's response (AM), view full personal alert history (N), report suspicious activity (YM), select an incident type (RM), live community crime feed filtered by area (TM) | Community safety alerts, crime hotspots map and membership payments |
| Sprint 7 | 31 Aug to 4 Sep | Community safety broadcast alerts from admin (RM), crime hotspots map (AM), log out of the app (N), set up payment method and pay membership fee (TM), view guard's name, photo and PSIRA number (YM) | Guard response tools: routing, accepting alerts, availability status |
| Sprint 8 | 7 to 11 Sep | In-app map routing to the resident (RM), accept or decline an incoming alert (AM), update availability status (TM), add notes when resolving an incident (YM), personal response history (N) | Guard PSIRA verification and equipment |
| Sprint 9 | 14 to 18 Sep | Upload PSIRA certificate and ID (RM), profile approved/rejected notification (AM), equipment checklist (N), report an equipment issue (TM), flag a safety concern about an alert (YM) | Admin tools for guards and live monitoring |
| Sprint 10 | 21 to 25 Sep | Register and approve guard profiles (RM), assign guards to patrol zones (AM), deactivate or suspend a guard (N), live dashboard of active alerts (TM), live positions of on-duty guards (YM) | Moderation, announcements and reports |
| Sprint 11 | 28 Sep to 2 Oct | Approve or reject community incident reports (AM), post community safety announcements (RM), monthly reports on incidents and response times (N), guard performance metrics (YM), configure patrol zone boundaries (TM) | Payments, equipment inventory and emergency-wide alerts |
| Sprint 12 | 5 to 9 Oct | Manage membership payments (RM), handle refunds or fee disputes (AM), manage guard equipment inventory (N), broadcast emergency-wide alert (TM), review and resolve guard safety flags (YM) | Payment gateway, live updates and security hardening |
| Sprint 13 | 12 to 16 Oct | Payment gateway sandbox and webhooks (AM), WebSocket channel for live alert status (RM), API rate limiting on the SOS endpoint (N), API documentation (TM), error logging and monitoring (YM) | Testing, compliance and launch readiness |
| Sprint 14 | 19 to 23 Oct | Unit tests (RM), staging environment and deployment pipeline (AM), POPIA compliance review (N), security penetration testing (TM), automated database backup and recovery plan (YM) | App onboarding and training |
| Sprint 15 | 26 to 27 Oct | First-time app onboarding walkthrough (YM, RM, AM), in-app safety onboarding training module (N, TM) | SMS fallback, caching, crash reporting, load testing and app store deployment |
| Sprint 16 | 28 to 30 Oct | SMS fallback integration (RM), caching layer for guard location lookups (AM), mobile app crash reporting (YM), load testing for the SOS/alert endpoint (TM), app store deployment pipeline (N) | The project is complete and ready for release |

## Reflection

**What I did.** For SafeGuard Soshanguve, our team kept a record of our work over 16 sprints, from 20 July to 30 October. Every sprint had about five cards, and every card had an owner and a due date, so the board works as a day-by-day log of what was planned and what was finished. When a card was done it moved into our Sprint | Completed column. This logbook turns that record into an entry for each sprint: what we completed, and what we planned to do next.

**What I learned about keeping a log.** A logbook makes progress visible. When I read my log from the start, I can see the product grow in a clear order. We began with the technical foundation in Sprint 1, then let residents register and set up their emergency contacts in Sprint 2. Guards joined in Sprint 3, and in Sprint 4 the SOS button brought everything together. After that, each sprint added a layer: updates during an alert, history and ratings, community safety features, guard tools, admin tools, payments, security and testing. Reading the "Planned next" column against the next entry's "Completed" column showed me that we did what we planned, which gave the team a sense of progress and kept us accountable.

**What I learned about planning in small steps.** Because each sprint was about five cards, the work always felt manageable. A product with more than 60 features could have felt overwhelming, but a week at a time it was clear what mattered now. The log also showed me why the order matters: the SOS button in Sprint 4 needed residents (Sprint 2) and guards (Sprint 3) first, and the admin tools for approving guards in Sprint 10 needed guards to upload their certificates in Sprint 9.

**How the log shows teamwork.** The initials next to every card show that the work was shared across the whole team. The log also shows that some cards had more than one owner, such as the onboarding walkthrough in Sprint 15, which was shared between three people. This reminded me that a logbook is not only about tracking tasks, it is also about showing who is responsible for what, so no one is unsure and no one carries the whole project.

**Quality, security and launch.** The later entries show a shift from building features to making the product safe and ready. Sprint 13 added rate limiting and error logging, Sprint 14 added unit tests, a POPIA compliance review and penetration testing, and Sprint 16 added load testing, crash reporting and the app store deployment pipeline. I learned that finishing a product means testing it, protecting people's data and preparing it for release, and that these tasks need their own place in the plan.

**What was difficult.** Our sprints were not all the same size. Sprint 1 had six cards and Sprint 15 only two, and some cards were much bigger than others. Keeping the log honest was also a challenge, because it only helps if the record matches what really happened and is updated as we go, not written afterwards. I also noticed that a table of cards shows what was done, but not why a decision was made or what went wrong along the way.

**How it connects to the rest of my portfolio.** The logbook records the work that comes out of the other four pieces. Our Agile Team Charter set the rules for how we worked, including that every task has an owner. The user stories and Product Backlog describe what we built, and the Sprint Backlog shows the cards we chose for each sprint. The logbook is where those pieces come together as a timeline of what we actually finished.

**What I would do differently.** Next time I would add a short retrospective at the end of every sprint to record what went well, what did not, and what to change. I would also note blockers and decisions in the log as they happen, so the record shows the problems we solved and not only the cards we finished. And I would write a clear sprint goal at the start of each sprint and check it at the end. This work improved my organisation, my communication with the team, and my ability to track a large project from the first day to the last.
