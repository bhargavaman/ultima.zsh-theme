# ultima.zsh-theme — Theme and Settings for Z Shell

---

![item zsh prompt](https://github.com/egorlem/021011/blob/main/demos/zsh-theme-demo-min.png?raw=true)

---

## Features

- **Multi-Line Prompt**: The prompt is divided into three lines for better readability. The first line separates the previous command's output from the prompt, the second line provides detailed path information, and the third line is for input.
- **Multiple Prompt Levels**: Provides configurations for secondary and tertiary prompt levels (`PS2` and `PS3`).
- **SSH Status Indicator**: Displays an indicator when an SSH connection is established.
- **VCS (Version Control System) Integration**: Supports Git, SVN, and Mercurial for showing branch and repository status directly in the prompt.
  - **Git Integration**: Shows branch name, staged and unstaged changes, and untracked files.
  - **SVN and Mercurial Integration**: Shows branch name and repository status.
- **Completion Enhancements**: Provides advanced completion settings, including menu completion, caching, and various completion styles and formats.
- **LS_COLORS Configuration**: Configures `LS_COLORS` for both BSD and GNU systems to enhance the display of directory listings.
- **LESS and MAN Configuration**: Customizes the behavior and appearance of `less` and `man` pages.

These features make the `ultima.zsh-theme` a powerful and versatile theme for Z shell users, enhancing both functionality and aesthetics.

---

## **Installation**

### **[Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh)**

1. Clone the repository:

```shell
git clone https://github.com/bhargavaman/ultima.zsh-theme
```

2. Link file to oh-my-zsh's theme folder:

```shell
ln ~/path-to-cloned-folder/ultima.zsh-theme/ultima.zsh-theme ultima.zsh-theme
```

3. Go to your `~/.zshrc` file and set `ZSH_THEME=ultima`

---

## **Recommended settings and compatibility**

### Fonts

Not all fonts contain U+203a unicode unless your system supports **Single Right-Pointing Angle Quotation Mark** install one of the standard fonts on your system. For example **Arial**, **Consolas**, **Impact**.

For comfortable work, I usually use [JetBrains Mono](https://www.jetbrains.com/lp/mono/).
The font is already available characters that are used in the theme and are ideal for full compatibility.

---

## Contribution Guide

We welcome contributions to improve `ultima.zsh-theme`! Here’s how you can help:

### How to Contribute

1. **Fork the Repository**: Click the "Fork" button at the top right of this repository to create a copy of the repository on your GitHub account.

2. **Clone Your Fork**: Clone the forked repository to your local machine using the following command:

    ```bash
    git clone https://github.com/<your-username>/ultima.zsh-theme.git
    ```

    Replace `<your-username>` with your GitHub username.

3. **Create a Branch**: Create a new branch for your changes:

    ```bash
    git checkout -b feature/your-feature-name
    ```

    Replace `your-feature-name` with a descriptive name for your feature or fix.

4. **Make Changes**: Make your changes to the codebase. Ensure your code follows the project's coding standards and conventions.

5. **Commit Changes**: Commit your changes with a descriptive commit message:

    ```bash
    git add .
    git commit -m "Add feature: your feature description"
    ```

6. **Push Changes**: Push your changes to your forked repository:

    ```bash
    git push origin feature/your-feature-name
    ```

7. **Open a Pull Request**: Go to the original repository and click the "New Pull Request" button. Select your branch from the dropdown and create the pull request. Provide a clear and detailed description of your changes.

### Reporting Issues

If you find any bugs or have feature requests, please open an issue on the GitHub repository. Provide as much detail as possible to help us understand and resolve the issue.

### Getting Help

If you need any help, feel free to reach out by opening an issue or starting a discussion in the repository.

---

## License

This project is licensed under the **Do What The F*ck You Want To Public License**. See the [LICENSE](https://github.com/egorlem/ultima.zsh-theme/blob/f8a01d549ee38e720a597f9632ccf7960c7b9c8e/LICENSE) file for details.

---

Original by [Egor Lem](https://egorlem.com/)
Modified by me [Aman Bhargava](https://links.bhargavaman.com/)
