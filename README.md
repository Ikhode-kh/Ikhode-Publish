# Ikhode-Publish

# Development of a Racing Game with Traffic Simulation

## Abstract
This project focuses on developing a realistic racing game integrated with a traffic simulation system. The game aims to mimic real-world driving conditions, requiring players to follow traffic laws, including driving on the correct side of the road, using turn signals, and stopping at red lights.

## Table of Contents
1. [Introduction](#introduction)
2. [Literature Review](#literature-review)
3. [Methodology](#methodology)
    - [Project Planning](#project-planning)
    - [Design](#design)
    - [Implementation](#implementation)
    - [Testing](#testing)
4. [Results](#results)
5. [Discussion](#discussion)
6. [Conclusion](#conclusion)
7. [References](#references)
8. [Appendices](#appendices)

## Introduction
This project explores the development of a racing game with an integrated traffic system. The game aims to simulate real-world driving conditions, where players must adhere to traffic laws, such as driving on the correct side of the road, using turn signals, and stopping at red lights.

## Literature Review
A review of existing literature on racing games and traffic simulations was conducted. Various traffic simulation techniques were analyzed, and different game development tools and frameworks were compared to determine the best approach for this project.

## Methodology
### Tools and Technologies
- **RVP (Vehicle Controller):** [Randomation Vehicle Physics](https://github.com/JustInvoke/Randomation-Vehicle-Physics/tree/master) by JustInvoke
- **UI Template:** [Gamepad Navigation, Scroll Views, and Selection Groups](https://assetstore.unity.com/packages/tools/gui/gamepad-navigation-scroll-views-and-selection-groups-81277)
- **Scene Transitions:** [Easy Transitions](https://assetstore.unity.com/packages/tools/gui/easy-transitions-225607)
- **Game Engine:** Unity
- **Database:** MySQL with PHP for database interaction
- **Email:** Google API SMTP with PHPMailer for password reset requests
- **Graphics:** Unity's URP template and measured material library
- **3D Models:** Car models from SnowWall via Free3D
- **Mapping:** GIS world map with shapefile of Cambodia for the project blueprint

### Design
The game design includes the following elements:
- **Game Concept and Design Principles:** Focus on realism and adherence to traffic rules.
- **Level Design and Environment Setup:** Creation of urban and suburban environments.
- **Vehicle Design and Physics:** Realistic vehicle behavior using RVP.
- **AI for Traffic and Player Vehicle Control:** AI-driven traffic that interacts with the player's vehicle.

#### Authentication
##### Login

- <img src="https://github.com/user-attachments/assets/d62203b9-0db0-423b-9527-64edd753fa84" width="400"/>

##### Register

- <img src="https://github.com/user-attachments/assets/d35c01b9-926e-4530-b0f5-c7863ef866d8" width="400"/>

##### Request Reset Password

- <img src="https://github.com/user-attachments/assets/682578f4-c800-4f11-8cb9-d1cd3f69b542" width="400"/>

#### Mode & Sense Selection 

- <img src="https://github.com/user-attachments/assets/34603dcf-de07-4d03-b99b-0da1fb45796b" width="400"/>

### Implementation
The implementation phase involved:
- Developing core gameplay mechanics.
  
 - <img src="https://github.com/user-attachments/assets/7444c7df-9e49-4a65-9f73-571917e490b5" width="400"/>

- Coding traffic laws and driving rules.

 - <img src="https://github.com/user-attachments/assets/805678b9-de28-4024-9767-3e94bfcd7561" width="400"/>
- Integrating AI for realistic traffic behavior.
- Performance Optimization
  - **Level of Detail (LOD):**
-  <div style="display: flex; justify-content: space-around;">
      <img src="https://github.com/user-attachments/assets/f59aabd2-188c-437d-b3df-da62ba8d321f" alt="LOD Image 1" width="150">
      <img src="https://github.com/user-attachments/assets/066fa48b-6d66-44ed-ab1f-2346c7c26cb2" alt="LOD Image 2" width="150">
      <img src="https://github.com/user-attachments/assets/a02d0040-a4aa-4351-8d40-7068ef2ba6b6" alt="LOD Image 3" width="150">
      <img src="https://github.com/user-attachments/assets/63c24a8e-d71f-4728-8511-62ed230b658d" alt="LOD Image 4" width="150">
      <img src="https://github.com/user-attachments/assets/6ddf8220-274a-49f4-bfd5-869695d6799d" alt="LOD Image 5" width="150">
</div>

- Utilizing Unity's new input system for improved control.
 
 - <img src="https://github.com/user-attachments/assets/efc154f8-8ed8-4a66-a879-9a3cc4581906" width="400"/>
### Testing
- Unit testing for individual components.
- Integration testing to ensure smooth interaction between game elements.
- User acceptance testing to gather feedback and make necessary adjustments.
  - The UI is well-designed, allowing control via keyboard, mouse, gamepad, and game controller, making it user-friendly.
  - Gameplay currently features a single camera position (not inside the car yet) but includes functions like blinkers, enhancing the player's experience.

### Results
- The final game features realistic traffic behavior and a challenging racing environment.
- It deducts 10 points for traffic violations or rule infractions.
- The transitions are visually appealing.
- While the graphics are not as realistic as HDRP, the URP graphics are impressive.
- The game maintains a smooth performance, running at 90 to 110 FPS.

### Conclusion
- This project successfully developed a racing game that simulates real-world traffic conditions, offering a unique and challenging experience for players.
- Although the game is nearly complete, further improvements, such as restructuring the database and enhancing the UI for better graphics, are planned for the next month.

## References
- Books, research papers, and articles on traffic simulation and game development.
- Documentation for Unity, RVP asset, and the new Unity input system.


---

*Created by [Ikhode Arena]*  
*Advisor: [BunChhun]*  
*Date: [28/07/2024]*
