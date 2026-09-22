## Module Two Team Project Plan

📋 **[View the QA & Testing Report (TESTING.md)](TESTING.md)**

### Project Setup
* **Scenario:** Unannounced Third-Person Game
* **Theme:** Fantasy
* **Core Elements:** Boss Enemy (Robert), x2 Stationary Enemies (Julie), x2 Moving Enemies (Steve), x4 Stationary Obstacles (Chris)
* **Extra Elements:** Health pickup (Chris), Jump pickup (Robert), Weapons (Drew)

### Brainstorming & Gameplay Overview
* **Theme & Setting:** A linear fantasy RPG set within ancient ruins where the player must defeat a warlord threatening local villages.
* **Level Design & Progression:** The game consists of 5 distinct rooms. Rooms 1 and 2 introduce jumping puzzles and stationary turrets. Room 3 introduces moving AI enemies and a hidden key. Room 4 requires the key to unlock the door. Room 5 contains the final Boss Enemy arena.
* **Combat Mechanics:** The player utilizes a sword weapon and can collect a jump pickup to gain extra vertical mobility for dodging hazards.

### Project Schedule & Milestones
* **Module 4 — Alpha Stage:** Focuses on foundational player movement and environment layout.
    * *Tasks:* Player Movement (Robert), Jump Pickup (Robert), Landscape Creation (Chris), Room Creation (Chris/Steve), Stationary Enemies/Turrets (Julie), and Obstacles (Julie).
* **Module 5 — Beta Stage:** Focuses on core gameplay progression and AI logic.
    * *Tasks:* Moving Enemies (Chris), Boss Enemy (Drew), Health Pickup (Chris), Key/Award Items (Drew), and Main Menu UI (Robert).
* **Module 7 — Final Submission:** Focuses on combat systems integration and polish.
    * *Tasks:* Health/Damage (Drew) and Projectiles (Chris).

### Communication & Task Tracking
* **Preferred Methods:** Discord is used for daily communication, with weekly meetings at 4:00 PM EST and optional midweek check-ins.
* **Task Reporting:** An Excel spreadsheet tracks individual assignments, completion statuses, and active bug logs to monitor project velocity.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Module Three Project Log - Team Development: QA and Testing Plan

### Testing Plan & Schedule 
* **How We Test:** Each team member will check functionality before and after adding new mechanics/features.
   * **Week 3:** Each member play tests their tasks. Daily testing occurs by at least one person and presents findings in the testing page of the Excel sheet. 
   * **Week 4:** Play testing the interactions of each addition to the project. All members will perform individual testing to ensure functionality of the combined features.
   * **Week 5:** Demo testing will be conducted individually throughout the week in addition to one final group demo at the Saturday team meeting. 
   * **Week 6:** Code Release testing is going to be our major testing time in which every member will be present and conducting in-depth testing of all functionality. Complex tests will allow us to flesh out major or game-breaking bugs prior to the final release of our game. This is also when final polishing of the game will take place in preparation of the final release.
   * **Where:** Testing and bugs are reported in the shared Excel sheet with detailed breakdowns. Everything in the Excel sheet is ongoing and changes daily/weekly with each added feature or idea. Every Saturday is when we hold our meetings and will use this time to address testing issues or concerns. 

 ### Managing Tests
* **What Will Be Tested:** Testing consists of checking functionality for each task listed in the Excel sheet. Tasks include- Player Movement, Player Pickups, Room Creations, Landscape Creations, Moving Enemies, Stationary Enemies, Boss Enemy, Stationary Obstacles, Keys/Award Items, Main Menu, Health/Damage, Projectiles, and Stamina. (Ongoing list; More to be added)
* **How We Update the Test Plan:** Everyone has access to the Excel sheet where we report the tests, note the bugs, give a brief description, and remark the plan toward debugging/fixing the bug. This keeps each team member up to date on the health of the project in between team meetings. At team meetings, we have a debrief on major bugs encountered and plan accordingly. 

### Bug Management
* **How We Report Bugs:** As stated previously, our team is highly dependent on the Excel sheet as well as our daily communication through the group Discord. Combined, we are in constant communication regarding bugs. 
* **How We Track Bugs:** We track the bugs in the Excel sheet so everyone can remain aware of bugs encountered and how they were fixed. Most team members will handle the bugs they encounter and any major bugs will be addressed to the team at the weekly team meetings if help is needed. The Excel sheet has dedicated columns so that detail is ensured. 

