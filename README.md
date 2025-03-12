# The 2025 ICRA Arena Challenge
As part of the workshop Advances in Social Navigation: Planning, HRI and Beyond, the Arena 2025 challenge aims to benchmark recent state of the art social navigation approaches for navigation in crowded collaborative environments. We utilize our arena platform to host the competition. The **Arena Challenge 2024** invites participants to tackle the complexities of **social navigation** in **crowded, dynamic, and collaborative environments**. The goal is to develop autonomous navigation solutions capable of efficiently maneuvering through environments filled with pedestrians, dynamic obstacles, and realistic social interactions.

## 🎯 Challenge Overview
Participants are required to design and develop navigation algorithms that can handle:
- **Dynamic and Complex Environments**: Navigate through environments populated with moving pedestrians and unpredictable social dynamics.
- **Socially Aware Navigation**: Respect social norms, avoid collisions, and interact safely with dynamic groups.
- **Scalable Difficulty Levels**: Overcome environments that gradually increase in complexity and difficulty.

## 🚀 Challenge Focus
- **Dynamic & Crowded Environments**: Tackle multiple dynamic environments populated with moving pedestrians, obstacles, and social interactions.
- **Social Interaction Awareness**: Navigate while respecting social norms, avoiding collisions, and adapting to unpredictable human behaviors.
- **Collaborative Scenarios**: Address scenarios that require understanding and adapting to group dynamics and collaborative movement within crowds.

## 🛠️ Evaluation Criteria
Algorithms will be evaluated based on:
- **Efficiency**: How quickly and effectively the robot can navigate through the environment.
- **Safety**: Avoidance of collisions with pedestrians and dynamic obstacles.
- **Social Compliance**: Adherence to social norms and smooth navigation in collaborative scenarios.

## 🏆 Prize Money
Top-performing teams will be awarded **prize money** in recognition of their innovative and effective solutions.

## 🛠️ Competition Structure
- A series of **dynamic environments** with varying levels of complexity and difficulty.
- Each environment simulates real-world social dynamics, including:
  - Dense pedestrian traffic
  - Variable speeds and unpredictable movements
  - Collaborative human behaviors and group formations

## 👥 Who Should Participate?
- Researchers in robotics, AI, and autonomous systems.
- Developers focusing on social navigation and dynamic path planning.
- Innovators aiming to push the boundaries of autonomous navigation in social contexts.

## 📅 Timeline
- **Registration Opens**: 15 March 2025  
- **Challenge Begins**: 15 March 2025  
- **Submission Deadline**: 01 May 2025  
- **Winner Announcement**: 21 May 2025

## ⚙️ How to Participate
1. **Register** your team via [Insert Link].
2. **Download** the environment simulation package.
3. **Develop** your navigation algorithm to tackle the dynamic social scenarios.
4. **Submit** your results for evaluation.

## 🌟 Why Join?
- Benchmark your navigation solutions against the best in the field.
- Gain exposure and feedback from experts and industry leaders.
- Contribute to advancing social navigation research and real-world applications.

## 📝 Competition Rules

Participants in the **Arena Challenge 2024** are required to develop autonomous navigation systems capable of effectively operating in dynamic, crowded, and collaborative environments. The primary objective is to navigate a standardized robot from a predefined start location to a goal location as efficiently and safely as possible, adhering to the following rules:

1. **Robot Specifications**:
   - **Platform**: Clearpath Jackal robot equipped with:
     - **Perception**: 2D LiDAR with a 270° field of view.
     - **Actuation**: Differential drive system with a maximum speed of 2 m/s.
     - **Computation**: Onboard computing resources provided by the organizers.

2. **Environment**:
   - **Dynamic Obstacles**: Environments will include moving pedestrians and dynamic obstacles exhibiting various motion profiles to simulate real-world social scenarios.
   - **Variability**: Environments will vary in complexity, from moderately crowded spaces to highly dynamic and dense crowds.

3. **Task**:
   - Develop a navigation system that processes LiDAR input and outputs motion commands to drive the robot from the start to the goal location without collisions.

4. **Approaches**:
   - Participants may employ any method, including classical planning algorithms, machine learning techniques, or hybrid approaches.

5. **Simulation and Physical Trials**:
   - The competition consists of both simulated environments and physical trials at the conference venue.
   - Performance in simulation will determine eligibility for the physical trials.

## 📝 Competition Rules

Participants in the **Arena Challenge 2024** are required to develop autonomous navigation systems capable of effectively operating in dynamic, crowded, and collaborative environments. The primary objective is to navigate a standardized robot from a predefined start location to a goal location as efficiently and safely as possible, adhering to the following rules:

1. **Robot Specifications**:
   - **Platform**: Clearpath Jackal robot equipped with:
     - **Perception**: 2D LiDAR with a 270° field of view.
     - **Actuation**: Differential drive system with a maximum speed of 2 m/s.
     - **Computation**: Onboard computing resources provided by the organizers.

