# The 2025 ICRA Arena Challenge 
As part of the workshop Advances in Social Navigation: Planning, HRI and Beyond, the Arena 2025 challenge aims to benchmark recent state of the art social navigation approaches for navigation in crowded collaborative environments. We utilize our arena platform to host the competition. The **Arena Challenge 2024** invites participants to tackle the complexities of **social navigation** in **crowded, dynamic, and collaborative environments**. The goal is to develop autonomous navigation solutions capable of efficiently maneuvering through environments filled with pedestrians, dynamic obstacles, and realistic social interactions.

## Challenge Overview
Participants are required to design and develop navigation algorithms that can handle:
- **Dynamic and Complex Environments**: Navigate through environments populated with moving pedestrians and unpredictable social dynamics.
- **Socially Aware Navigation**: Respect social norms, avoid collisions, and interact safely with dynamic groups.
- **Scalable Difficulty Levels**: Overcome environments that gradually increase in complexity and difficulty.

Participants will integrate their planner into our arena platform and upload their code on a dedicated branch for us to test. 

<span style="color:red; font-size:1.2em; font-weight:bold;">Important:</span> We have integrated a number of state-of-the-art planners in the past and have encountered issues such as overfitting, functionality errors, non-operational planners, outdated dependencies, and more. These challenges make reproducibility a key concern. Please reach out to us if you experience any problems during integration. Our team of dedicated researchers is available to assist you and can even retrain your algorithms on our servers. Feel free to contact us for any support you may need.


## 🛠️ Evaluation Criteria and Calculation of Metrics
Algorithms will be evaluated based on:
- **Efficiency**: How quickly and effectively the robot can navigate through the environment.
- **Safety**: Avoidance of collisions with pedestrians and dynamic obstacles.
- **Social Compliance**: Adherence to social norms and smooth navigation in collaborative scenarios.
Performance evaluation will be based on the following metrics:

Following calculations will be conducted to determine the scores of each planner:
### 1. Completion Time ($T$)
- The time taken by the robot to navigate from the start to the goal location.

### 2. Collision Penalty ($P$)
- A penalty incurred for each collision with dynamic obstacles or pedestrians, calculated as:

$$
P = N_c \times p
$$

Where:  
- $N_c$ = Number of collisions  
- $p$ = Penalty per collision (a constant value determined by the organizers)

### 3. Social Compliance Score ($S$)
- A score reflecting the robot's adherence to social norms, such as maintaining appropriate distances from pedestrians and avoiding abrupt movements.  
- This score ranges between **0** (non-compliant) and **1** (fully compliant).

---

### 🚀 Overall Performance Score

The overall performance score is calculated as follows:

$$
\text{Score} = \frac{1}{T + P} \times S
$$

Where:  
- $T$ = Completion time (in seconds)  
- $P$ = Total collision penalty  
- $S$ = Social compliance score  

> **Note**: A **higher score** indicates better performance, balancing efficiency, safety, and social compliance.

## Prize Money
Top-performing teams will be awarded **prize money** in recognition of their innovative and effective solutions.

## Competition Structure
The competition is structured around a series of dynamic environments designed to challenge participants with increasing levels of complexity and difficulty. Each environment features variable speeds, unpredictable movements, emergency situations, and doorway blockage scenarios. In total, there are nine distinct environments, each offering three goal positions. Participants will upload their code to a dedicated GitHub branch, and the organizers will execute the code on our servers. For each planner, every goal position will be run twice, resulting in a total of 54 runs. These runs will then be analyzed using our predefined calculations to compute the metrics and determine the ranking of each planner. Rankings will be continuously updated on our website until the submission period ends, and the winner will be announced at the ICRA 2025 workshop.

## 👥 Who Should Participate?
Everyone is welcome to participate! Participants include, but are not limited to, researchers in robotics, AI, and autonomous systems; developers focusing on social navigation and dynamic path planning; and undergraduate or graduate students interested in testing how their planners perform in social scenarios.

**Note:** The planning approaches do not necessarily have to be specifically designed for social navigation. We are also interested in observing how classical navigation planners or other dynamic obstacle avoidance methods perform, as these approaches can sometimes prove more efficient.

## 📅 Timeline
- **Challenge Begins**: 01 April 2025  (AoE)
- **Submission Deadline**: 19 May 2025 (AoE)  
- **Winner Announcement**: 21 May 2025 (3pm ET)

## How to Participate

1. **Clone our repository** via [Arena-Rosnav](https://github.com/Arena-Rosnav).
2. **Download** the simulation environments at [Arena-Simulation-Setup](https://github.com/Arena-Rosnav/arena-simulation-setup).
3. **Develop** your navigation algorithm and test it locally on your computer.
4. <span style="color:red; font-weight:bold;">**Reach out to us so we can integrate it together!**</span>
5. **Upload** your code on your branch and make a pull request.

Note: You can continuously push updates until the submission deadline. On the day of the submission deadline, we will pull the latest version and run them on the worlds.



## 🏅 Leaderboard: Arena Challenge 2025

The leaderboard ranks participating teams based on their overall performance scores, considering completion time, collision penalties, and social compliance.

| **Rank** | **Team Name** | **Completion Time (s)** | **Collision Penalty** | **Social Compliance Score** | **Final Score** |
|----------|--------------|-------------------------|-----------------------|----------------------------|-----------------|
| 1        | DWB   | 120.5                   | 2.0                   | 0.95                       | 0.0076          |
| 2        | RosNAV (Ours)      | 135.2                   | 1.5                   | 0.90                       | 0.0065          |
| 3        | DWB        | 140.8                   | 3.0                   | 0.92                       | 0.0063          |
| 4        | Dragon  | 150.0                   | 4.0                   | 0.88                       | 0.0055          |
| 5        | Crowdnav++    | 160.3                   | 2.5                   | 0.85                       | 0.0052          |
| ...      | ...          | ...                     | ...                   | ...                        | ...             |


**Note**: The leaderboard will be **continuously updated** as teams submit and improve their solutions.

## 👥 Organizers

| ![Organizer 1](https://via.placeholder.com/150) | ![Organizer 2](https://via.placeholder.com/150) | ![Organizer 3](https://via.placeholder.com/150) |
|--------------------------------------------------|--------------------------------------------------|--------------------------------------------------|
| **Dr. Linh Kaestner**                            | **Dr. Alex Doe**                                 | **Prof. Jamie Lee**                              |
| Lead Organizer                                   | Technical Chair                                  | Research Advisor                                 |

| ![Organizer 4](https://via.placeholder.com/150) | ![Organizer 5](https://via.placeholder.com/150) |
|--------------------------------------------------|--------------------------------------------------|
| **Samim Ahmadhi**                                | **Jordan Smith**                                 |
| Program Manager                                  | Logistics Coordinator                            |



### 🎯 About the Organizers

- **Linh Kaestner**: Lead developer of the **Arena platform** and expert in simulation environments for social navigation.  
- **Alex Doe**: Specialist in dynamic robotics systems and advanced AI planning algorithms.  
- **Jamie Lee**: Advisor and mentor, contributing to research strategies and evaluation frameworks.  
- **Samim Ahmadhi**: Project manager overseeing timelines, communication, and partnership coordination.  
- **Jordan Smith**: Responsible for event logistics, communications, and participant support.
