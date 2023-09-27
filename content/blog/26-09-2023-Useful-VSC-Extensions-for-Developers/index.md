---
title: "Useful VSC Extensions for Developers"
date: 2023-09-26T09:08:06+08:00
draft: false
tags: ["tools", "developers", "tech", "vsc"]
categories: ["tech"]
authors:
  - Michael Lu
---

Welcome to my first blog!

After much contemplation and deliberation, I've decided to kickstart this blog with content that can prove beneficial to fellow developers. Please note that the tools and extensions mentioned here are presented in no particular order of importance or priority.

> The majority of the content in this blog has been composed or enhanced with the assistance of Chat-GPT, often guided by initial text snippets or prompts. Admittedly, I'm not a fan of writing myself! 😅

## 1. Code Spell Checker and Prettier - Code formatter

Need I say more? These two extensions are an absolute necessity for every developer to ensure proper standardized code formatting and spelling.

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) is a code formatter that ensures consistent and clean code styling across your projects. With Prettier, you no longer need to spend time manually aligning code or fixing indentation issues. It automatically formats your code as you type, saving you valuable development time and ensuring code uniformity among team members.

Typos and spelling errors can sneak into your code, leading to unexpected bugs and issues. [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) is a helpful extension that scans your code for spelling mistakes and provides suggestions for corrections. This ensures that your code is not only error-free but also maintains a professional and polished appearance.

### Extras:

- [isort (Python import sorter)](https://marketplace.visualstudio.com/items?itemName=ms-python.isort)

- [Sort JSON objects](https://marketplace.visualstudio.com/items?itemName=richie5um2.vscode-sort-json)

- [Sort lines](https://marketplace.visualstudio.com/items?itemName=Tyriar.sort-lines)

- [ChatGPT Community](https://chat.openai.com/c/328f1e14-1ccf-4e88-bc62-b01040e04041)

## 2. GitLens

[GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) is a must-have extension for Visual Studio Code that takes your Git experience to the next level:

- **Rich Git Insights**: Gain real-time insights into your Git repositories, including commit history and authorship details, directly in your code.

- **Time Travel**: Effortlessly navigate commit histories, explore changes made over time, and understand code evolution.

- **Interactive Rebase**: Streamline your Git workflow with interactive rebase support, allowing you to easily reorder, edit, and squash commits, enhancing code history management.

- **Code Annotations**: See commit and blame annotations within your code, providing context for code changes and collaboration.

- **Code Lens Integration**: Seamlessly integrates with Code Lens for Git blame, history, and more.

- **Efficient Code Reviews**: Simplify code reviews with pull request and issue links, enhancing team collaboration.

With GitLens, you not only gain comprehensive insights into your Git repositories but also improve code history management through interactive rebasing. It's an indispensable tool for developers looking to enhance their Git workflow within Visual Studio Code

## 3. Console Ninja and Error Lens

![Console Ninja Demo](./img/ConsoleNinja.gif)

[Console Ninja](https://marketplace.visualstudio.com/items?itemName=WallabyJs.console-ninja) displays console.log output and runtime errors directly in your editor from your running browser or node application. It brings clarity to your debugging process, making it easier to identify and address issues in your code.

[Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens) is your ally in detecting and resolving errors within your codebase. It highlights problematic lines, such as compiler errors or warnings, directly in your code. With Error Lens, you can swiftly spot issues and take corrective actions, ensuring cleaner, error-free code.
GitLens enhances code understanding and collaboration, making it essential for Git-based projects in Visual Studio Code.

## 4. Ai Code Assistant

AI code assistants have become indispensable tools for developers, offering advanced coding assistance and productivity boosts. Here, we explore three prominent AI code assistants:

- [GitHub Copilot](https://github.com/features/copilot/)

- [TabNine](https://www.tabnine.com/)

- [IntelliCode](https://visualstudio.microsoft.com/services/intellicode/).

## 5. Bracket Pair Colorization Toggler and Indent Rainbow

![Bracket Pair Colorization Demo](./img/BracketPair.gif)

![Indent Rainbow Demo](./img/RainbowIndent.png)

Gone are the days of struggling to decipher your code's indentation and bracket pairings. Thanks to [Bracket Pair Colorization Toggler](https://marketplace.visualstudio.com/items?itemName=dzhavat.bracket-pair-toggler), you can now effortlessly identify matching brackets. Additionally, [Indent Rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow) provides clear visual cues for your current indentation level. These extensions simplify code comprehension and enhance your coding experience.

### Extras:

- [Evondev - Indent Rainbow Palettes](https://marketplace.visualstudio.com/items?itemName=evondev.indent-rainbow-palettes)

## 6. Peacock

![Peacock Demo](./img/Peacock.png)

If you've ever juggled multiple repositories in Visual Studio Code and found yourself perplexed by which window belongs to which project, [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock) comes to the rescue. This extension allows you to personalize the color of each Visual Studio Code window, making it effortless to distinguish them by their distinct hues. Say goodbye to confusion and streamline your workflow by quickly identifying and navigating your projects with ease, all thanks to Peacock.

## 7. Auto Close Tag and Auto Rename Tag

[Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag) and [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag) are invaluable extensions that streamline the development process by simplifying tag creation and renaming. They prove especially helpful when dealing with renaming tags separated by extensive lines of code.

One minor inconvenience with Auto Close Tag is that it generates the closing tag next to the opening tag when creating a new one. This causes a slight disturbance when you want to wrap a portion of text in a new tag. You will need to manually relocate it to the desired position at the end of your content.

For example:

```HTML
<p>
  Below are the text that I want to wrap in a bold tag:
  ---example text to be wrapped in a bold tag---
</p>
```

```HTML
<p>
  Below are the text that I want to wrap in a bold tag:
  <b></b><= closing b tag automatically generated and needs to be
  manually moved
</p>
```

## 8. Color Highlight

![Color Highlight Demo](./img/ColorHighlight.png)

[Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight) is a small convenient extension that simplifies color management in your code. It automatically detects and highlights color codes in CSS, SASS, LESS, and more, providing real-time color previews.
