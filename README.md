# Nasz Typer - Mundial 2026

A real-time Single Page Application (SPA) built to predict football match results among friends. Designed entirely in a single HTML file using vanilla web technologies (HTML, CSS, JavaScript) to challenge my understanding of state management and asynchronous data flow without relying on external frameworks.

## Live Demo
https://czechwiktor.github.io/mundial-2026-typer/

## Key Features
* **Real-time Synchronization:** Uses Firebase Realtime Database to instantly sync match scores, player bets, and chat messages across all clients.
* **Dynamic Point Calculation:** Custom JS engine calculates points (3 for exact score, 1 for outcome) with dynamic multipliers for later tournament stages (x2, x3, x4).
* **Time-based Access Control:** Inputs are automatically locked for regular users the exact moment a match begins, while the admin retains update privileges.
* **Interactive Chat:** Built-in chat module featuring replies, timestamp formatting, and emoji reactions.
* **Responsive UI:** Mobile-first design with CSS animations, day/stage filtering, and visual match status cues.

## Technologies Used
* HTML5, CSS3, Vanilla JavaScript
* Firebase Realtime Database