### Overall Meeting Takeaways
**How the meeting went, questions we still have, and how we feel about the project thus far:**
* Drew, Robert, Chris, Steve, and Julie were all present at the Saturday meeting. During the group meeting we brainstormed ideas and came to a consensus on timelines, testing plans, and reporting plans. All members contributed. Every Saturday is the assigned team meeting with occasional meetings on Wednesdays.
* Robert- "Conflicts in merging are painful"
* Julie- "The team communication is on point and every team meeting is productive and improves the progress of our project"
* Drew- "I'm feeling confident and it seems like we are all on top of it. I can't wait to see how this project comes together in the end"
* Steve- "This team is kicking butt. We communicate exceptionally well and all work great as a team"
* Chris- "This team is great and I look forward to staying in touch even after the project is completed"
* Overall the team is in great shape and maintains a collaborative and helpful environment for everyone. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Module Four Project Log - Team Development: Team Reflection

### What Went Well
1. Room Testing: Having team members test the room functionality and experience it for the first time was fun and went great.
2. GitHub Problem-shooting: We ran into issues in Git that required trial and error to fix. We did well testing and backtracking on problems. 
3. Debugigng: The team has encountered minimal bugs which, in turn, created a smooth debugging process. All bugs so far have been easily fixed.
4. Communication: Team communication on bugs and problems has been free flowing and kept up to date. Also, the Excel sheet has been maintained and updated accordingly.

### Bug Identificaiton and Correction Process
* Bugs were found both during creation of new features as well as through testing pre-existing features.
* Experiencing compile errors that required attention before proceeding forced us to diagnose bugs as they occurred.
* A specific example is with the character health which was noticed by two team members during the integration of damage types. This was presented to the team which the bug was diagnosed and corrected, resulting in the correction of the damage types as well. 

### How We Would Improve the Process
* Assigning specific individuals to testing that way there is distinction between desgin and testing. This would also allow the team to have a streamlined way of resolving bugs. The testers could present their findings and pass that along to the design team who would revisit the bug and solve the issue.
* Designating specific testing times could also help us improve the overall project flow. If Wednesdays were testing days, this would give the team enough time to diagnose problems and implement fixes before the end of the week.

### Successful Tools for Alpha Development
* Discord: As our main (and only) form of communication, we would be in shambles without it. Having a solid communication tool such as Discord, we are always in contact. 
* Temp Main Branch: This technique was used to create a temporary main branch to test merges. Rather than ruin our main branch, we were able test merges on the temp branch; mitigating major issues.
* Polycutting Tool/Union Tool (in UE5): Within Unreal, this tool has been astronomically useful to several team members in terms of modeling and editing buildings/rooms.
* Excel Sheet: Using Excel as a resource and middle ground to better document tasks and bugs saved us the headache of miscommunication or misunderstandings. Helped maintain organization and let everyone know what tasks are completed or still in process.

### Unsuccessful Tools for Development 
* Extruding (in UE5): Within Unreal, the extruding tool/technique caused problems with the room creation and contributed to bugs.
* Cloud Storage: We ran into a problem with storage and had to find an alternative solution to proceed with the creation of the project.

### Team Approach 
* We held team talks to decide on what methods or techniques would work best.
* Deciding on tools such as Discord and Excel Sheets contributed to our overall team approach. Our team had an initial drive for clear communication and organization which is what led to the decision to use such tools.
* Using the temporary main branch was a direct result of early problems encountered with the main branch. The decision was made to prevent further issues since the design document and project require the use of Git. 

### Overall Team Takeaways
**Additional thoughts and last minute comments:**
* One takeaway from this meeting is that we are assigning Chris as the one responisble for the creation and commit of the Final Alpha branch so that there is no confusion or mishaps.
* We also have acknowledged some current bugs and frustrations such as animations in general and the angle of the damage projectile from the turret.
* Members present at the meeting are Chris, Robert, Steve, and Julie. Drew was consulted afterward for his input due to being unable to make the meeting.
* Julie- "I still feel confident about our project. Projectiles get weird sometimes"
* Robert- "The jumping puzzle is hard"
* Steve- "Free-roaming/shooting enemies are a pain to blueprint"
* Chris- No Comment
* Drew- No Comment

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Module Five Project Log - Team Reflection

