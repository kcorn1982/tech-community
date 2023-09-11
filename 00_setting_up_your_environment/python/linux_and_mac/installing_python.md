# Installing Python on Mac & Linux

## Installing Python on macOS

### 1. Installing from the official Python website

1. **Visit the Python Downloads Page**
   - Go to [Python's official download page](https://www.python.org/downloads/).

2. **Download the macOS Installer**
   - Click on the "Download Python x.x.x" button for macOS (where x.x.x is the latest version).
   - This will download the macOS installer package.

3. **Run the Installer**
   - Navigate to your downloads folder and double-click on the downloaded `.pkg` file.
   - Follow the on-screen instructions to complete the installation.

4. **Verify Installation**
   - Open a new Terminal.
   - Type `python3 --version` and press Enter. You should see the version of Python you installed.

## Installing Python on Linux

### 1. Installing using the package manager


1. **Open a Terminal**

2. **Update package lists**

   ```bash
   sudo apt update
   ```

3. **Install Python**

   ```bash
   sudo apt install python3
   ```

4. **Verify Installation**

   ```bash
   python3 --version
   ```

You should see the version of Python you installed.

## 3. Installing via Visual Studio Code (VSCode) on Linux & Mac

### Prerequisites:

- Ensure you have Visual Studio Code installed. If not, download it from [VSCode's official website](https://code.visualstudio.com/).

1. **Open VSCode**
   - Launch Visual Studio Code.

2. **Install the Python Extension**
   - Go to the Extensions view by clicking on the square icon on the sidebar or pressing `Ctrl+Shift+X`.
   - Search for "Python" and install the one published by Microsoft.

3. **Open the Command Palette**
   - Press `Ctrl+Shift+P` to open the command palette.

4. **Install Python using the Command Palette**
   - Type "Python: Select Interpreter" and select it from the dropdown.
   - If no Python interpreter is found, you'll be prompted to install one. Click on "Install" when prompted.

5. **Verify Installation**
   - Open a new terminal in VSCode by clicking on `Terminal > New Terminal`.
   - In the terminal, type `python --version` and press Enter. You should see the version of Python you installed.