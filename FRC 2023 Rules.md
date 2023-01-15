# Gameplay
### The grid
- 3x9 grid of "nodes"
- Pieces on nodes grant points
    - Bottom row
        - 3 in auto
        - 2 in teleop
    - Middle row
        - 4 in auto
        - 3 in teleop
    - Top row
        - 6 in auto
        - 5 in teleop
- 3 pieces in a row is a link
    - 5 points per link
    - Pieces can only be in a single link; No piece may be in multiple links at once (so 4 pieces in a row is not 2 links, but 6 in a row is)
    - 5 links on the grid = 1 ranking point (sustainability bonus)
- Bottom row is all "dual nodes", which can fit either cubes or cones
- Other two rows have either cube nodes or cone nodes
    - cone-cube-cone-cone-cube-cone-cone-cube-cone
- Divided into 3 3x3 grids
    - The middle one is the "coopertition grid"
    - 3 pieces in coopertition grid decreases sustainability bonus threshold by 1 (from 5 links to 4)
### The substations
- Substations are used to deliver pieces from outside of the arena to the robots
- 2 kinds of substation
    - Single substation
        - 1 chute
        - Drop pieces down onto the floor
    - Double substation
        - 2 sliding trays
        - Place piece onto tray, slide tray sideways so robot can access it
        - Also the option to drop a piece onto the floor
- Team 5115 will be prioritizing the double substation
### The charging station
- Balance board thing
- Almost entirely blocks access to the community zone in which the grid lies
- There are small spaces on either side of it, but it's a tight turn to make (still doable)
- At the end of each phase, robots on the charging station grant points
    - 2 states
        - Docked
            - Robot fully supported by the charging station
        - Engaged
            - Charging station is level (indicated by light strip under the transparent platform)
    - At the end of auto, docked/engaged points can only be scored by 1 robot (2 robots docked and/or engaged would not net 2 robot's worth of points)
    - End of auto
        - Docked = 8 pts
        - Docked + engaged = 12 pts
    - End of teleop
        - Docked = 6 pts
        - Docked + engaged = 10 pts

|                         | No teleop dock/engage | 1 teleop dock | 2 teleop docks | 3 teleop docks | 1 teleop engage | 2 teleop engage | 3 teleop engage |
|-------------------------|-----------------------|---------------|----------------|----------------|-----------------|-----------------|-----------------|
| **Auto engage**         | 12                    | 18            | 24             | ***30***         | 22              | ***32***          | ***42***          |
| **Auto dock**           | 8                     | 14            | 20             | ***26***         | 18              | ***28***          | ***38***          |
| **No auto dock/engage** | 0                     | 6             | 12             | 18             | 10              | 20              | ***30***          |
- If at least 26 points were earned from being docked and/or engaged on the charging station, 1 ranking point is given (activation bonus)
# Rules
- No extensions when in the opponent's loading or community zone
    - Penalty: [foul](#foul)
    - [Tech foul](#tech-foul) per repeated instance
- No contacting opponent robots when in the opponent's loading or community zone
    - Penalty: [foul](#foul) per instance
- Robots can only be in [control](#control) of 1 game piece at a time
    - Penalty: [foul](#foul) per additional game piece
    - Yellow card if egregious
- A robot may not move a scored game piece from an opponent's node
# Defitions
### CONTROL
The state of a game piece if any of the following are true:
- The game piece is fully supported by the robot
- The robot is intentionally moving a game piece to a desired location or in a preferred direction
### Foul
5 game points to opponent alliance
### Tech Foul
12 game points to opponent alliance
### Yellow card
Warning - 2 yellow cards = red card = disqualification