Assignment 1: Software Requirements, Use Case Model, and Domain Model

Part A: Formulating Software Requirements
Functional and Non-Functional Requirements
Functional Requirements (FR)
FR1 (Priority 1): The game shall allow the player to control a car that can move smoothly across the map using keyboard inputs.
FR2 (Priority 2): The game shall spawn power-ups randomly on the map that provide either a shield or clear all projectiles on the screen.
Non-Functional Requirements (NFR)
NFR1: The car movement must feel responsive and smooth to ensure a positive driving experience.
NFR2: The hit registration system must be fair and balanced to avoid frustration.
Conversion of NFRs to FRs
NFR1 (Smooth car movement) → FR3: The car movement system shall have precise acceleration and deceleration mechanics to ensure smooth control.
NFR2 (Fair hit registration) → FR4: The hit registration system shall use a consistent and well-calibrated collision detection system for all objects.
Constraints
C1: The game must be playable with standard keyboard controls (WASD or arrow keys).
C2: The game must be developed using Unity for consistency with team expertise.
Traceability Matrix
Non-Functional Requirement (NFR)	Converted Functional Requirement (FR)
NFR1 (Smooth movement)	FR3 (Car movement system ensures smooth control)
NFR2 (Fair hit registration)	FR4 (Consistent collision detection for fairness)

Part B: Use Case Model
Abstract Use Cases (UC)
UC1: Car Movement (ID: UC1_Movement)

Scope: The player moves the car to dodge projectiles and survive as long as possible.
UC2: Power-Up Collection (ID: UC2_PowerUps)

Scope: The player collects power-ups that either grant a shield or clear projectiles from the screen.
Expanded Use Case for UC1: Car Movement
Actor Action	System Response
1. Player presses movement keys.	2. The car moves smoothly in the corresponding direction.
3. Player stops pressing keys.	4. The car slows down naturally, ensuring fluid motion.
5. Car collides with a projectile.	6. The game registers a hit and applies damage or triggers the loss condition.

Part C: Domain Model
Brainstorming & Classification
Key Entities:

Player (controls the car)
Car (driven by the player)
Projectile (hazard)
Power-Up (shield or clear bullets)
Game Session (tracks score and survival time)