### What Went Well
* Boss Integration: Implementing the boss went smoothly and there were no hiccups during that process.
* Moving Enemies: Putting those enemies into the project has gone well with minimal issues encountered.
* Deadlines: Did a good job getting everything ready and submitted on time. Assigning one person to handle the branch submission for Alpha kept us on track.
* Melee: This feature has gone well in terms of adding it to the character and is fun to use in actual gameplay.

### What Went Wrong
* GitHub: Our team has been experiencing a tremendous setback with Git for one team member which has been a pain to navigate.
* Door BP: The first time trying to add this was glitchy and not quite working as intended. The second attempt is when it really came together.
* Damage Turret: Reworking the damage turret mesh caused some issues with the projectiles that had to be addressed and fixed.

### Previous Integrations 
* Referencing the README file: Looking back at the README file for guidance on helpful tools and techniques helped with current work on the project.
* Review the Excel File: We all refer back to our Excel file to stay up to date and on task. Each integration that we add at the end of the week is beneficial to the future of our project's development. 

### What Would We Do Differently
* Managing the Git: Taking more care in the beginning to get a solid grasp on Git and manage the project repository better. We've run into several issues with Git throughout this course which could have possibly been avoided if we were more comfortable working with Git.
* Nothing Else: We have had seemless collaboration and communication throughout the team and the entire project. There really is not anything we can think of that we would do differently in the collaborative process. 

### Tools and Techniques: Not Useful
* Again, Git: It feels like there is a lack in troubleshooting guides to help us manage the problems we are encountering. The resources provided in the course are not enough for the scenarios we are facing. 

### Identify Completed Stage
* Adding in Turrets: Putting the turrets in the final level and getting them set up is something we are working on so that the project is Beta ready.
* Obstacles: Implementing the stationary obstacles so that the gameplay feels more natural and provides cover from the turrets.
* Menu Setup: We still need to link the main menu so that it opens the correct level.
* Third-person Mesh: Before Beta release we need to update the third-person mesh to match the theme of our game.

### Overall Team Takeaways
**Additional thoughts and last minute comments:** 
* All members of the team (Drew, Robert, Steve, Chris, and Julie) were all present at the designated meeting time and contributed to the team log activity.
* Chris: "The process is a lot smoother than I expected. The way we all mesh and work together flows smoothly and there is no headbutting"
* Robert: "I think a kick will be the next attack animation"
* Steve: "I enjoy working with Git Bash (with immense sarcasm)"
* Julie: "Despite encountering some personal setbacks, we all take care of each other and support each other where we can"
* Drew: "We are on track and I think it will be a good final release next week"

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Module Six Project Log - Team Reflection

### What Went Well
* Conflict Resolution: The team resolved issue with Github and got everyone back on the same page for project development.
* Communication: Our team effectively communicated throughout every part of development which also helped us solve encountered issues.
* Deliverables: We met our targets and integrated the features and assets that we set out to include within the project.
* Resources: Utilizing the module resources went well for us and was perceived to be very helpful to the team.

### What Went Wrong
* Enemy Runtime Error: One of the enemy characters is producing a runtime error that still needs to be solved. 

### Integration of Previous Evaluations
* Our team has made steady progress since the last evaluation and is on the right track.
* Since last week, the Github issues that we kept running into have been fixed.
* We have maintained our workflow and keep progressing as we have the past several weeks. 

### What Would We Do Different
* Different Game Engine: There has been interest expressed in the team about trying a different game engine to gain new experience and expand skillsets.
* Modeling Software: Using a modeling software would've added a lot more freedom to the development and artistry of our game.
   * **Unhelpful Tools/Techniques:**
   * Troubleshooting Github: There was little to no troubleshooting help when we encountered issues with Github. The resources felt limiting and caused setbacks.
 
### Overall Team Takeaways
**Additional thoughts and last minute comments:** 
* All members of the team were present and contributed to the completion of this team log.
* Drew: "I wish our game project was due in week 7 with the postmortem in week 8. It would give us more time to polish and develop the game."
* Robert: "We still need a respawn animation."
* Julie: "I will be trying to fill out the level with structures and obstacles so that map feels more intentional."
* We need a finish to the game which is still in development. The thought is to implement the ghosts of your fallen friends (part of the lore) that will rise up and finally be freed. 

**This week's log was done ahead of schedule due to Julie not being available for the rest of the week.**
