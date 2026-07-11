# EmbyTemplatev2

A standardized, automation-ready repository template for rapidly scaffolding Emby Server plugins. 

## Features
* **Zero-Configuration Scaffolding**: Uses automated GitHub Actions to rename namespaces, solution files, and projects instantly upon repository creation.
* **Modern Solution Format**: Powered by the lightweight `.slnx` solution format.
* **Pre-configured Git Hooks**: Holds native hooks locally inside the `.git/hooks/` folder to maintain coding patterns and repository standards.

## How to Instantiate a New Plugin

This template is completely automated via the cloud. You do not need to use `dotnet new` or run local renaming commands.

1. Click the green **Use this template** button at the top of this GitHub page.
2. Select **Create a new repository**.
3. Name your repository using your new plugin's name (e.g., `Emby.Plugin.MyCoolFeature`).
4. Click **Create repository**.

### What happens in the background:
GitHub will instantly spin up a cloud action, read your repository name, and automatically update your folder paths, `.csproj`/`.slnx` filenames, and C# namespaces to match perfectly.

5. Open **GitHub Desktop** and clone your brand new repository down to your computer.
6. Launch the solution file inside `src/` and start coding immediately!