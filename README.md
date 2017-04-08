# Idle.Next
Iteration II of Idle Game

== Project Plan ==

Technical Milestones:
[X] GitHub setup

[01] Separate game logic from UI logic (game logic in new library, no WinForm specific objects in function arguments).
[02] Convert game logic to C#.
[03] Separate database access logic from game logic.
[04] Create API layer for accessing game logic.
[05] Hook Legacy UI to API.
[06] Separate threads for UI and game logic - game logic runs mostly headless (one player).
[07] Game logic runs headless for multiple players at once.
[08] Create UI layer that outputs HTML5 read only UI (refresh click required).
[09] Allow HTML5 UI to raise events in game logic and react.
[10] Allow game logic to raise events in HTML5 UI (no more refresh clicks).
[11] Create database service with API and hook game logic to it.
[12] Create directory service to store service locations.
[13] Create authorization service to secure game and secure communication between services.
[14] Get cloud VMs for directory service, database service, then game logic.
[15] Create simple web portal that hosts HTML5 UI.
[16] Create Android thin client that is a glorified link to web portal (requires internet to play)
[17] Android thick client (offline mode) - portable game logic/database combo, refactor for battery efficiency.
[18] A moment for reflection.
[19] Encrypt messages between services

Secondary objectives:
[ ] v2 Name
[ ] Refine game elements and content
[ ] Advertise game to others for feedback
[ ] API documentation
[ ] Installers to streamline VM setup?