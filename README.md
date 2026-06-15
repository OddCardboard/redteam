Nathen Reed- Team Lead, Programmer
Hunter Eck- Team Lead, Artist
Cedrick Lee- UI/UX, 
William Meredith- Programmer (primarily)


Module 2 Assignment
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2-2 Project Log: Team Formation and Project Design

Chosen Scenario
As a team, we decided to go with scenario choice: 2D Side-Scroller Platformer. We wanted to design a platformer focused around a rabbit-themed character navigating through hazardous zones filled with predators, traps, collectibles, and platforming obstacles. The rabbit must make their way from the level start to the level end while avoiding damage, collecting power-ups and rewards, and surviving enemies in their path.

Additional Items Selected
For player pickups, our group chose collectible power-ups. We settled on having three power-ups: a Health Boost to recover health or provide the player with an extra hit, an Invincibility Power-Up that grants the rabbit temporary immunity from damage, and a Projectile Power-Up that allows the rabbit to attack at range.
We also decided to include coins or rings spread throughout the level. These will encourage players to further explore the environment and attempt more dangerous platforming sections to collect them all.
For moving enemies, we discussed including different predator animals that match the rabbit theme. Examples include red foxes, wild cats, and possibly robotic variations of predator animals, depending on the overall look of the game. Enemies will roam around the level, patrol certain paths, or guard areas near challenging jumps and obstacles.
We also decided on spikes, pools of lava or acid, and springs/bounce traps as stationary hazards. These will challenge players during platforming sections and require precise timing of movements.

Additional Brainstorming and Game Design Concepts
Some ideas brought up by the team focused on gameplay and art style. We decided we wanted the game to have a vibe similar to Mario. Gameplay will consist of player movement, timing, exploration, and obstacle avoidance while progressing through the level.
The level design will follow a straightforward point A to point B structure. The player starts at one end of the map and reaches the goal at the other end. The level will begin easy and gradually increase in difficulty by introducing more challenging jumps, enemies, and hazard placements.

Development Schedule and Timeline
Module 3:
During Module 3, we will begin developing our game. We will create our player movement and jumping system, basic level design, collision and camera systems, start and finish areas, placeholder assets, and test basic gameplay elements.
Alpha Stage (Module 4):
Module 4 will be our Alpha stage build deadline. By this point, we want the game to be fully playable from start to finish. The alpha version should include functioning player movement, collectibles/pickups, enemies, and hazards.
Beta Stage (Module 5):
Module 5 will be our Beta stage submission. At this stage, both visual quality (mainly textures) and gameplay should be refined, with improved balance in overall structure and player experience.
Final Stage (Module 6):
Module 6 will complete final testing. At this point, we will fix any remaining bugs, finalize visual assets, and review repository documentation while preparing for submission.

Communication Methods
Our team is comfortable using Discord, so we decided to continue with it. We will use Discord for meetings and progress updates.

Communication Frequency
The team decided to meet weekly to discuss progress, tasks, and goals. Outside of meetings, we will communicate through text.

Task Assignment and Reporting
We agreed to use the GitHub repository along with commit history for tracking progress. All team members will discuss completed and unfinished work throughout the development process.

Collaborators: Hunter Eck, William Meredith, Cedrick Lee, Nathan Reed

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

3-2 Project Log: QA and Testing Plan

-Nathen Reed
[
Our preferred means of communication is primarily discord still, as we can update each other with more casual frequency, but we have also created a planning document to handle workload assignment and feature implementation. Quality assurance is maintained in this pre-alpha stage through communication and planning. We are planning on more extensive playtesting during the Alpha stage this coming week as we first need to complete a basic 2D Testing level.

During the Play Test stage we communicate frequently and share progress, playtesting after any new features are implemented.
Firstly, each game feature will be recorded within our attached test plan document and have a set of methods to verify upon each play test. This method allows us to record and share our play testing results at the various stages of development. To maintain pacing and organize content updates we are also using a plan in that same attached Excel document that specifies the start and completion of production, with the completion requiring a full playtest.
The Demo phase will be scheduled for post Alpha and will be focused on finding and correcting any bugs in the project. Afterwards the focus will shift towards a discussion on design choices and gameplay mechanics. Any and all corrective actions or bugs will be documented here in the test plan just as before. 

The checklist for our test plans thus far is as follows:
Player movement, collision, attacks, UI, and respawning. level traversal, enemy movement, enemy attacks, enemy health widgets, enemy defeat, level checkpoints, Flipbook animation issues.
The Test plan will be updated to include new tests for new features as they are implemented. As issues are encountered they will be documented along with the method used to correct any of these test fails.
bugs are reported and documented in our test plan excel document along with how the bug was encountered. Runtime errors are recorded separately from bugs. Importantly, we will maintain records of the bug and its resolution even after it is corrected. Old bug information will be retained in the relevant section in the excel doc, if it becomes too long a new document will be created to list the past bugs for that specific area of development.
]
-Nathen Reed, in Collaboration with Hunter Eck, William Meredith, Cedrick Lee

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

