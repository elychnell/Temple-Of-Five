# The Temple of Five

![The Temple of Five Startpage](/public/images/startpage.png)

Welcome to **The Temple of Five**, a digital escape room and atmospheric puzzle adventure game created by **The Pogo Stick Pioneers**. 


## My Contribution

I was involved in both the development of the game and the integration of the different systems created by the team.
My main individual contribution was the Earth Room, which I developed from scratch, including its game logic and timer functionality.

I also contributed to the project by:

- Implementing and adapting the timer functionality
- Integrating functionality developed by other team members into my room
- Contributing to debugging and improving the game's cheat engine
- Participating in testing, debugging and general polishing of the game
- Presenting the finished project

As part of our Scrum-based workflow, all team members also took turns acting as Scrum Master, giving everyone experience with planning, coordination and facilitating the team's work.

## About the Game

In a future where cities collapsed and the jungle reclaimed the world, one structure still breathes with dormant power. The Temple of Five Elements holds ancient survival tech — sealed behind trials of Wood, Fire, Earth, Metal, and Water. Solve the puzzles, collect the sacred artifacts, and unlock the temple's final secret. Each chamber features its own puzzle and gameplay mechanic designed to test the player's logic, observation, and reflexes.

### **Core Features**

- **Five Elemental Trials:** Distinct puzzles for Wood, Fire, Earth, Metal, and Water.
- **Immersive Atmosphere:** Dynamic audio, custom CSS animations, and thematic visual effects.
- **Real-time Scoring:** Progress tracking with a highscore system based on speed and accuracy.
- **Full Accessibility:** Designed for both mouse and keyboard navigation (ARIA-compliant).
- **Responsive Design:** Optimized for various screen sizes, from desktop to mobile.

## How to Play

1.  **Enter the Temple:** Begin your adventure in the first elemental chamber.
2.  **Solve to Advance:** Read the room's unique instructions, interact with the environment, and solve the puzzle to claim the artifact.
3.  **Master the Elements:** Progress through all five rooms, adapting to different mechanics in each.
4.  **The Final Challenge:** Complete the final trial to see your total score and escape the temple!
    ![Gameplay Demo](/public/images/welcomepage.gif)

## Live Demo

