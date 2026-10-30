# Sprint Backlog

## What a Sprint Backlog Is
A Sprint Backlog is the plan for one sprint. It takes items from the Product Backlog and lists the specific work the team commits to finishing in that sprint. For SafeGuard Soshanguve, we ran 16 sprints on Trello, with 78 cards in total. Each sprint is a column on our board, usually with 5 cards. Every card has a due date and an owner shown by their initials, and many have a checklist of smaller tasks. When a card is finished it moves into our "Sprint | Completed" column.

## Evidence: Trello Board
<img width="1275" height="432" alt="image" src="https://github.com/user-attachments/assets/afe2a6de-34af-4dc2-b147-cd03391201c4" />
<img width="1251" height="354" alt="image" src="https://github.com/user-attachments/assets/b4256118-bb99-42b1-aefb-ba491204a383" />

<img width="1274" height="433" alt="image" src="https://github.com/user-attachments/assets/463a6fea-8fc7-419a-a158-59d4297f86f5" />
<img width="1251" height="348" alt="image" src="https://github.com/user-attachments/assets/729eb3e8-ce25-4a43-b0c7-81472121445e" />

<img width="1277" height="454" alt="image" src="https://github.com/user-attachments/assets/3dbcd924-5ca4-4915-bc80-6bd7a3317c4a" />
<img width="1286" height="423" alt="image" src="https://github.com/user-attachments/assets/e6e4174a-8947-4adf-95ee-11407b0ed6cf" />

<img width="497" height="385" alt="image" src="https://github.com/user-attachments/assets/90920ade-9c76-4fda-87e6-a4716bafb33b" />
<img width="252" height="375" alt="image" src="https://github.com/user-attachments/assets/8bd7bdf2-82b5-4b24-ac8f-b4b60c8363d7" />
<img width="252" height="380" alt="image" src="https://github.com/user-attachments/assets/b78daf7b-f9bd-46b6-b93a-ba10fc6e9bc9" />
<img width="241" height="368" alt="image" src="https://github.com/user-attachments/assets/8da4a10b-1d2a-43b7-be6b-f0c1fb19ac77" />
<img width="246" height="374" alt="image" src="https://github.com/user-attachments/assets/f8acd67f-514d-4da0-b6c5-7fdc7b477bcc" />







## Sprint Overview

Owners are shown by their Trello initials.

### Sprint 1: Technical foundation
| Card | Due | Owner |
| --- | --- | --- |
| Set up Spring Boot project structure | Jul 20 | RM |
| Design and implement database schema | Jul 21 | TM |
| Set up JWT authentication and role-based authorization | Jul 21 | AM |
| Integrate FCM for push notifications | Jul 22 | N |
| Set up React project structure | Jul 23 | RM |
| Implement geolocation "nearest guard" query | Jul 24 | YM |

### Sprint 2: Resident registration and emergency contacts
| Card | Due | Owner |
| --- | --- | --- |
| Register an account using a phone number | Jul 27 | AM |
| Set up a home address by dropping a pin on the map | Jul 28 | RM |
| Add up to 3 emergency contacts | Jul 29 | N |
| Edit or remove emergency contacts at any time | Jul 30 | TM |
| Verify identity via OTP sent to phone | Jul 31 | YM |

### Sprint 3: Guard profiles and shift tracking
| Card | Due | Owner |
| --- | --- | --- |
| Register a guard profile with ID number and training certificate | Aug 3 | N |
| Log shift start by checking in on the app | Aug 4 | AM |
| Log shift end by checking out on the app | Aug 5 | TM |
| View assigned patrol zone on the map | Aug 6 | RM |
| Receive an emergency alert notification with resident name and location | Aug 7 | YM |

### Sprint 4: The core SOS feature
| Card | Due | Owner |
| --- | --- | --- |
| Press the SOS button to trigger an emergency alert | Aug 10 | N |
| Hold down the SOS button to confirm and avoid accidental triggers | Aug 11 | AM |
| Share live GPS location automatically when SOS is activated | Aug 12 | RM |
| View a live map showing the responding guard's location | Aug 13 | TM |
| See the guard's estimated time of arrival | Aug 14 | YM |

