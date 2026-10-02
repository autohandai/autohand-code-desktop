<p align="center">
  <img src="assets/autohand.png" width="88" alt="Autohand logo" />
</p>

<h1 align="center">Autohand Code Desktop</h1>
<p align="center">A workspace for your favourite coding agents.</p>
<p align="center">
  <a href="https://github.com/autohandai/autohand-code-desktop/releases/latest"><strong>Download the latest release</strong></a>
  &nbsp; · &nbsp;
  <a href="https://github.com/autohandai/autohand-code-desktop/releases">Changelog</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/autohandai/autohand-code-desktop/issues/new/choose">Report an issue</a>
</p>

Bring Autohand, Codex, and Claude into one desktop workspace. Connect your agents, add a project, and start a conversation. Autohand Code CLI is included with the desktop app.

This is the **public home for downloads, release notes, and issues**. The application source is maintained privately. You do not need to clone this repository or build anything to use the app.

## Download

1. Open the [latest release](https://github.com/autohandai/autohand-code-desktop/releases/latest).
2. Expand **Assets** below the release notes.
3. Choose the installer for your computer:

| Your computer | Download | How to choose |
| --- | --- | --- |
| Mac with Apple Silicon | `Autohand-Desktop-…-arm64.dmg` | Apple M-series chips, including M1, M2, M3, and M4. |
| Mac with Intel | `Autohand-Desktop-…-x64.dmg` | An Intel processor listed in **Apple menu → About This Mac**. |
| Windows, 64-bit Intel or AMD | `Autohand-Desktop-…-x64.exe` | The Windows installer. |
| Linux, 64-bit Intel or AMD | `Autohand-Desktop-…-x86_64.AppImage` | A portable executable; no package manager required. |

On a Mac, **About This Mac** shows **Chip** for Apple Silicon or **Processor** for Intel. Choose the matching download.

The `.zip` files are macOS update packages. The `.yml`, `.blockmap`, and `.provenance.json` files support updates and build verification; they are not installers. GitHub's automatically generated **Source code** archives contain this distribution repository, not the desktop application.

## Install

### macOS

1. Open the `.dmg` you downloaded.
2. Drag **Autohand Desktop** into **Applications**.
3. Launch it from Applications and follow the setup guide.

The current release is not Apple-notarized. If macOS blocks its first launch, open **System Settings → Privacy & Security**, find the message for Autohand Desktop, and choose **Open Anyway**. Only do this for the installer downloaded from the releases linked above.

### Windows

Open the `.exe` and follow the installer. Launch **Autohand Desktop** from the Start menu. If Windows displays a publisher warning, check that the file came from this repository's release before continuing.

### Linux

Make the AppImage executable, then launch it. For example, from your Downloads folder:

```sh
chmod +x Autohand-Desktop-*-x86_64.AppImage
./Autohand-Desktop-*-x86_64.AppImage
```

Use the exact filename if you have downloaded more than one version.

## Your first project

The setup guide helps you connect an agent, choose your defaults, and add a project folder. You can use your existing Codex or Claude account, or sign in to Autohand. Your provider's account and usage limits still apply.

If you skipped setup, you can return to it from the app's settings. Add a project, start a new thread, and tell your agent what you want to build.

## Updates and changelogs

Every release includes its own changelog and installers for the supported platforms. Use **Check for Updates** in the app, or download a newer installer from [Releases](https://github.com/autohandai/autohand-code-desktop/releases).

Previously published installers may still point to the private update feed. If an older copy cannot check for updates, use the public release page to install the latest version. New builds will use this public repository's feed.

## Help us improve it

- [Report a bug](https://github.com/autohandai/autohand-code-desktop/issues/new?template=bug-report.yml): include your app version, operating system, agent, and steps to reproduce.
- [Suggest a feature](https://github.com/autohandai/autohand-code-desktop/issues/new?template=feature-request.yml): describe the workflow you want to improve.
- [Read the changelog](https://github.com/autohandai/autohand-code-desktop/releases): see what changed between releases.

Before posting, remove access tokens, private project paths, and sensitive conversation content from screenshots or logs.

---

[Autohand website](https://autohand.ai) · [Downloads](https://github.com/autohandai/autohand-code-desktop/releases/latest) · [Issues](https://github.com/autohandai/autohand-code-desktop/issues)
