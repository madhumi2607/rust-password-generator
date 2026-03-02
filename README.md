# Rust Password Generator CLI

A simple command-line password generator built using Rust.
This tool generates secure random passwords directly from the terminal.

## Features

* Generate random secure passwords
* Custom password length
* Uses Rust's random number generation
* Simple CLI interface

## Project Structure

rust-password-generator
│
├── Cargo.toml
├── Cargo.lock
└── src
    └── main.rs

## Installation

Clone the repository:

git clone https://github.com/madhumi2607/rust-password-generator.git

Move into the project directory:

cd rust-password-generator

Build the project:

cargo build

## Usage

Run the program and specify the password length:

cargo run 12

Example output:

Generated Password: A8@kT2!Lm9Pq

## Example Commands

Generate a 10 character password:

cargo run 10

Generate a 16 character password:

cargo run 16

## Technologies Used

* Rust
* Cargo (Rust package manager)

## Future Improvements

* Option for special characters toggle
* Option for uppercase/lowercase control
* Copy password to clipboard
* Save generated passwords

## Author

Madhu
Engineering Student | Software Development Enthusiast
