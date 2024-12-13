 File Existence Checker

This repository contains a simple Node.js project that includes a GitHub Actions workflow to check if a specific file exists in the root directory of the repository. If the file exists, its content is displayed using the `cat` command. If the file does not exist, the workflow fails and returns an error.

## Workflow Overview

The project includes a GitHub Actions workflow that is triggered on every push to the `main` branch. The workflow performs the following steps:

1. **Checks if a specified file exists** in the root directory of the repository.
2. If the file exists, it outputs the file content using the `cat` command.
3. If the file does not exist, the workflow fails with an error message and terminates with a non-zero exit code.

### Workflow Features:
- Triggered on every push to the `main` branch.
- Checks for the existence of a file in the root directory.
- If the file exists, it displays its content in the workflow logs.
- If the file does not exist, it fails the workflow and outputs an error message.

## Getting Started

Follow these steps to set up the project locally:

### Prerequisites

You need to have the following installed on your local machine:
- **Git** (to clone the repository)

### Clone the Repository

To get started, clone the repository to your local machine:

```bash
git clone https://github.com/rafaelhueb92/github_actions_workflow_bash.git