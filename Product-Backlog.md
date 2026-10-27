# Product Backlog

## What a Product Backlog Is
A Product Backlog is the prioritised list of everything a product needs: features, technical work, bug fixes and improvements. For SafeGuard Soshanguve, ours lives on Trello in the "Product Backlog" column, which holds 62 cards. From there, the team pulled stories into sprints.

## Product Vision
To make Soshanguve a safer community by giving residents an affordable, locally run security service backed by a mobile alert app for fast emergency response.

## Evidence: Trello Board
(Trello screenshot of the Product Backlog column goes here)

## Backlog Items

| # | User Story | Theme | Priority | Planned Sprint |
| --- | --- | --- | --- | --- |
| 1 | Set up Spring Boot project structure | Technical foundation | Must have | Sprint 1 |
| 2 | Design and implement database schema | Technical foundation | Must have | Sprint 1 |
| 3 | Register an account using a phone number | Resident account | Must have | Sprint 2 |
| 4 | Set up a home address by dropping a pin on the map | Resident account | Must have | Sprint 2 |
| 5 | Add up to 3 emergency contacts | Resident account | Should have | Sprint 2 |
| 6 | Register a guard profile with ID number and training certificate | Guard management | Must have | Sprint 3 |
| 7 | Receive an emergency alert notification with resident name and location | Emergency alerts | Must have | Sprint 3 |
| 8 | Press the SOS button to trigger an emergency alert | Emergency alerts | Must have | Sprint 4 |
| 9 | Hold down the SOS button to confirm and avoid accidental triggers | Emergency alerts | Must have | Sprint 4 |
| 10 | Share live GPS location during an alert | Emergency alerts | Must have | Sprint 4 |
| 11 | Receive a push notification when a guard accepts the alert | Alert updates | Should have | Sprint 5 |
| 12 | Receive a push notification when the guard is on route | Alert updates | Should have | Sprint 5 |
| 13 | Rate the guard's response after an incident is resolved | Feedback | Could have | Sprint 6 |
| 14 | View full personal alert history with dates, guards and outcomes | Feedback | Could have | Sprint 6 |
| 15 | Receive community safety broadcast alerts from admin | Community safety | Should have | Sprint 7 |
| 16 | View a map of recent crime hotspots in the township | Community safety | Should have | Sprint 7 |
| 17 | Log out of the app | Resident account | Should have | Sprint 7 |
| 18 | Navigate to the resident using in-app map routing | Guard response | Must have | Sprint 8 |
| 19 | Accept an incoming alert within the required response window, or decline if unavailable | Guard response | Must have | Sprint 8 |
| 20 | Upload ID for verification during registration | Guard management | Must have | Sprint 9 |
| 21 | Receive a notification when my profile is approved or rejected by admin | Guard management | Should have | Sprint 9 |
| 22 | View equipment checklist and confirm equipment issued | Guard management | Could have | Sprint 9 |
| 23 | Register and approve new security guard profiles | Admin tools | Must have | Sprint 10 |
| 24 | Assign guards to specific patrol zones on the map | Admin tools | Should have | Sprint 10 |
| 25 | Deactivate or suspend a guard | Admin tools | Should have | Sprint 10 |
| 26 | Approve or reject community incident reports before they go public | Admin tools | Should have | Sprint 11 |
| 27 | Post community safety announcements to residents in a specific area | Admin tools | Should have | Sprint 11 |
| 28 | Manage membership payments | Payments | Should have | Sprint 12 |
| 29 | Handle refunds or fee disputes | Payments | Could have | Sprint 12 |
| 30 | Manage guard equipment | Admin tools | Could have | Sprint 12 |

The Trello column holds 62 cards in total. The table above lists the main stories, and the rest are smaller technical and supporting cards.

## How We Prioritised
We ordered the backlog by how much each story supports SafeGuard's core promise: a fast response in an emergency. Stories that make the SOS alert work came first, because without them there is no product. Features like ratings, alert history and payments came later, because they improve the service but do not stop it from working. We used Must have, Should have and Could have to show this.

## Reflection

**What I did.** For SafeGuard Soshanguve, our team kept every feature, technical task and idea in one Product Backlog on Trello. By the time we finished planning, the column held 62 cards. We wrote most of them as user stories from the point of view of residents, security guards and admins, for example "Press the SOS button to trigger an emergency alert" and "Register a guard profile with ID number and training certificate". We then put the items in order so the most important work would be built first, and pulled them into sprints from the top of the list.

**What I expected versus what I found.** At the start, I thought a product backlog was simply a big to-do list. Once we had dozens of items, I understood that it is really a list of choices. Everything felt important, but we had a limited number of sprints and a limited team, so we could not build everything at once. The backlog forced us to decide what mattered most and what could wait.

**How we decided on priorities.** Our priorities came from the problem we were solving. Our research showed that residents in Soshanguve worry about crime and slow emergency response. Our customer persona, Andile, wants affordable and fast protection. So the SOS button, live location sharing and guard response went to the top, because without them SafeGuard is not a security product at all. Features like rating a guard, viewing alert history and handling refunds were useful but came later, because the service still works without them. I used Must have, Should have and Could have to make these decisions visible. This taught me that prioritising is not about what is most interesting to build, it is about what delivers the most value to the user.

**Why the order and the technical work matter.** Not every backlog item is a feature that a resident sees. Items like setting up the Spring Boot project structure and designing the database schema had to come first, because nothing else could be built without them. I learned that a good backlog includes this behind-the-scenes work too, and that some items must be done early because other items depend on them. For example, the guard push notifications could not be built before the SOS alert existed, and admin approval of guards could not be built before guards could register.

**How feedback changed the backlog.** Our lecturer's feedback pushed us to test our assumptions with the community instead of guessing, including whether residents would pay R100 to R200 a month. That showed me that a backlog is a living document. It should change as we learn more, and adding, removing or reordering items is a normal part of Agile, not a sign that the plan failed.

**What was difficult.** The hardest part was keeping 62 items clear. Some stories were too big and had to be broken into smaller ones, and a few cards were technical rather than user-focused, which made them awkward to write in the "As a user, I want..." format. It was also easy for similar stories to overlap, so we had to check the list regularly to avoid duplicates. Deciding which stories were truly Must have and which were only Should have also took discussion, because different team members cared about different features.

**How it connects to the rest of my portfolio.** The product backlog is built from our user stories, and our team charter set the rules for how we managed it, such as every task having an owner. From the backlog we chose items for the Sprint Backlog, where each sprint has its own goal, due dates and owners. Our Agile Logbook then records the stand-ups and retrospectives where we discussed how the work was going and what to change. Together these pieces show the full Agile process from idea to delivery.

**What I learned about myself and my skills.** This exercise improved my planning, my ability to think from the user's point of view, and my ability to make trade-offs. I also became more comfortable using Trello to organise a large project and to communicate with the team about who is doing what and when.

**What I would do differently.** Next time I would give every item an effort estimate from the start, so we could see how much work each sprint can really hold. I would review and re-prioritise the backlog with the whole team after every sprint so it never gets out of date. I would also involve real community members in ranking the features, since they know best what they need, and write acceptance criteria for each story so the whole team agrees on what "done" means.
