# Codespaces JavaFX

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-007396?style=flat-square&logo=java&logoColor=white)
![GitHub Codespaces](https://img.shields.io/badge/GitHub_Codespaces-000000?style=flat-square&logo=github&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A ready-to-run JavaFX Hello World application configured for GitHub Codespaces with a built-in virtual desktop environment.

## Overview

This project provides a minimal JavaFX application that runs entirely within GitHub Codespaces. It uses a devcontainer configuration with desktop-lite (noVNC) to render the JavaFX GUI directly in your browser -- no local Java or display setup required.

## Features

- **Zero-config JavaFX development** -- Works out of the box in GitHub Codespaces
- **Browser-based desktop** -- Renders the JavaFX GUI via noVNC virtual desktop
- **Pre-configured Java 21** -- Uses Azul Zulu JDK with JavaFX bundled
- **VS Code Java support** -- Includes the Java Extension Pack for IntelliSense, debugging, and more

## Prerequisites

- A [GitHub](https://github.com) account with access to [GitHub Codespaces](https://github.com/features/codespaces)

## Getting Started

### Installation

1. Click the green **Code** button on the repository page.
2. Select the **Codespaces** tab and click **Create codespace on main**.
3. Wait for the devcontainer to build and initialize.

### Usage

1. Once the Codespace is ready, open the integrated terminal.
2. Compile and run the application:
   ```bash
   javac HelloWorld.java && java HelloWorld
   ```
3. The virtual desktop preview (port `6080`) will open automatically in a Simple Browser tab. Click into it to see the JavaFX window with a "Say 'Hello World'" button.

## Tech Stack

| Technology | Purpose |
|---|---|
| Java 21 (Zulu FX) | Runtime and language |
| JavaFX | GUI framework |
| GitHub Codespaces | Cloud development environment |
| noVNC / desktop-lite | Browser-based virtual desktop |

## License

This project is licensed under the [MIT License](LICENSE).
