[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15289055&assignment_repo_type=AssignmentRepo)

# Dev_Setup

Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
   Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

#Deliverables:

- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:\*\*

- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.

Answers to the above question

### Installing Visual Studio Code for my windows

1. To download VS Code Installer:

   - I first went to [Visual Studio Code website](https://visual studio for windows.com/).
   - Click on the download button for Windows.
   - Save the installer file (`VSCodeSetup-{version}.exe`) to your computer.

2. Run the Installer:

   - Double-click the downloaded installer file to start the installation process.
   - If prompted by User Account Control, click "Yes" to allow the installer to make changes.

3. Follow Installation Steps:

   - Click "Next" on the initial screen.
   - Accept the license agreement and click "Next".
   - Choose the default folder and click "Next".
   - Select additional tasks (e.g., adding to PATH) as needed and click "Next".
   - Click "Install" to begin the installation.
   - Wait for the installation to complete and then click "Finish".

4. Verify Installation:
   - Open VS Code by searching for it in the Start menu or desktop shortcut.

By following these steps i was able to successfully install Visual Studio Code on my system.

### Installing Python for my windows

1. To download Python Installer:

   - i went to the [Python official website](https://www.python.org/).
   - Navigate to the Downloads section.
   - Click on the latest version of Python for Windows (e.g., Python 3.10.0).
   - Scroll down to the Files section and download the Windows installer (`Windows installer (64-bit)` or `Windows installer (32-bit)` depending on your system).

2. Run the Installer:

   - Once downloaded, double-click the installer (`python-{version}.exe`) to start the installation process.
   - Check the box "Add Python {version} to PATH" and click "Install Now".

3. Verify Installation:

   - Open Command Prompt (cmd) or PowerShell.
   - Type `python --version` to verify that Python is installed and to check the version.

   Challenge face

   Path Configuration: Issues with adding Python to the system PATH, on my Windows.

   Troubleshooting Step

4. Path Configuration:
   I Manually add Python to PATH:
   - Right-click on "This PC" -> Properties -> Advanced System Settings -> Environment Variables.
   - Under System Variables, find PATH, and add `C:\Python{version}\`.

### Pip installation

     To download pip i navigate to vs code terminal and type the prompt pip install pandas.

     challenge face:
     i was unble to find it directly in the vs code extentions.

     Troubleshooting step:
     to solve the problem i navigated to vs code termital and type pip install and there i have successfully installed.

Certainly! Git Bash is a command-line interface for Git on Windows, providing a Unix-like shell experience. Here's a detailed guide to installing Git Bash, covering potential challenges and troubleshooting steps, with screenshots where applicable.

### Installing Git Bash windows

1. Download Git for Windows:

   - I went to the [Git for Windows official website](https://gitforwindows.org/).
   - Click on the download link to download the installer (`Git-2.xx.xx-64-bit.exe` for 64-bit system).

2. Run the Installer:

   - Double-click the downloaded installer file (`Git-2.xx.xx-64-bit.exe`) to start the installation process.
   - If prompted by User Account Control, click "Yes" to allow the installer to make changes.

3. Choose Installation Options:

   - I choose the default editor used by Git (usually leave as default).
   - Adjust PATH environment (choose "Git from the command line and also from 3rd-party software").
   - Choose HTTPS transport backend (leave as default).
   - Configure the line ending conversions (leave as default).
   - Choose the terminal emulator (use MinTTY recommended).
   - Choose the default behavior of the git pull command (leave as default).

4. Complete the Installation:

   - I click "Install" to begin the installation process.
   - Once completed, i click "Finish" to exit the installer.

   Verify Installation

5. Open Git Bash:

   - you can open it from the Start menu by searching for "Git Bash".

6. Verify Git Installation:
   - In Git Bash, type `git --version` to verify that Git is installed and to check the version.

By following these steps i was able to successfully install Git Bash on my Windows system.

### Installing MySQL Database for Windows

1. To download MySQL Installer:

   - i navigate to the [MySQL Community Downloads page](https://dev.mysql.com/downloads/mysql/).
   - Select the MySQL Community Server edition suitable for my Windows version(64bit os).
   - Click on the "Download" button to get the installer (`mysql-installer-web-community-{version}.exe`).

2. Run the Installer:

   - I Double-click the downloaded installer file (`mysql-installer-web-community-{version}.exe`) to start the installation process.
   - If prompted by User Account Control,i click "Yes" to allow the installer to make changes.

3. MySQL Installer Setup:

   - I choose "Developer Default" setup type for a typical development installation.
   - Click "Next" to proceed with installation.

4. Product Configuration:

   - Select MySQL Server and other components you want to install in my case i selected MySQL Workbench.
   - Click "Next" to continue.

5. Installation Process:

   - Review the summary of products and features to be installed.
   - I Click "Execute" to begin the installation process.

6. Complete Installation:
   - Once installation completes, i click "Next" and then "Finish" to exit the installer.

Challenges You Might Face

- Root Password Setup:\*\* Setting up the root password during installation.

  Troubleshooting Steps

1.  Root Password Setup:

- If you forget the root password, you can reset it using the MySQL server instance configuration wizard or by restarting MySQL in safe mode.

By following these steps i was able to successfully install MySQL database on your system and troubleshoot any issues that arise.