2. **Environment**:
   - **Dynamic Obstacles**: Environments will include moving pedestrians and dynamic obstacles exhibiting various motion profiles to simulate real-world social scenarios.
   - **Variability**: Environments will vary in complexity, from moderately crowded spaces to highly dynamic and dense crowds.

3. **Task**:
   - Develop a navigation system that processes LiDAR input and outputs motion commands to drive the robot from the start to the goal location without collisions.

4. **Approaches**:
   - Participants may employ any method, including classical planning algorithms, machine learning techniques, or hybrid approaches.

5. **Simulation and Physical Trials**:
   - The competition consists of both simulated environments and physical trials at the conference venue.
   - Performance in simulation will determine eligibility for the physical trials.

---

## 📊 Calculation of Metrics and Points

Performance evaluation will be based on the following metrics:

### 1. Completion Time ( \( T \) )
- The time taken by the robot to navigate from the start to the goal location.

### 2. Collision Penalty ( \( P \) )
- A penalty incurred for each collision with dynamic obstacles or pedestrians, calculated as:

$$
P = N_c \times p
$$

Where:  
- \( N_c \) = Number of collisions  
- \( p \) = Penalty per collision (a constant value determined by the organizers)

### 3. Social Compliance Score ( \( S \) )
- A score reflecting the robot's adherence to social norms, such as maintaining appropriate distances from pedestrians and avoiding abrupt movements.  
- This score ranges between **0** (non-compliant) and **1** (fully compliant).

---

### 🚀 Overall Performance Score

The overall performance score is calculated as follows:

$$
\text{Score} = \frac{1}{T + P} \times S
$$

Where:  
- \( T \) = Completion time (in seconds)  
- \( P \) = Total collision penalty  
- \( S \) = Social compliance score  

> **Note**: A **higher score** indicates better performance, balancing efficiency, safety, and social compliance.



## 🏅 Leaderboard: Arena Challenge 2024

The leaderboard ranks participating teams based on their overall performance scores, considering completion time, collision penalties, and social compliance.

| **Rank** | **Team Name** | **Completion Time (s)** | **Collision Penalty** | **Social Compliance Score** | **Final Score** |
|----------|--------------|-------------------------|-----------------------|----------------------------|-----------------|
| 1        | Team Alpha   | 120.5                   | 2.0                   | 0.95                       | 0.0076          |
| 2        | RoboNav      | 135.2                   | 1.5                   | 0.90                       | 0.0065          |
| 3        | NavAI        | 140.8                   | 3.0                   | 0.92                       | 0.0063          |
| 4        | PathFinders  | 150.0                   | 4.0                   | 0.88                       | 0.0055          |
| 5        | SocialBot    | 160.3                   | 2.5                   | 0.85                       | 0.0052          |
| ...      | ...          | ...                     | ...                   | ...                        | ...             |

### 📊 Score Calculation Formula
\[
\text{Final Score} = \frac{1}{T + P} \times S
\]
Where:  
- \( T \) = Completion Time (in seconds)  
- \( P \) = Collision Penalty  
- \( S \) = Social Compliance Score (between 0 and 1)  

### 🛠️ How to Interpret the Scores
- **Higher scores** indicate better navigation performance, accounting for efficiency, safety, and social awareness.  
- **Collision Penalties**: Every collision incurs a predefined penalty, increasing the total score denominator.  
- **Social Compliance**: Robots that adhere to social norms and safe navigation behaviors receive higher scores.

---

**Note**: The leaderboard will be **continuously updated** as teams submit and improve their solutions.

## 👥 Organizers

The **Arena Challenge 2024** is organized by a dedicated team of experts in robotics, AI, and autonomous navigation. Our goal is to advance research in socially-aware navigation and contribute to real-world robotics applications.

| ![Organizer 1](https://via.placeholder.com/150) | ![Organizer 2](https://via.placeholder.com/150) | ![Organizer 3](https://via.placeholder.com/150) |
|------------------------------------------------|------------------------------------------------|------------------------------------------------|
| **Dr. Linh Kaestner**                          | **Dr. Alex Doe**                               | **Prof. Jamie Lee**                             |
| Lead Organizer                                 | Technical Chair                                | Research Advisor                                |

| ![Organizer 4](https://via.placeholder.com/150) | ![Organizer 5](https://via.placeholder.com/150) |
|------------------------------------------------|------------------------------------------------|
| **Samim Ahmadhi**                             | **Jordan Smith**                              |
| Program Manager                               | Logistics Coordinator                          |

---

### 🎯 About the Organizers

- **Linh Kaestner**: Lead developer of the **Arena platform** and expert in simulation environments for social navigation.  
- **Alex Doe**: Specialist in dynamic robotics systems and advanced AI planning algorithms.  
- **Jamie Lee**: Advisor and mentor, contributing to research strategies and evaluation frameworks.  
- **Samim Ahmadhi**: Project manager overseeing timelines, communication, and partnership coordination.  
- **Jordan Smith**: Responsible for event logistics, communications, and participant support.
