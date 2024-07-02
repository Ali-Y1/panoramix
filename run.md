### Step 1: Install Poetry

First, you need to install Poetry if it's not already installed on your system. You can install Poetry through the recommended installer script:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

This command downloads and runs the installation script. Make sure to follow the post-installation instructions to ensure that Poetry's command is available in your shell.

### Step 2: Clone the Repository

If the package `panoramix-decompiler` is available in a Git repository, clone it:

```bash
git clone [repository-url]
cd panoramix-decompiler
```

Replace `[repository-url]` with the actual URL of the Git repository.

### Step 3: Install Dependencies

Inside the project directory, install the dependencies using Poetry:

```bash
poetry install
```

This command creates a virtual environment if one doesn't exist and installs all the dependencies listed in `pyproject.toml`.

### Step 4: Activate the Virtual Environment

To run commands using the project's dependencies, you should activate the virtual environment managed by Poetry:

```bash
poetry shell
```

This command activates the virtual environment, allowing you to run Python and other commands within the context of your project's dependencies.

### Step 5: Run the Package

Based on the `pyproject.toml` file you showed earlier, you can run the `panoramix` command, which is configured to execute the main function of the package:

```bash
panoramix
```

If you need to pass arguments or options, include them in the command line as needed.

### Step 6: Deactivate the Virtual Environment

When you're done, you can exit the virtual environment:

```bash
exit
```

This command will return you to your global shell, outside the Poetry managed environment.
