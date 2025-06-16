# AI Agent Development with Google ADK in a Devcontainer

This repository provides a Python development environment using a Devcontainer, pre-configured for developing AI agents leveraging the Google ADK (presumably the Gemini API and related tools).

**Purpose:**

This devcontainer setup streamlines the development process for AI agents by providing a consistent and reproducible environment with all necessary dependencies and configurations.

**Usage:**

1.  Ensure you have Docker and VS Code (or another Devcontainer-compatible editor) installed.
2.  Clone this repository.
3.  Open the repository in VS Code.
4.  VS Code should prompt you to reopen the project in a Devcontainer. If not, use the "Remote-Containers: Reopen in Container" command.
5.  The Devcontainer will build automatically, installing the required Python packages and setting up the environment.
6.  Once the Devcontainer is running, you can start developing your AI agents.

**Details:**

*   The `.devcontainer/devcontainer.json` file configures the Devcontainer.
*   Python dependencies (e.g., the Google ADK library) are typically specified in a `pyproject.toml` file.  Make sure to install dependencies with use `poetry install`.

**Contributing:**

Contributions are welcome! Please submit pull requests with bug fixes, new features, or improvements to the documentation.