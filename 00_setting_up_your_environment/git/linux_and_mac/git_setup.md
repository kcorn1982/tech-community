# Setting up git on Linux and Mac

## Install Git on Linux

1. Update your default packages. `sudo` is a command that allows you to run programs with the security privileges of another user (by default, as the superuser). You will need `sudo` access to install Git.

### Note

The the following instructions assume you are using a Debian based Linux distribution and have `sudo` access. The `sudo` command stands for "superuser do". It allows a permitted user to execute a command as the superuser or another user, as specified in the sudoers file. If you are using a different distribution or do not have `sudo` access, you may need to adjust the commands accordingly. Similarly, on macOS, the instructions assume you have administrative rights to install Homebrew and Git.

```bash
sudo apt-get update
```

2. Install Git.

```bash
sudo apt-get install git
```

3. Verify the installation.

```bash
git --version
```

You should see the version of the installed Git.

## Install Git on macOS

1. Open Terminal.

2. Check if Git is already installed.

```bash
git --version
```

If Git responds with a version, you have it already installed. If not, proceed to the next step.

3. Install Homebrew. Homebrew is a package manager for macOS that will help you install Git. If you have Homebrew already installed, you can skip this step.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### _Note_

[Homebrew](https://brew.sh/) is a free and open-source software package management system that simplifies the installation of software on Apple's macOS operating system and Linux.

Homebrew takes care of downloading, unpacking, and installing the software and manages all the dependencies that come with it.

In short, Homebrew is a powerful tool that helps macOS users to manage and install software packages easily. It's like a Linux package manager, but for macOS.

4. Install Git using Homebrew.

```bash
brew install git
```

5. Verify the installation. 

```bash
git --version
```

You should see the version of the installed Git.
