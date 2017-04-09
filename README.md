# Idle.Next
Iteration II of Idle Game

== Project Plan ==

Technical Milestones:
- [x] GitHub setup

- [ ] Separate game logic from UI logic (game logic in new library, no WinForm specific objects in function arguments).
- [ ] Convert game logic to C#.
- [ ] Separate database access logic from game logic.
- [ ] Create API layer for accessing game logic.
- [ ] Hook Legacy UI to API.
- [ ] Separate threads for UI and game logic - game logic runs mostly headless (one player).
- [ ] Game logic runs headless for multiple players at once.
- [ ] Create UI layer that outputs HTML5 read only UI (refresh click required).
- [ ] Allow HTML5 UI to raise events in game logic and react.
- [ ] Allow game logic to raise events in HTML5 UI (no more refresh clicks).
- [ ] Create database service with API and hook game logic to it.
- [ ] Create directory service to store service locations.
- [ ] Create authorization service to secure game and secure communication between services.
- [ ] Get cloud VMs for directory service, database service, then game logic.
- [ ] Create simple web portal that hosts HTML5 UI.
- [ ] Create Android thin client that is a glorified link to web portal (requires internet to play)
- [ ] Android thick client (offline mode) - portable game logic/database combo, refactor for battery efficiency.
- [ ] A moment for reflection.
- [ ] Encrypt messages between services

Secondary objectives:
-v2 Name
-Refine game elements and content
-Advertise game to others for feedback
-API documentation
-Installers to streamline VM setup