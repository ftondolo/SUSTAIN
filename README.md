# SUSTAIN
Final project for CMSC20900: Computers for Learning made with Caroline Apple and Camila Arcentales.
A Unity C# educational game designed to teach children ages 11-13 about sustainability.

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#objective">Objective</a></li>
    <li>
      <a href="#game-design">Game Design</a>
      <ul>
        <li><a href="#learning-trajectory">Learning Trajectory</a></li>
      </ul>
      <ul>
        <li>
          <a href="#levels">Levels</a>
          <ul>
            <li><a href="#1">1</a></li>
          </ul>
          <ul>
            <li><a href="#2">2</a></li>
          </ul>
          <ul>
            <li><a href="#3">3</a></li>
          </ul>
        </li>
      </ul>
    </li>
    <li>
      <a href="#reflection-and-next-steps">Reflection and Next Steps</a>
      <ul>
        <li><a href="#what-we-learned">What we Learned</a></li>
      </ul>
      <ul>
        <li><a href="#whats-next">What's Next?</a></li>
      </ul>
    </li>
  </ol>
</details>

## Objective
We set out to create a game which makes no preconceptions about its users and therefore has no biases embedded in its usability, allowing for people of diverse cultural, technical, and societal backgrounds to interact with an educational game on a level playing field to reach a communal learning goal. To achieve this we built a game from the ground up using the Unity 2D engine to construct an educational game about ecological sustainability whose every facet we tailored to attempt to be as intuitive as possible to as wide a gammit of users as we could think of such as taking into consideration disabilities such as color blindness and impaired sight in designing the UI. Our ultimate goal was to introduce our users to the concepts of resource usage and associated waste, and environmental responsibility through the demonstration of causality and how when one has control over an environment it is one's own choices which determine its health and ultimate survival.

## Game Design
For more information, the writeup contains far more in depth detail thamn this short description including hypothetical target users, the skillset the game is seeking to sharpen in its users, our efforts to craft culturally-relevant instruction, and the way the game motivates different kinds of players to engage in the learning experience whether they are more interestedd in accumulating rewards or badges (Collectors), those who are attracted by an engaging storyline (Storytellers), or simply those who like to see the world burn (Jokers) among many others.

The game is a simulation where players are given control of a limited environment including the temperature, light exposure, and water levels of the plants stored therein and the responsibility is placed upon them to make the plants flourish while making sure their control is judicious by tasking them to keep in check other externalf factors such as C02 levels.  Water and light are importnat, yet moderation is key and one eventually starts receiving diminishing returns as the plants beegin to drown or dry out respectively. Excessive use of artificial lights also requires energy which comees at a cost: if C02 reaches dangerous levels in the enclosure thee plants will have no more Oxygen for photosynthesis yet the way different plants will react to this also varies. In a quest for balance users need to make cost conscientious decisions about the best ways to tend to their plants in the presnt without forgoing long-term stability.

### Learning Trajectory
To try and teach our users these abstract concepts without alienating our rather young target age group we settled on a spiral learning trajectory. This learning method works as follows: after introducing a central concept, for instance the simple idea that actions have consequences, the game develops the idea by introducing new facets to it while also refreeshing and reviewing the tenet in each new "revolution" of the spiral as the breadth of the learning trajectory expands. Thusly working step-by-step the user is not flooded with nonrepresentational ideas which are hard to grasp but is rather guided through the formational components of the overarching theme of sustainability without making any logical leaps which may turn off the user from continuing to play.

### Levels
The Game was split into three separate levels, each designed to introduce a new aspect of the game's environment to the player in logical progession to eventually populate the entire GUI.

#### Level 1:
  - The simplest of the levels introduces the players to the game by planting their first plant. They are made to select a seed from a pre-seleected variety (with possibility for more seeds after completing the tutorial) of disparate locations around th world allowing not only for a level of customization but also for an opportunity to learn about different plant species.  Once a fertilizer is also selected between a more effective yet resource wasteful nitrogen-based variant and more basic compost the player is shown the main screen!  Here, the player is shown around the UI pointing out what each indicator on-screen is meant to rpresent and its importance. The level ends with the player gaining the Earth badge, commemorating the planting of their seed and giving them encouragement to keep playing on!

#### Level 2:
  - Now, one plant is all well and good but true sustainability is about weighing the needs of many individuals, to tend to one is  too simple an equation for the weight of one's actions to be effectively taught so the player is introduced to a mini-game environment with three different plants. Here, the effect of light sources in introduced by asking the user to make thir three plants grow as much as possible with the two light sources available to them. Sunlight will make their plants grow less quickly but will do so without impacting C02 levels. Artifical grow lights on th other hand will speed the process up with the side-effect of also increasing C02. At the end of the circa 30s mini-game the differece between these two light sources will have ben demonstrated to the players organically, without them having been fed thee information through lengthgy verbal descriptions (such as this one) and earning them the light badge!

#### Level 3:
  - Back in their original, level 1, garden with th addition of light of course, the players are now left to their own devices a little bit.  After a couple of minutes of uninterrupted play to allow the players a dgree of flexibility in what is otherwise a quite structured tutorial the game pauses to show them how their actions have impacted their environment. Specifically, the new addition of a light source results in a gradual, yet constant, increase in temperature. Moreover, as their plants grow and C02 accumulates (with the possible compounding effects of artificial lights) the environment heats up quicker still, illustrating the greeenhouse ffect and causing a positive feedback loop to increase difficulty and engage the player. With this new challenge in place, the stakes set, the programmd tutorial ends and the hands-off simulation is primed to begin.

## Reflection and Next Steps

### What we Learned
This was the first tim coding in C# for us and certainly th first time interacting with a proper game engine and the learning curve was certainly steep, something further compoundd by the complications of remote-learning during the COVID-19 pandemic. However, more than just the new language, game design required thinking in terms new to us, including elements such as sprites, animations, interactive graphical menus, and numerous other aspects which strayd from the fixed programmatical mindset one usually evolves in non-game oriented CS work. More than anything it was this mindset which in my personal view was th most valuable take away from this project (apart from the Unity C# know-how which decreases the barrier for entry into computer gaming monstrously).  The undestanding of how a user progress through a game with different scenes, effects, and sprites orchestrated to appear and disappear to give the illusion of progression through a virtual landscape was really quite something. 

### What's Next?
This game is currently only the tutorial, and while to provide the full experience one ned only remove the end screen from this program since the simulation's mechanics have already been defined allowing for nearly-perptual play (or at least until all the plants die) this highlights the double-edged nature of this type of game. Indeed, while the advantages of a simulation-style game lie in that the programmers need only create a reactive environment as oppposed to a proactive one, this also means that the burden of engagemnt is entirely on the useer since everything is in their control, the game cannot fight back. Implementing an adversary bot within the realm of the game, either seeking to outcompete the player or merely destroy their own gardn by sabotaging their efforts would not only give the game  a more laborate type of difficulty to increase engagemnt but also would serve as a learning opportunity for ourselves to not only create a bot but also balance its ddifficulty in such a way as to provide a challenge without discouraging the player, perhaps requiring the introduction of furtheer features to balance the playing field, placing an interesting challengee.
