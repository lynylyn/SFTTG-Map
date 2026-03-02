# UX Design Project - 10CT TASK 1
# Project Proposal
For this project, I’ve selected the fantasy novel ‘Set Fire to the Gods’ by Sara Raasch and Kristen Simmons, set in a Greco-Roman inspired world and centring around two warriors. I chose this book specifically due to its invigorating fantasy elements and clear, well-drawn world map - I thought of doing a map before choosing a book, so the world building was very appealing. The software I’ll be designing alongside it is an interactive world map, in which the user can hover over each area for a basic amount of information, and click on different boxes within that to see detailed information on characters, setting, and backstory. This user experience type has a focus on aesthetics (especially with animation and the stylistic map), and this will work especially well to engage the user in the fantasy world. This program is great for people interested in reading ‘Set Fire to the Gods’, but also for those who’ve read it and want more information they may have missed. More specifically, the target audience is young adults (14-18 year olds), who likely have a prior interest in the fantasy genre. For this task, I’ll first be experimenting with Unity - if that doesn’t perform as I’d like, I’ll instead be using Powerpoint.
# Requirements Definition
## Functional Requirements
### Purpose of the Application
- The app will allow users to interact with ‘Set Fire to the Gods’’s world map, hovering over areas for popups which also allow for further interaction. The users should be able to see a basic summary of the selected area, information about characters from that area, and notes about the backstory of it. The application is great both for people already familiar with the book, as well as people interested in getting into it, or just generally knowing more about it.
### User Requirements
- The user should be able to:
    - Hover over locations on the map to view simple summaries
    - Click on buttons within that pop-up to get more information
### Inputs and Outputs
- **INPUTS**:
    - Hovering over the map
    - Clicking within the pop-up
- **OUTPUTS**:
    - Information being displayed (location summary)
    - Information being displayed (characters, backstory, etc.)
### Core Features
- The system must inform users about the novel, giving them the choice of what information to display when. This interactivity will immerse users in the novel.
### User Interaction
- The user will interact with the system through a graphical interface, created in Unity (possibly Powerpoint).
### Use Cases & Test Cases
1. User will hover over a location on the map to view the pop-up
    - Actors: User
    - Preconditions: Code and scene are fully functional
    1. User hovers their cursor over a location
    2. The pop-up shows up
    3. The user can move their mouse away from the location/pop-up to exit
    - Postconditions: Information has been displayed successfully
    - Testing: Can be tested through self-testing / unit-testing, however, it will also be important to ensure hovering works on multiple devices
2. User will click on a character in the pop-up for more information
    - Actors: User
    - Preconditions: Code and scene are fully functional
    1. User clicks on a character within the popup
    2. The user is taken to a different page/scene which displays more information
    3. The user can interact with elements within that page
    4. The user can press the back button to return to the home page
    - Postconditions: The user has been taken to a different page and is able to return
    - Testing: Self-testing is adequate
3. User will click on the location for more information
    - Actors: User
    - Preconditions: Code and scene are fully functional
    1. User clicks on a location rather than hovering
    2. The user is taken to a different page/scene which displays more information
    3. The user can interact with elements within that page
    4. The user can press the back button to return to the home page
    - Postconditions: The user has been taken to a different page and is able to return
    - Testing: Self-testing is adequate
4. User will click the back button to return to the homescreen
    - Actors: User
    - Preconditions: Code and scene are fully functional; user is already within either a character page or a location page
    1. User clicks on the back button
    2. The user is taken back to the home page
    - Postconditions: The user has been taken back to the home page
    - Testing: Self-testing is adequate

## Non-Functional Requirements
### Performance
- 
### Usability
- Hovering over a location should be slightly delayed to ensure there isn't overlap and accidental hovering. 