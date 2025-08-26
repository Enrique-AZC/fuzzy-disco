# Interactive Web Terminal Simulation

## Abstract
This project implements an interactive **web-based terminal simulation** using only **HTML, CSS, and JavaScript**.  
It reproduces the aesthetics of a retro command-line interface, while also incorporating a password-protected login system and a set of custom commands that simulate different functionalities.  
The purpose of this project is to explore user interaction design in a constrained text-based environment, combining playful narrative elements with technical implementation.

## Objectives
The main goals of the project are:
1. To design a **terminal-like user interface** in a web browser using standard web technologies.
2. To implement a **basic authentication system** that restricts access through a predefined password.
3. To simulate **command execution** and provide textual responses, mimicking a real CLI.
4. To create a modular and extensible structure for adding new commands.
5. To analyze how interactive retro-style interfaces can enhance user engagement.

## Features
- **Password-based access**: Users must enter the correct password to access the terminal.
- **Custom command set**: Includes predefined commands such as:
  - `help` → Displays available commands.
  - `./start` → Simulates the initialization of a time machine.
  - `clear` → Clears the terminal screen.
- **Typing animation** for output, enhancing immersion.
- **Retro-style design**: Green text on a black background, blinking cursor, and monospace font.

## Implementation Details
- **HTML**: Provides the structural layout of the login screen and terminal environment.
- **CSS**: Defines the retro aesthetic, including the color scheme, blinking cursor, and typography.
- **JavaScript**: Manages user interaction, password validation, command parsing, and simulated typing effects.

## Requirements
- A modern web browser (Chrome, Firefox, Edge, Safari).  
- No additional libraries or frameworks are required.

## Installation & Usage
1. Clone or download this repository.
2. Open the `index.html` file in a browser.
3. Enter the predefined password to unlock the terminal.
4. Type `help` to see the list of available commands.

```bash
git clone https://github.com/your-username/web-terminal-simulation
cd web-terminal-simulation