4-2 Project Log: Team Reflection and Alpha Release
-Nathen Reed
[
(What parts of the testing process did the team perceive to go well?):
I believe documentation went well, and that we haven't encountered as many bugs that may have been expected thus far.

(How were bugs identified and corrected?):
Before pushing a branch any feature was first tested in turn by running unreal in a testing level. In some cases strings were utilized to announce to the tester that a specific piece of logic was being passed correctly or incorrectly.

(In terms of the QA and testing process, what would you do differently to improve the process?):
Thus far the biggest issue with QA has been more with minor communication setbacks. Sometimes various team members, myself included, developed a feature but postponed pushing to the repository in favor of waiting for a collection of features. This results in a bit of lag especially in areas that required features from one class to be implemented before progressing on a different class. This could be improved by breaking down completion dates of features to place greater priority on specific objectives, instead of just using Pre-Alpha, Alpha, Beta. This would also give more room for proper bug testing before that version is actually released.

(What tools (chosen in Module Two) did you find successful in the development of your Alpha project? Why?): 
Of the tools we mentioned here in module 2, discord has still afforded us greater communication and allowed us to make up for our mentioned issues with pushing versions too late. Mostly by easy updates and casual discussion. We have worked well as a team thus far and our planning has been aided by git bash aside from some small problems. Not mentioned previously, we have been making use of Aseprite as a tool to create sprites for our Flipbooks.

(Were there any tools or techniques that you did not find helpful in the success of your project development? Why?):
Again, Git bash is great at times but plenty of times it has been confusing and unwieldy as myself and some other team members aren't too familiar with how it actually functions. At times it feels like it adds to that delayed input that has been bringing us problems.

(How did the team approach to the initial analysis of the game design document contribute to the decision to use these tools and techniques?): 
As I stated before the game design document has guided us towards making a 2D platformer, that has required the distribution of effort. Planning through our excel document has assisted us in deciding priorities and limiting the programming that our lead artist Hunter Eck would have to do as a 2D game requires a lot of sprite work, Unreal Engine doesn't include many sprite creation tools so the creation of sprites is a bit of a bottleneck. It has also necessitated new features to be added that I hadn't initially thought of, such as a system to collect items and ways to store that information to be pulled elsewhere. Additionally, we have had to alter our way of adding new branches somewhat.
]
-Nathen Reed, in Collaboration with Hunter Eck, William Meredith, Cedrick Lee
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
5-2 Project Log: Team Reflection and Beta Release
-Nathen Reed
[
Following our planning from module 3 has gotten us to a solid point for our beta however rushed it may have been. We had established a solid outline for what we intended for our finished project using our planning document. As well we avoided overloading one team member too much with uneven workloads. However, the biggest flaw in our plan was plotting the more minute details such as time frames and due dates. Planning a set of object to all be completed by a set stage is less gradual and resulted in more features being put in later rather than earlier. On top of that my own personal planning had placed less focus on features earlier in dev, whereas our Alpha and especially Beta required progressively more effort. The step up from Alpha to Beta when compared to Pre-Alpha to Alpha has been much more more than expected which has actually resulted in our Beta being late. I'm uncertain however if I was focused too much on ensuring the Beta had a much greater quality than the Alpha. As it stands the completion after Beta will be much less packed.

(What parts of the plan did the team perceive to go well in relation to the last stage evaluation?):
Communication was rather simple and straight forward. We have begun handling git bash with greater ease. Each assigned area has been brought pretty close to completion.

(What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?):
Time management is a major issue, a large portion of blame falls on me for not realizing how intense the workload for this week would be not just for this course alone either. Furthermore, at different points in the process different team members missed important features when pushing a branch that slowed down other team members. Though I think this is partly due to rushing.

(How were the previous evaluations integrated into this latest stage?):
We followed through on what worked well, focused on our set areas and communicated issues quickly. The process for sharing updates has become much faster and our goals for full release are much clearer. Beta was very much the larges speedbump and despite being a little late the project is in a good spot and mainly requires polish.

(What would you do differently to improve the collaboration or development process?):
Largely, overhauling my planning to include general goals but also much more specific goals that set up the team members with a cleaner idea of what all has to be completed before the end of the week. As well, ensuring every team member double checks what they are pushing before they create a branch. As we got faster we also became less accurate at times which didn't hurt our progress too much but it could become a problem that snowballs over time. I gave myself a little too much to do with the level creation all being my area, so I spent more time building the tile maps for Beta than anything else on this project which made it harder for me to get better oversight on where everyone was actually at.

(Were there any tools or techniques that you did not find helpful in the success of your project development? Why?): I didn't find that the Test Planner was as useful as it likely should be with a larger project, but that's likely because its easier to just handle the bugs as soon as you find them. Specifically, writing down the test steps isn't very useful for us at this moment. Though we definitely understand how useful it would be in the future if that bug was recreated, we would want to know the steps that led to it and how to check in future projects. For this project though it's main use is just recording, since we always mention bugs immediately in the discord. 

(Identify the completed stage of development of the intended Beta and address the project schedule to meet Final Release development deadline.):
The completed stage for our Beta hinged on us creating at least two playable levels with all of our features except the boss enemy present on both stages. As I placed most of the level by hand it took longer than I would have expected among some other minor problems we encountered along the way. I also wanted to ensure the game was playable and not overly clunky or buggy. We were late on our Beta however, our Final release is going to be handled with much greater urgency. Fortunately, our beta brough almost the entirety of our endgames features to near completion. The first focus of this week will be upon building our third and final level that includes a small boss fight and a game completion screen. After that its mostly just Quality Assurance and polish, making smaller changes to timers, hitboxes, sprite sizes, etc... 
]

