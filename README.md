
# Epson Robot Final Code

This repository contains the final implementation code for the Epson robot, designed to perform three tasks:

1. **Task 1**: Pick and Place operation.  
2. **Task 2**: Stacking operation.  
3. **Task 3**: Integration task to record and write down the number of items counted.

## Table of Contents

1. [Overview](#overview)  
2. [Features](#features)  
3. [Installation](#installation)
4. [Division of Responsibilities](#Division-of-Responsibilities)
5. [Usage](#usage)  
6. [Project Structure](#project-structure)  
7. [Contributing](#contributing)  
8. [License](#license)

---

## Overview

This project demonstrates the capabilities of an Epson robot in automating pick-and-place, stacking, and item-counting tasks. The code is structured to provide seamless execution of all three tasks.

### Task Details

- **Task 1: Pick and Place**
  - The robot picks an object from a specified location and places it at a target location.
  
- **Task 2: Stacking**
  - The robot stacks objects in a predetermined order or pattern.

- **Task 3: Counting and Writing**
  - The robot integrates with a counting mechanism and records the count.

## Features

- Efficient and accurate pick-and-place operations.
- Robust stacking with error handling for alignment issues.
- Real-time integration for counting and data logging.
  
## Division of Responsibilities
- **Programming**: M11351016 田祖恩
- **Electrical Control**: M11351019 閻亭頤
- **Mechanical Design**: M11351018 蘇柔伊
- 
## Installation

### Prerequisites

- [Epson RC+ Software](https://www.epson.com/) (for robot programming and control).  
- A computer with the robot driver installed and connected.  
- Necessary hardware setup for the Epson robot.

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/robota3/Epson-Final-Code.git
   cd Epson-Final-Code
   ```

2. Open the project in Epson RC+ software:
   - Import the files into a new or existing project.

3. Ensure the hardware connections are set up and configured according to the robot's manual.

4. Compile and load the code onto the Epson robot.

## Usage

### Running Tasks

#### Task 1: Pick and Place
- Execute the pick-and-place code using:
  ```bash
  [Command/Procedure to execute Task 1]
  ```

#### Task 2: Stacking
- Run the stacking operation by loading the stacking program in Epson RC+.

#### Task 3: Counting and Writing
- Start the counting and writing program. Ensure the counting sensor/system is connected.

### Notes
- For optimal performance, ensure the workspace is clear and all objects are within the robot's range.
- Follow safety guidelines as per the Epson robot's manual.

## Project Structure

```
Epson-Final-Code/
├── Task1_PickPlace.src     # Pick and Place operation
├── Task2_Stacking.src      # Stacking operation
├── Task3_Counting.src      # Counting and integration task
├── README.md               # Project documentation
└── LICENSE                 # License file
```

## Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests with improvements or new features.

1. Fork the repository.  
2. Create a feature branch (`git checkout -b feature/task-name`).  
3. Commit your changes (`git commit -m 'Add Task improvement'`).  
4. Push to the branch (`git push origin feature/task-name`).  
5. Create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---
