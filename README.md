[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244549&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5

## Installation and Navigation of Visual Studio Code (VS Code)

### Questions&Answers:

1. **Installation of VS Code:**

   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

     **Prerequisites:**

     - A laptop/PC with a working Windows 10/11.
     - A working internet connection.

     **Steps:**

     1.1. **Open Chrome:**

     - Open the Chrome browser.
       
     1.2. **Search for VS Code:**
     
     - Type "VS Code download" in the search bar.
     
     1.3. **Locate the Official Website:**
     
     - Enter the official Visual Studio Code website (usually `code.visualstudio.com`).
     
     1.4. **Download VS Code:**
     
     - Click on the download button that looks like this: <img src="https://imgur.com/LaAkHTQ.png">.

     1.5. **Run the Installer:**
     
     - Locate the downloaded file in your Downloads folder.
     - Double-click the installer file to start the installation.

     1.6. **Install VS Code:**
        - Agree to the terms and conditions.
        - Follow the installation prompts by clicking "Next" until the installation starts.
          
     1.7. **Complete Installation:**
        - Let the installation run until it finishes.
        - Exit the installation window.

2. **First-time Setup:**

   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

     **Steps:**

     2.1 **Open Extensions Sidebar:**

     - Press `Ctrl+Shift+X` to open the Extensions sidebar.
       2.2 **Install Prettier:**
     - In the search bar under "EXTENSIONS", type "Prettier".
     - Click the "Install" button to install the Prettier extension.
       2.3 **Install Other Essential Extensions:**
     - Repeat the process for other extensions like "Python" or "Live Server".

3. **User Interface Overview:**

   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

     **Components:**

     - **Activity Bar:**
       - Located on the far left, it provides quick access to different views like Explorer, Search, Source Control, Run and Debug, and Extensions.
     - **Side Bar:**
       - Displays the contents related to the selected view from the Activity Bar, such as files in the Explorer.
     - **Editor Group:**
       - The central area where you open and edit files. You can open multiple files in tabs.
     - **Status Bar:**
       - Located at the bottom, it shows information like errors, warnings, the current Git branch, and the current line/column of the cursor.

4. **Command Palette:**

   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

     **Explanation:**

     - The Command Palette is a powerful tool that allows you to access all commands available in VS Code.
     - **Accessing the Command Palette:**
       - Press `Ctrl+Shift+P` or `F1`.
     - **Examples of Tasks:**
       - Opening files (`File: Open`).
       - Changing the color theme (`Preferences: Color Theme`).
       - Installing extensions (`Extensions: Install Extensions`).

5. **Extensions in VS Code:**

   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

     **Role:**

     - Extensions enhance the functionality of VS Code, allowing you to customize your development environment.
     - **Finding and Installing Extensions:**
       - Open the Extensions sidebar with `Ctrl+Shift+X`.
       - Search for extensions by name or functionality.
       - Click "Install" to add an extension.
     - **Managing Extensions:**
       - Use the Extensions sidebar to enable, disable, or uninstall extensions.
     - **Examples for Web Development:**
       - **Prettier:** Code formatter.
       - **ESLint:** JavaScript linter.
       - **Live Server:** Launch a local development server with live reload.
       - **Debugger for Chrome:** Debug JavaScript in Chrome.

6. **Integrated Terminal:**

   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

     **Opening the Integrated Terminal:**

     - Press `` Ctrl+`  `` (backtick) or go to `View > Terminal`.
     - You can open multiple terminal instances and switch between them.
       **Advantages:**
     - Direct integration with your code editor, allowing you to run commands and see results without switching windows.
     - Supports various shells (PowerShell, Command Prompt, Git Bash, etc.).

7. **File and Folder Management:**

   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

     **Creating Files/Folders:**

     - Right-click in the Explorer sidebar and select `New File` or `New Folder`.
       **Opening Files/Folders:**
     - Use `File > Open File` or `File > Open Folder`.
     - Drag and drop files/folders into the VS Code window.
       **Navigation:**
     - Use the Explorer sidebar to browse directories.
     - Use `Ctrl+P` to quickly open files by typing their names.
     - Use `Ctrl+Tab` to switch between open files.

8. **Settings and Preferences:**

   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

     **Accessing Settings:**

     - Go to `File > Preferences > Settings`.
     - **Changing Theme:**
       - Go to `File > Preferences > Color Theme` or use the Command Palette (`Ctrl+Shift+P`), then type `Color Theme`.
     - **Changing Font Size:**
       - Search for "Font Size" in the settings and adjust the value.
     - **Changing Keybindings:**
       - Go to `File > Preferences > Keyboard Shortcuts` or use the Command Palette and type `Preferences: Open Keyboard Shortcuts`.

9. **Debugging in VS Code:**

   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

     **Steps:**

     9.1. **Open the Debug Sidebar:**

     - Click on the Debug icon in the Activity Bar or press `Ctrl+Shift+D`.
       9.2. **Configure Debugger:**
     - Click on the gear icon to configure the launch.json file.
     - Select the appropriate environment (e.g., Node.js, Python).
       9.3. **Set Breakpoints:**
     - Click in the gutter next to the line numbers in your code.
       9.4. **Start Debugging:**
     - Click the green play button in the Debug sidebar or press `F5`.
       **Key Features:**

     - Breakpoints, Step Over, Step Into, Step Out, Watch variables, Call stack inspection.

10. **Using Source Control:**

- How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

  **Integrating Git with Command Prompt:**

  10.1. **Initialize a Repository:**

  Open the integrated terminal in VS Code:

  - Press `Ctrl+` (backtick) or go to `View > Terminal`.

  In the terminal, navigate to your project directory if you aren't already there:

  ```
  cd path/to/your/project
  ```

  Initialize a new Git repository:

  ```
  git init
  ```

  10.2. **Making Commits:**

  Stage changes:

  - To stage all changes:
    ```
    git add .
    ```
  - To stage specific files:
    ```
    git add filename1 filename2
    ```

  Commit the staged changes:

  ```
  git commit -m "Your commit message"
  ```

  10.3. **Pushing Changes to GitHub:**

  Ensure you have a remote repository on GitHub:

  - Create a new repository on GitHub and copy the repository URL.

  Add the remote repository URL:

  ```
  git remote add origin https://github.com/yourusername/your-repository.git
  ```

  Push the changes to the remote repository:

  ```
  git push -u origin main
  ```
