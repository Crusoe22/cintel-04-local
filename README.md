# cintel-04-local

## Set up the Project

### Commands

Commands are operating system-specific.
These commands are for Windows users.
On Mac/Linux, generally use `python3` instead of `py`.
Edit your README.md to reflect the commands that work on your machine.

### Verify Installations

1. Open project folder in VS Code.
2. Open a new terminal - on Windows, ensure the terminal type is PowerShell (not the old cmd)
3. Run the following commands in the terminal one at a time to verify installations.

```shell
py --version
git --version
git config user.name
git config user.email
```

## Python Project Virtual Environment

Run the following commands in the terminal to set up a project virtual environment and install the necessary packages.
Run them from the root project folder (e.g. pyshiny-penguins-dashboard-express).
Use PowerShell on Windows or the terminal on macOS and Linux.

### Create a Project Virtual Environment (generally one-time setup)

Create a project virtual environment in the .venv folder of the project root directory.

  ```shell
  py -m venv .venv
  ```
