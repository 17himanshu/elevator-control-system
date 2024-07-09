# Elevator Control System

This project implements a digital system design for an elevator control system using Verilog. The elevator operates over 3 floors and prioritizes requests based on the direction (up and down). The design incorporates a Moore Machine and features async reset, motor control for elevator movement, door control, and a display screen showing the current floor number.

## Features

- **Three Floors**: Operates on 3 different floors.
- **Request Prioritization**: Handles and prioritizes requests based on up and down movements.
- **Motor Control**: Manages the movement of the elevator motor.
- **Door Control**: Controls the opening and closing of the elevator door.
- **Floor Display**: Displays the current floor number on a screen.
- **Async Reset**: Includes an asynchronous reset feature.
- **Moore Machine**: Utilizes a Moore state machine for design logic.

## File Structure

- `elevator_machine.v`: Verilog code for the elevator control system.
- `elevator_machine_tb.v`: Testbench for verifying the elevator control system.
- `state-diagram.jpg`: State diagram that depicts the complete flow of tghe process

## Getting Started

### Prerequisites

- **Verilog Simulator**: A Verilog simulation tool like ModelSim or any other preferred simulator.
- **Text Editor**: Any text editor or IDE that supports Verilog, such as VS Code with Verilog extensions.

### Simulation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/17himanshu/elevator-control-system.git
    cd elevator-control-system.git
    ```

2. **Open Verilog Files**:
    Open `elevator_machine.v` and `elevator_machine_tb.v` in your Verilog simulator or text editor.

3. **Run the Simulation**:
    Use your Verilog simulator to run `elevator_machine_tb.v` to simulate and verify the functionality of the elevator control system.

## Design Overview

The elevator control system is implemented as a Moore Machine with states representing different actions such as moving up, moving down, opening doors, and closing doors. The system also includes logic to prioritize requests based on the direction of movement and handle asynchronous resets to ensure reliability.

### State Diagram

![State Diagram][WhatsApp Image 2024-07-09 at 12 18 41_4bb27352](https://github.com/17himanshu/elevator-control-system/assets/96365482/8e5d369d-6c27-4dc4-aac2-bce3df8eb37a)


## Future Enhancements

- Adding more floors.
- Implementing more sophisticated request handling algorithms.
- Integrating sensors for precise control.
- Enhancing the display with more information.

