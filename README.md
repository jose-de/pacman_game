# 👻 Pacman Game - Modification and Version Control

## 📄 Repository Description
This repository contains the source code for the **Pacman** game in Python. The original base code belongs to the *Free Python Games* collection by Grant Jenks. The purpose of this repository is to document the modifications made to the source code while working as a team using a distributed version control system (Git and GitHub).

The source code has been documented and formatted strictly following Python style guides (**PEP 8**), ensuring clean, modular, and professional programming standards according to the institute's guidelines.

## 🛠️ Features Implemented
As part of the activity, the original code was modified by integrating the following features. The software engineering rule of "one feature per commit" was applied by working on separate branches:

*   **Smarter Ghosts:** Implemented a distance-based heuristic algorithm (minimizing Euclidean distance) so the ghosts actively pursue Pacman instead of making random choices. *(Developed by: José Manuel Cisneros Palma)*
*   **Change the Board:** Modified the tile matrix array to create a completely new map layout and structural environment for the game. *(Developed by: Juan Manuel Gonzalez Rocha)*
*   **Faster Ghosts:** Adjusted the movement vectors and speed parameters of the ghosts to significantly increase the game's difficulty. *(Developed by: Juan Manuel Gonzalez Rocha)*

## 👥 Collaboration Dynamics (Git & GitHub Roles)
To fulfill the project evidence criteria and simulate a real professional development environment, team members alternated roles using the distributed repository workflow (*Fork & Pull Request*):

*   **Owner Role:** José Manuel Cisneros Palma 
*   **Fork Role (Collaborator):** Juan Manuel Gonzalez Rocha

**Workflow:**
1.  The project was divided by creating individual branches for each requirement.
2.  Code integration from the collaborator to the base repository was done via `Pull Requests`.
3.  Conflicts were resolved, and the corresponding `Merges` were executed on GitHub to unify the final code.
4.  A clean commit history was maintained with precise descriptions of each feature update.

## 🚀 How to Run the Game
1. Clone this repository to your local machine:
   `git clone https://github.com/jose-de/pacman_game.git`
2. Ensure you have Python 3 and the `freegames` library installed.
3. Run the main file from your terminal:
   `python pacman.py`
