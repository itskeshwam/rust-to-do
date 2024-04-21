# Rust To-Do List

This is a simple to-do list program written in Rust. It allows users to add, list, mark as done, and remove tasks.

## Features

- **Add Task**: Add a new task to the to-do list.
- **List Tasks**: Display all tasks in the to-do list.
- **Mark Task as Done**: Mark a task as completed.
- **Remove Task**: Remove a task from the to-do list.

## Requirements

- Rust Programming Language
- Cargo (Rust's package manager)

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/todo-list.git
   ```

2. Navigate to the project directory:

   ```bash
   cd todo-list
   ```

3. Build the project:

   ```bash
   cargo build --release
   ```

## Usage

1. Run the executable:

   ```bash
   ./target/release/todo-list
   ```

2. Follow the prompts to perform various actions such as adding tasks, listing tasks, marking tasks as done, or removing tasks.

## File Structure

- `main.rs`: Entry point of the program.
- `storage.rs`: Module responsible for tasks serialization and deserialization.
- `tasks.rs`: Module containing functions for adding, listing, marking, and removing tasks.
- `Cargo.toml`: Dependency configuration file.
- `tasks.json`: JSON file storing the tasks.

## Contributing

Contributions are welcome! If you have any ideas for improvements or find any bugs, feel free to open an issue or submit a pull request.