[Live demo](https://elychnell.github.io/Temple-Of-Five/)

## Developer Access

The demo includes a developer shortcut for quickly accessing later
rooms without completing the previous trials.

- **Secret key sequence:** `pogo`
- **Developer code:** `temple5`

Use this to skip directly to later rooms when exploring the project.

The developer shortcut can be used to quickly access the Earth Room and explore my individual contribution.

## Technologies Used

![HTML badge](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white) ![Sass badge](https://img.shields.io/badge/Sass-CC6699?style=flat&logo=sass&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Markdown badge](https://img.shields.io/badge/Markdown-000000?style=flat&logo=markdown&logoColor=white) ![Vite badge](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white) ![Biome](https://img.shields.io/badge/biome-%2360A5FA.svg?style=for-the-badge&logo=biome&logoColor=white)

---

## Screenshots & Validation

### Chrome Lighthouse

![Chrome Lighthouse](/dokumentation/screenshots/lighthouse.png)

### Firefox Rendering

![Firefox Rendering](/dokumentation/screenshots/firefox.png)

### W3C HTML validation results

![W3C HTML Validation](/dokumentation/screenshots/w3c.png)

### W3C CSS / SASS validation results

![W3C CSS/SASS Validation](/dokumentation/screenshots/cssw3c.png)

---

## Design & Planning

- **Game Logic & Flow:** [Miro Flowchart](https://miro.com/app/board/uXjVGD_af74=/?share_link_id=396365481063)
- **Visual Identity:** [Figma Mockup](https://www.figma.com/proto/OJgqdjOM1fksuh2Gh2rsAX/The-temple-of-five?node-id=4-55&p=f&t=QRSCgQpighrHxX8w-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&device-frame=0)

---

## Challenges & Lessons Learned

One of the main challenges was keeping the shared game state consistent across different rooms and interactions.
The project also required careful handling of timers, intervals and event listeners to avoid unwanted behaviour when restarting or replaying the game.

Working as a team introduced additional challenges around Git branches, merge conflicts and coordinating changes to shared functionality.

Integrating functionality developed by different team members also required us to coordinate interfaces between systems and resolve conflicts when combining our work.
## Credits

### The Team:

| Pioneer                  | Role / Profile                                                                                                                    |
| :----------------------- | :-------------------------------------------------------------------------------------------------------------------------------- |
| **Alexander Johansson**  | [![GitHub](https://img.shields.io/badge/GitHub-AlexJCodes-181717?style=flat&logo=github)](https://github.com/AlexJCodes)          |
| **Alexandra Henriksson** | [![GitHub](https://img.shields.io/badge/GitHub-xAlexCode-181717?style=flat&logo=github)](https://github.com/xAlexCode) |
| **Emil Lychnell**        | [![GitHub](https://img.shields.io/badge/GitHub-elychnell-181717?style=flat&logo=github)](https://github.com/elychnell)            |
| **Louise Sverkström**    | [![GitHub](https://img.shields.io/badge/GitHub-LolloLicense-181717?style=flat&logo=github)](https://github.com/LolloLicense)      |
| **Minai Karlsson**       | [![GitHub](https://img.shields.io/badge/GitHub-minza--42-181717?style=flat&logo=github)](https://github.com/minza-42)             |

### Visuals

- **Images:** Generated using ChatGPT's image generator.
- **Icons:** Icons provided by [Iconify](https://iconify.design/) and [Heroicons](https://heroicons.com/). Layout and design work created in [Figma](https://www.figma.com/proto/OJgqdjOM1fksuh2Gh2rsAX/The-temple-of-five?node-id=20-467&p=f&t=QRSCgQpighrHxX8w-0&scaling=min-zoom&content-scaling=fixed&page-id=20%3A467).

### Audio & Sound Effects (via Pixabay)

| Room      | Music                                                                                                             | Sound Effects                                                                                                                                                                                                                                                                                                              |
| --------- | ----------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Wood**  | _Shadowed Whispers_ – [TrenoX8](https://pixabay.com/music/mystery-shadowed-whispers-321103/)                      | Click – [arunangshubanerjee](https://pixabay.com/sound-effects/film-special-effects-cassette-recorder-stop-button-mechanical-click-sound-359987/)                                                                                                                                                                          |
| **Fire**  | _Ambient Burning Castle_ – [Sound Reality](https://pixabay.com/music/ambient-ambient-burning-castle-320841/)      | —                                                                                                                                                                                                                                                                                                                          |
| **Earth** | _Abyssal Echoes_ – [TrenoX8](https://pixabay.com/music/mystery-abyssal-echoes-dark-cinematic-suspenseful-316857/) | Click – [arunangshubanerjee](https://pixabay.com/sound-effects/film-special-effects-cassette-recorder-stop-button-mechanical-click-sound-359987/) <br> Stone Slide – [u_i15wxund59](https://pixabay.com/sound-effects/film-special-effects-stone-slide-sound-effects-322794/)                                              |
| **Metal** | _Veil of Darkness_ – [TrenoX8](https://pixabay.com/music/mystery-veil-of-darkness-321167/)                        | Click – [arunangshubanerjee](https://pixabay.com/sound-effects/film-special-effects-cassette-recorder-stop-button-mechanical-click-sound-359987/)                                                                                                                                                                          |
| **Water** | _The Cave_ – [Andrea Good](https://pixabay.com/music/ambient-the-cave-220274/)                                    | —                                                                                                                                                                                                                                                                                                                          |
| **Final** | _Cursed Forest_ – [TrenoX8](https://pixabay.com/music/mystery-cursed-forest-305207/)                              | Click – [arunangshubanerjee](https://pixabay.com/sound-effects/film-special-effects-cassette-recorder-stop-button-mechanical-click-sound-359987/) <br> _Submority Boom_ – [SUBMORITY](https://pixabay.com/users/submority-30821389/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=123876) |

---
