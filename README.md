# FlashPoint Board Game (Pyromancer edition) 
*The original 'FlashPoint Fire Rescue' Board Game made into a distributed 2D game on desktop with a few twists ...*

<p align="center">
  <img src="https://github.com/jz360/flashpoint/blob/master/fp.gif">
</p>

## Context:

- As part of McGill undergraduate course **COMP 361 (Software Engineering Project)**, a senior year project spanning 2 semesters ~ roughly 8 months (Fall 2018 - Winter 2019).

- Course description:
*Software development process in practice: requirement elicitation and analysis, software design, implementation, integration, test planning, and maintenance. Application of the core concepts and techniques through the realization of a large software system.*

## The application
A desktop app for the board game **FlashPoint Fire Rescue**, a turn-based strategic game (by designer Kevin Lanzing).

- Official Game Rules booklet: https://github.com/jz360/flashpoint/blob/master/core/assets/fp_rules.pdf

- Implementation followed a model-driven engineering approach and the SDLC

- The passionate Pyromancer Team behind the project: David-Gilbert-cs, dch133, Elvric, jz360, mathieuvachon2, simz089s

## Setup FlashPoint (Pyromancer edition):

1. Clone the repo

2. Open the project using **IntelliJ IDE**

3. After the project is built, click on **'Edit Configurations...'** and add the following two **Application** configurations:
- One named 'Server' with Main class: *com.cs361d.flashpoint.desktop.DesktopServerLauncher*
- Another named 'Client' with Main class: *com.cs361d.flashpoint.desktop.DesktopClientLauncher*

For **both** Server and Client: 
- Set the **Working directory** to: *./core/assets/*
- Set the **classpath of module** to: *desktop_main*

4. Run the Server first

5. To run as a Client, connect to the Server by setting the **DEFAULT_SERVER_IP** variable in *core/src/com/cs361d/flashpoint/networking/NetworkManager.java* to the Server's IP address. Finally, run the Client.

note: if playing on a single computer, change **IS_MY_TURN_ACTIVATED** variable to false in BoardScreen.java

## Outcome (after many coffees and late nights):
✔ Successfully implemented all the FlashPoint board game functionalities & features (see official game rules booklet)

✔ Added many extra features such as a chatting system, bonus roles (the Pyromancer), random maps, and game effects (audio)

🏆 Obtained the top marks in the class (out of 14 teams)

## Gallery (images)

[![login-4.png](https://i.postimg.cc/vHCxfdrW/login-4.png)](https://postimg.cc/nCYLfgwz)

[![create-3.png](https://i.postimg.cc/9MzcLDVz/create-3.png)](https://postimg.cc/7G8v6Y5y)

[![board-5.png](https://i.postimg.cc/pL24QyDj/board-5.png)](https://postimg.cc/QHyfh8YN)
