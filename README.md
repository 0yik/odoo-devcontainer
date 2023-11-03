# Odoo DevContainer

Odoo DevContainer is a development environment specifically designed for working with Odoo, an open-source business management software. It provides a pre-configured setup that includes all the necessary tools and dependencies for Odoo development.

With Odoo DevContainer, developers can easily set up their development environment without worrying about installing and configuring dependencies manually. It offers a consistent and isolated environment, ensuring that the development process remains smooth and efficient.

Some key features of Odoo DevContainer include:

- 🐳 Docker-based: It utilizes Docker containers to provide a consistent and reproducible environment across different systems.
- 🛠️ Pre-installed dependencies: It comes with all the necessary dependencies, such as Python and Odoo itself, already installed and configured.
- 🛠️ VSCode Ready: Just clone and start with the Remote - Containers extension.
- 📦 Customization: Developers can easily customize their DevContainer setup to match their specific development requirements.
- 💻 Easy collaboration: With DevContainer, developers can easily share their development environment setup with others, ensuring consistent development across the team.

Overall, Odoo DevContainer simplifies the setup and management of the development environment for Odoo developers, allowing them to focus more on building and customizing Odoo applications.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed on your system:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker](https://www.docker.com/products/docker-desktop)
- [Remote - Containers extension for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

## Quickstart

- Clone the repository:
```sh
git clone https://github.com/0yik/odoo-devcontainer.git
```
- Open the project in VSCode.
- Run the Dev Containers: Open Folder in Container... command from the Command Palette (F1) or quick actions Status bar item, and select the project folder odoo-devcontainer.
- The VS Code window will reload and start building the dev container. A progress notification provides status updates. You only have to build a dev container the first time you open it; opening the folder after the first successful build will be much quicker.
- After the build completes, VS Code will automatically connect to the container.