-Nathen Reed, in Collaboration with Hunter Eck, William Meredith, Cedrick Lee
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

6-2 Project Log: Team Reflection and Beta Release
-Nathen Reed
[
(As a team, you will routinely conduct reviews based on your progression towards the plans that you created. Evaluate the plan that your team created in Module Three from an artist’s standpoint.):
From the perspective of an artist, our plan provided much less direction as to what the final design should be. We only planned on a 16x16 pixel sizing and the player character being a rabbit. Along with that the overall designation of what exact sprites were needed was not really a feature in our planning and likely should have been. In retrospect the planning we did conduct towards the design only had generalized goals for the art. Such as 'complete tileset for stages' instead of of specifying the style and type of sprites needed.

After completing your plan analysis, conduct a team reflection and consider the following:

(What parts of the plan did the team perceive to go well in relation to the last stage evaluation?): This stage has been relatively less intense as the workload has lessened for the entire team. Some features were improved quite a bit since our other version by small changes like adding a delay just before the knockback from the stomp attack is applied.

(What parts of the plan did the team perceive to go wrong in relation to the last stage evaluation?): Personally, I had much more of an issue implementing the boss class and building it to be reactive to the player. I made use of another class I had made previously but I had different goals for this boss than the last one I had made. Meaning I had to adjust and correct issues that game from those differences. However, this stage of development has mostly been centered around polishing the game and finding bugs. Some of which have surprised us in different ways. Such as a little bug caused by me accidentally not connecting two objects in the respawn event.

(How were the previous evaluations integrated into this latest stage?): Firstly, looking back on the previous stage I began work on the boss class sooner instead of too late as it was the last major feature we really had to work in. We diverted some of the effort that would have distracted me by placing our artist Hunter Eck in charge of building the last level and boss arena as much of the sprite work was completed last week. This freed me up to focus on the boss. Additionally, I tried to provide much more clear directions towards the other team members as to what we needed by the end of this stage.

(What would you do differently to improve the collaboration or development process?):
Mostly, planning and time management could have improved. Understanding what time worked best for each team member would have aided in completing sections sooner. As well, general experience with collaboration has introduced many different aspects of planning we were less aware of beforehand. Such as more concrete art direction so that the artist could focus on goals easier. More importantly, understanding the expectations of each stage better so we could have planned more accurately, some features like the boss class were meant to be implemented sooner. However, our Beta stage was already somewhat overwhelming in workload.

(Were there any tools or techniques that you did not find helpful in the success of your project development? Why?): 
As before, our excel document that kept track of features with their completion date and our test planner saw less use in our final stages. Not to say they were not useful in collaboration and early planning, only that as we progressed, they became more vague and less helpful. As well, I tried to keep things generally open so that the team members could take some creative freedoms in their assigned goals. This less centralized approach helped us by limiting excessive micromanagement but it also had the downside of limiting expectation. While each team member performed well in their areas some features had to be added in post discussion. Mostly due to less defined objectives from the team leader me. Our more relaxed communication methods helped keep issues like that simple but it had the downside that we didn't really have strict meeting schedules to keep everyone on the same page. I was primarily  stating goals to team members with less feedback from them as to what type of planning we were lacking. I likely should have taken extra care in gathering more formal plans and goals.

]

-Nathen Reed, in Collaboration with Hunter Eck, William Meredith, Cedrick Lee
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------