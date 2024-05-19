# Coding Problems CLI

Welcome to the Coding Problems CLI! This project is a command-line interface application written in Rust that allows users to explore and solve various coding problems. It offers an interactive experience where users can browse through a list of problems, select one to view its details, and see the corresponding solution.

## Purpose

The purpose of this project is to provide a simple and interactive way for users to practice coding problems directly from their terminal. It aims to be a useful tool for both beginners and experienced programmers who want to enhance their problem-solving skills.

## Features

- **Welcome Message**: Users are greeted with a friendly welcome message upon starting the CLI.
- **Problem Listing**: Displays a list of available coding problems, sorted in numerical order.
- **Interactive Selection**: Users can select a problem using arrow keys or by typing the number.
- **Problem Details**: Shows the description and solution of the selected problem, including the code and inputs.

## Getting Started

### Prerequisites

- Rust programming language: Ensure you have Rust installed on your machine. You can download it from [rust-lang.org](https://www.rust-lang.org/).

### Installation

1. Clone the repository:
   ```sh
   git clone git@github.com:rubenVillalvazo/coding_problems.git
   cd coding_problems
   ```
2. Build the project:
   ```sh
   cargo build
   ```

### Usage

1. Run the CLI application:
   ```sh
   cargo run
   ```
2. Follow the on-screen instructions to navigate through the list of problems and view their solutions.

### Example

```sh
$ cargo run
Welcome to the Coding Problems CLI!
Available Problems:
1: Given a list of numbers and a number k, return whether any two numbers from the list add up to k.
Select a problem to view:
   > 1: Given a list of numbers and a number k, return whether any two numbers from the list add up to k.

   Problem 1: Given a list of numbers and a number k, return whether any two numbers from the list add up to k.
   Solution: Found a pair!
```

### Contributing

Contributions are welcome! If you have any suggestions for new problems or improvements to the existing code, feel free to open an issue or submit a pull request.

### Adding New Problems

1. Define the problem structure and solution in src/problems.rs.
2. Add the new problem to the all_problems function.
3. Implement the solution function for the new problem.

### License

This project is licensed under the MIT License. See the LICENSE file for more details.

### Acknowledgements

- Inspired by various coding challenge platforms and the desire to practice coding problems in a Rust environment.