### Sprint 5: Keeping residents updated during an alert
| Card | Due | Owner |
| --- | --- | --- |
| Receive a push notification when a guard accepts the alert | Aug 17 | N |
| Receive a push notification when the guard is on route | Aug 18 | AM |
| Receive a push notification when the guard has arrived | Aug 19 | TM |
| Cancel a false alarm before the guard departs | Aug 20 | YM |
| View the full details of a resolved incident | Aug 21 | RM |

### Sprint 6: Feedback, history and community reporting
| Card | Due | Owner |
| --- | --- | --- |
| Rate the guard's response after an incident is resolved | Aug 24 | AM |
| View full personal alert history with dates, guards, and outcomes | Aug 25 | N |
| Report on suspicious activity in the area | Aug 26 | YM |
| Select an incident type | Aug 27 | RM |
| View a live community crime feed filtered by area | Aug 28 | TM |

### Sprint 7: Community safety and membership
| Card | Due | Owner |
| --- | --- | --- |
| Receive community safety broadcast alerts from admin | Aug 31 | RM |
| View a map of recent crime hotspots in the township | Sep 1 | AM |
| Log out of the app | Sep 2 | N |
| Set up payment method and pay monthly membership fee | Sep 3 | TM |
| View guard's name, photo, and PSIRA number once assigned | Sep 4 | YM |

### Sprint 8: Guard response tools
| Card | Due | Owner |
| --- | --- | --- |
| Navigate to the resident using in-app map routing | Sep 7 | RM |
| Accept an incoming alert within the required response window, decline an alert if unavailable | Sep 8 | AM |
| Update availability status (available, on break, off duty) | Sep 9 | TM |
| Add notes when resolving an incident | Sep 10 | YM |
| View personal response history and past incidents handled | Sep 11 | N |

### Sprint 9: Guard verification and equipment
| Card | Due | Owner |
| --- | --- | --- |
| Upload PSIRA certificate and ID for verification during registration | Sep 14 | RM |
| Receive notification when profile is approved/rejected by admin | Sep 15 | AM |
| View equipment checklist / confirm equipment issued | Sep 16 | N |
| Report an equipment issue or request replacement | Sep 17 | TM |
| Flag a safety concern about a specific alert (e.g. "needs backup") | Sep 18 | YM |

### Sprint 10: Admin control of guards and live monitoring
| Card | Due | Owner |
| --- | --- | --- |
| Register and approve new security guard profiles | Sep 21 | RM |
| Assign guards to specific patrol zones on the map | Sep 22 | AM |
| Deactivate or suspend a guard account | Sep 23 | N |
| View a live dashboard of all active alerts in real time | Sep 24 | TM |
| View live positions of all on-duty guards on the map | Sep 25 | YM |

### Sprint 11: Moderation, announcements and reports
| Card | Due | Owner |
| --- | --- | --- |
| Approve or reject community incident reports before they go public | Sep 28 | AM |
| Post community safety announcements to residents in a specific area | Sep 29 | RM |
| Generate monthly reports on incidents and response times | Sep 30 | N |
| View guard performance metrics and average response times | Oct 1 | YM |
| Configure patrol zone boundaries on the map | Oct 2 | TM |

### Sprint 12: Payments, equipment and emergency-wide alerts
| Card | Due | Owner |
| --- | --- | --- |
| Manage membership payments | Oct 5 | RM |
| Handle refunds or fee disputes | Oct 6 | AM |
| Manage guard equipment inventory | Oct 7 | N |
| Broadcast emergency-wide alert (not area-specific) | Oct 8 | TM |
| Review and resolve guard safety flags | Oct 9 | YM |

### Sprint 13: Payment gateway, live updates and security
| Card | Due | Owner |
| --- | --- | --- |
| Integrate payment gateway sandbox and webhook handling | Oct 12 | AM |
| Set up WebSocket channel for live alert status updates | Oct 13 | RM |
| Implement API rate limiting / abuse protection on SOS endpoint | Oct 14 | N |
| Write API documentation | Oct 15 | TM |
| Set up error logging/monitoring | Oct 16 | YM |

### Sprint 14: Testing, compliance and launch readiness
| Card | Due | Owner |
| --- | --- | --- |
| Write unit tests | Oct 19 | RM |
| Set up staging environment and deployment pipeline | Oct 20 | AM |
| POPIA compliance review | Oct 21 | N |
| Conduct security penetration testing before launch | Oct 22 | TM |
| Set up automated database backup and recovery plan | Oct 23 | YM |

