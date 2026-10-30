# User Stories and Tasks

## Project
SafeGuard Soshanguve: a community security service with local guards and a mobile alert app for residents of Soshanguve.

## Who We Wrote the Stories For
Our main user is based on our customer persona, Andile Gomo. He is 35, works hard on a limited income, relies on public transport, and worries about crime at home and in the community. He wants affordable security (R100 to R200 a month) and a fast response in an emergency.

## How We Wrote Them
Every item on our Trello board is a user story. We wrote each one in the format "As a [type of user], I want [a feature] so that [the benefit]", and put it in the description of the card. We then broke each story into a checklist of smaller tasks, so the work could be shared, ticked off and finished within a sprint. Each card also has an owner and a due date, and it moves to Completed once every task on its checklist is done.

## User Stories
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/33592a36-7a4a-45f5-8873-7e061e252ad5" />



<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/4d32a414-1f0d-4e17-9cea-e05e2ae4b9a0" />


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/0dc83350-993a-4f77-af6d-0f21068d63d2" />

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9e765226-1391-4d3e-931f-dd2aa5def144" />


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/812ba581-3e84-489c-8067-e7b17404b3e4" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a095dcfc-c5d9-4f55-b4d3-cc4faf0749ca" />


<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/18b4bdcb-32b6-46f9-9831-0d6e4415e726" />

## User Stories and Tasks

### Story 1: Register an account using a phone number
Sprint 2 | Due: Jul 27 | Owner: AM | Status: Complete (4/4 tasks)

**User story:** As a resident, I want to register using my phone number so that I can create an account.

**Tasks:**
- Design the registration screen
- Create the registration form
- Validate phone number format
- Validate required fields

### Story 2: Set up a home address by dropping a pin on the map
Sprint 2 | Due: Jul 28 | Owner: RM | Status: Complete (9/9 tasks)

**User story:** As a resident, I want to set my home address by dropping a pin on the map so that emergency services can locate me accurately.

**Tasks:**
- Design the "Set Home Address" screen
- Integrate Google Maps/OpenStreetMap
- Display the user's current location
- Enable dropping a pin on the map

### Story 3: Add up to 3 emergency contacts
Sprint 2 | Due: Jul 29 | Owner: N | Status: Complete (4/4 tasks)

**User story:** As a resident, I want to add up to three emergency contacts so that they can be notified in case of an emergency.

**Tasks:**
- Design the Emergency Contacts screen
- Create a form to add up to three emergency contacts
- Validate and save the emergency contacts to the database
- Test adding, editing, and deleting emergency contacts

### Story 4: Edit or remove emergency contacts at any time
Sprint 2 | Due: Jul 30 | Owner: TM | Status: Complete (4/4 tasks)

**User story:** As a resident, I want to edit or remove my emergency contacts at any time so that my contact information remains up to date.

**Tasks:**
- Design the Edit Emergency Contact screen
- Allow users to edit existing emergency contacts
- Allow users to remove emergency contacts
- Test editing and deleting emergency contacts

### Story 5: Verify identity via OTP sent to phone
Sprint 2 | Due: Jul 31 | Owner: YM | Status: Complete (4/4 tasks)

**User story:** As a resident, I want to verify my identity via an OTP sent to my phone so that my account is secure.

**Tasks:**
- Generate and send an OTP to the user's phone number
- Allow the user to enter the OTP
- Verify the OTP and activate the account if valid
- Test OTP verification and handle invalid or expired OTPs

## Reflection

**What I did.** For SafeGuard Soshanguve, our team wrote our features as user stories on Trello. Each story is in the format "As a resident, I want... so that...", and each one has a checklist of tasks. The five stories on this page all come from Sprint 2, which is where a resident first gets into the system: registering with a phone number, setting a home address on the map, adding up to three emergency contacts, editing or removing those contacts, and verifying their identity with an OTP sent to their phone. All five were finished, with every task on every checklist ticked off.

**What I learned about writing stories.** The "so that" part of each story is the most useful part. It forces the team to explain why a feature exists, not just what it does. Registration exists "so that I can create an account", the home address exists "so that emergency services can locate me accurately", emergency contacts exist "so that they can be notified in case of an emergency", and the OTP exists "so that my account is secure". Because the reason is written next to the feature, anyone on the team can understand why the work matters, and it helps to judge whether the work is done properly. Writing everything from the resident's point of view also kept us focused on the people we are building for in Soshanguve, not only on the technology.

**How the stories fit together.** These five stories form one journey. A resident registers with their phone number, verifies it with an OTP, tells us where they live, and sets up the contacts who will be told if they trigger an alert. Seeing them side by side showed me that user stories are small pieces of a larger experience, and that the order in which we build them matters. The SOS alert in a later sprint depends on a resident having an account, a home address and emergency contacts first. The home address story makes this very clear, because without an accurate location, an alert is much less useful to a guard trying to reach someone.

**What I learned about breaking stories into tasks.** A story like "verify identity via OTP" is too big to start on, but its tasks are clear: generate and send an OTP, let the user enter it, verify it and activate the account, then test it, including invalid and expired codes. The map story is the biggest one on our board, with nine tasks. It starts with designing the screen, then integrating a map service, showing the user's current location and letting them drop a pin. The checklists often follow the same pattern: design the screen, build the feature, save or validate the data, then test. That showed me that a story is not finished when the feature is built, but when it has been tested, and that thinking about edge cases like expired OTPs belongs in the plan from the start. It also showed me that a larger story needs a longer checklist, and that a very long checklist is a sign a story might need to be split.

**What was difficult.** Our checklists are not all consistent. Several of our stories end with a test task, but the registration story ends with validating required fields and has no test task. That made it harder to be sure the story was really finished, and I learned that every story should have a task for testing so that "done" means the same thing for the whole team. Some of our stories also overlap. The last task of "Add up to 3 emergency contacts" is to test adding, editing and deleting contacts, but editing and deleting are also the subject of the next story. That made it unclear where one story ends and another begins. Stories should be small and independent, and each task should belong to one story only.

**How it connects to the rest of my portfolio.** These stories are the starting point of our Agile process. They are the cards in our Product Backlog, where they are ordered by importance. We chose them for Sprint 2 in our Sprint Backlog, where each one has an owner and a due date. Our Agile Team Charter set the rule that every task has an owner, and you can see that on each card. The Agile Logbook records the stand-ups where we reported on this work.

**What I would do differently.** Next time I would add acceptance criteria to every story, such as "an OTP expires after a set number of minutes", so the whole team agrees on what "done" means before we start. I would make sure every checklist includes a testing task, and I would check each new story against the existing ones to avoid overlap. I would also ask community members to read our stories to confirm that we have understood their needs. This work improved my ability to think from the user's point of view and to split a big feature into small, testable steps.
