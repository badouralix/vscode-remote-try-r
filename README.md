# Try Out Development Containers: R

[![Github Actions Buildx](https://github.com/badouralix/vscode-remote-try-r/actions/workflows/buildx.yaml/badge.svg)](https://github.com/badouralix/vscode-remote-try-r/actions/workflows/buildx.yaml)
[![Docker Pulls](https://img.shields.io/docker/pulls/badouralix/vscode-remote-try-r?label=pulls&logo=docker&logoColor=white)](https://hub.docker.com/r/badouralix/vscode-remote-try-r)
[![Docker Stars](https://img.shields.io/docker/stars/badouralix/vscode-remote-try-r?label=stars&logo=docker&logoColor=white)](https://hub.docker.com/r/badouralix/vscode-remote-try-r)
[![Docker Image Version (latest by date)](https://img.shields.io/docker/v/badouralix/vscode-remote-try-r?logo=docker&logoColor=white)](https://hub.docker.com/r/badouralix/vscode-remote-try-r)
[![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/badouralix/vscode-remote-try-r?label=size&logo=docker&logoColor=white)](https://hub.docker.com/r/badouralix/vscode-remote-try-r)

This is a sample project that lets you try out the **[VS Code Remote - Containers](https://aka.ms/vscode-remote/containers)** extension in a few easy steps.

> **Note:** If you're following the quick start, you can jump to the [Things to try](#things-to-try) section.

- [Setting up the development container](#setting-up-the-development-container)
- [Things to try](#things-to-try)
- [License](#license)

## Setting up the development container

Follow these steps to open this sample in a container:

1. If this is your first time using a development container, please follow the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).

2. To use this repository, you can either open the repository in an isolated Docker volume:

    - Press <kbd>F1</kbd> and select the **Remote-Containers: Open Repository in Container...** command.
    - Type [`badouralix/vscode-remote-try-r`](https://github.com/badouralix/vscode-remote-try-r) and press <kbd>return</kbd>.
    - Wait for the container to start, and try things out!

    ![**Remote-Containers: Open Repository in Container...**](https://user-images.githubusercontent.com/19719047/82132333-f9efd600-97de-11ea-9572-e761a97e25b9.png "Remote-Containers: Open Repository in Container...")

    Or open a locally cloned copy of the code:

    - Clone this repository to your local filesystem.
    - Open the cloned copy of this folder.
    - Press <kbd>F1</kbd> and select the **Remote-Containers: Reopen in Container** command.
    - Wait for the container to start, and try things out!

    ![**Remote-Containers: Reopen in Container**](https://user-images.githubusercontent.com/19719047/82131929-b98e5900-97da-11ea-868b-7542abd17a27.png "Remote-Containers: Reopen in Container")

## Things to try

Once you have this sample opened in a container, you'll be able to work with it like you would locally.

Some things to try:

1. **Edit:**

    - Open [learnxinyminutes.R](learnxinyminutes.R).
    - Try adding some code and check out the language features.

2. **Terminal:** Press <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>\`</kbd> and type `uname` and other Linux commands from the terminal window.
3. **R Interactive:**

    - Press <kbd>F1</kbd> and run the **R: Create R terminal** command.
    - Try running some R commands.

4. **Run Source:**

    - Open [learnxinyminutes.R](learnxinyminutes.R).
    - Press <kbd>F1</kbd> and run the **R: Run Source**.

    ![**R: Run Source**](https://user-images.githubusercontent.com/19719047/82131092-f1dd6980-97d1-11ea-89bb-1bfdd19e98cc.png "R: Run Source")

5. **Run Selection:**

    - Open [learnxinyminutes.R](learnxinyminutes.R) and select a few lines.
    - Press <kbd>F1</kbd> and run the **R: Run Selection/Line** command.

    ![**R: Run Selection**](https://user-images.githubusercontent.com/19719047/82131094-f6a21d80-97d1-11ea-89e3-0d72239f3a34.png "R: Run Selection")

6. **Preview Dataframe:**

    - Open [learnxinyminutes.R](learnxinyminutes.R) and select a data frame, for instance `students`.
    - Press <kbd>F1</kbd> and run the **R: Preview Dataframe** command.

    ![**R: Preview Dataframe**](https://user-images.githubusercontent.com/19719047/82505461-156c2100-9afe-11ea-90b4-42672d269173.png "R: Preview Dataframe")

## License

Unless explicitly stated to the contrary, all contents licensed under the [MIT License](LICENSE).
