# MathWorks Minidrone Competition 2024 - India


### Competition: India 2024 | Indian Institute of Science, Bangalore  
This project is a submission for the **MathWorks Minidrone Competition 2024**, where we developed an **autonomous minidrone line follower** using **Model-Based Design** techniques. The goal of the competition was to build a simulation-based solution that could be extended to a real-world application.

## Project Overview

In this project, we focused on **Round 1: Simulation**, which involved developing algorithms for:
- **Path Planning**
- **Image Processing**
- **Control Systems**

Our approach centered around the use of the **Bresenham's Line Algorithm** for efficient path drawing and image processing.
## Simulation Environment 

![path](https://github.com/user-attachments/assets/d2693442-3106-4a62-9f04-9982e61eee7e)

Line following algorithm based on [Bresenham's line algorithm](https://en.wikipedia.org/wiki/Bresenham%27s_line_algorithm) and circle detection with brute force technique.


<br><br>

<div float="left" align="center">
  <img src="https://github.com/koraykzly/parrotMinidroneCompetition/blob/main/example_gifs/bresenham.gif" alt="bresenham" 
    width="180" height="140"/>
  <img src="https://github.com/koraykzly/parrotMinidroneCompetition/blob/main/example_gifs/output1.gif" alt="output1"
    width="180" height="140"/>
  <img src="https://github.com/koraykzly/parrotMinidroneCompetition/blob/main/example_gifs/output2.gif" alt="output2"
    width="180" height="140"/> 
</div>

## Key Features
- **Path Planning**: Used Bresenham’s line algorithm for determining optimal paths in the drone's field of view.
- **Image Processing**: Leveraged the Computer Vision Toolbox for detecting and following the line in simulation.
- **Control Systems**: Designed control strategies to guide the minidrone along the detected path.
  
## Tools and Technologies
- **MATLAB & Simulink**
- **Computer Vision Toolbox**
- **Bresenham’s Line Algorithm**: Implemented to approximate straight lines for the line-following feature.
- **Model-Based Design**: Developed simulation models for path planning and control.

## Algorithm Description: Bresenham's Line Algorithm
Bresenham’s line algorithm is a rasterization algorithm used to determine the pixels that form a straight line between two points. It’s efficient due to the use of only integer addition, subtraction, and bit-shifting operations, making it computationally inexpensive. We also implemented the **midpoint circle algorithm** to detect circular shapes that might be encountered during path planning.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/minidrone-line-follower.git
   ```
2. Open MATLAB and navigate to the project directory.
3. Open the Simulink model `minidrone_line_follower.slx`.
4. Run the simulation to observe the minidrone following the line in the virtual environment.

## Future Work
- Real-time implementation on a physical minidrone.
- Improved obstacle detection using advanced image processing techniques.
- Enhanced control systems for dynamic environments.

## Contributors
- Vishal - Team Leader
- Jaswanth
- Rohit Tanga
- Rohan titus






