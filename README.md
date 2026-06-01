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