### Sprint 15: Onboarding
| Card | Due | Owner |
| --- | --- | --- |
| Complete first-time app onboarding walkthrough | Oct 26 | YM, RM, AM |
| Complete in-app safety onboarding training module | Oct 27 | N, TM |

### Sprint 16: Reliability and release
| Card | Due | Owner |
| --- | --- | --- |
| Implement SMS fallback integration | Oct 28 | RM |
| Implement caching layer for guard location lookups | Oct 28 | AM |
| Set up mobile app crash reporting | Oct 29 | YM |
| Set up load testing for the SOS/alert endpoint | Oct 30 | TM |
| Set up app store deployment pipeline | Oct 30 | N |

## Reflection

**What I did.** For SafeGuard Soshanguve, our team planned the whole product into 16 sprints on Trello, with 78 cards between them. Each sprint was a column with about five cards, and every card had an owner and a due date. The due dates run roughly one per working day, from Sprint 1 on 20 July to Sprint 16 on 30 October. Many cards also had a checklist of smaller tasks. For example, "Register an account using a phone number" had 4 tasks and "Set up a home address by dropping a pin on the map" had 9. When a card was finished, it moved into our "Sprint | Completed" column.

**What I learned about choosing sprint work.** The product backlog holds everything we might build, but a sprint backlog is only the small amount we commit to in that sprint. With about five cards per sprint, we had to decide what really belonged in each one. I could see this thinking in the order of the board. Sprint 1 was all technical foundation: the Spring Boot project, the database, JWT authentication and role-based authorization, push notifications with FCM, the React project and the "nearest guard" location query. Nothing else could be built until those were in place.

**Why the sequence matters.** Each sprint builds on the one before. Residents can register and add emergency contacts in Sprint 2, and guards can register, check in for a shift and see their patrol zone in Sprint 3, so the SOS button in Sprint 4 has people to alert and guards to respond. After the alert exists, Sprint 4 adds live GPS sharing, a live map of the responding guard and the estimated arrival time, and Sprint 5 adds the push notifications for a guard accepting, being on route and arriving. Admin tools for approving and assigning guards come later, in Sprint 10, after guards can upload their PSIRA certificate in Sprint 9. Seeing this made me understand that sprint planning is about sequence and dependencies, not only about picking tasks.

**Trust and safety were planned in.** Several cards are about making the service safe and trustworthy for residents and guards. Residents verify their identity with an OTP in Sprint 2, they can cancel a false alarm in Sprint 5, and they can see their guard's name, photo and PSIRA number in Sprint 7. Guards flag safety concerns, such as "needs backup", in Sprint 9, and admins review those flags in Sprint 12. I learned that for a security product, trust and safety are features that need their own planned work.

**Quality and compliance had their own sprints.** The last sprints are about making the product safe to launch. Sprint 13 includes rate limiting on the SOS endpoint, error logging and API documentation. Sprint 14 includes unit tests, a staging environment, a POPIA compliance review, penetration testing and a database backup plan. Sprint 16 includes an SMS fallback, a caching layer for guard locations, crash reporting, load testing of the SOS endpoint and an app store deployment pipeline. SafeGuard handles people's names and locations during emergencies, so protecting that data and making sure the alert system works under pressure had to be planned work, not something added at the end.

**What was difficult.** Sprints were not all the same size. Sprint 1 had six cards, most sprints had five, and Sprint 15 had only two. Some cards were also much bigger than others, which made it hard to keep the workload balanced. A few cards were owned by more than one person, such as the onboarding walkthrough, and that needed coordination to make sure the work was shared fairly. Several cards also carried reminders or due-date warnings on Trello, which showed me how quickly a sprint can slip when one card is late.

**How it connects to the rest of my portfolio.** The sprint backlog draws from our product backlog and user stories. Our Agile Team Charter set the rule that every task has an owner, and every card on the board shows one. The Agile Logbook records the stand-ups where we reported on this work.

**What I would do differently.** Next time I would write a clear sprint goal at the start of every sprint and check it at the end. I would also plan sprints of a more even size by giving each card an effort estimate, so no one has a much heavier week than the others. I would hold a short review at the end of each sprint to see what we finished and what to change, and I would test with community members earlier, not mostly near the end. This process improved my planning, my teamwork and my ability to break a big product into small, deliverable pieces.
