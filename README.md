[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15276753&assignment_repo_type=AssignmentRepo)
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

<h3>#Solutions to Deliverables:</h3>

My OS is Windows 10. Setting up a developer environment on Windows 10 involves several steps to ensure that one has the necessary tools and configurations to efficiently develop software.The detail process of effective developer environment setup is hereby outlined.

For Git installation:
First, I visited the official Git website at https://git-scm.com/ and download the latest Git for Windows.
   - Next, I ran the downloaded installer (.exe file) and grant administrative privileges as needed.
   - During installation, I kept most settings as default but paid attention to choosing "Git from the command line and also from 3rd-party software" and "Use the OpenSSL library."
   - Finally, I completed the installation by clicking through the screens and finished the setup.
Setting up Git,
   - I opened Git Bash from the Start menu, which gives me access to the Git command-line interface.
   - To configure Git, I enter my username and email using commands like 'git config --global user.name "Fatimat Adebayo" and 'git config --global user.email "fattysocioscope.com"'.
Connecting to GitHub repository,
   - I signed up for a GitHub account at https://github.com/.
   - After logged in, I created a new repository on GitHub to push my local projects to.
   - In order to link my local Git repository to GitHub, I navigated to my project folder in Git Bash with 'cd FolderName', initialized Git with 'git init', added my GitHub repository as a remote with 'git remote add origin https://github.com/adeyus2024/GitDemo.git', and push my code to GitHub using 'git push -u origin master.
   - Finally, I verified that my code has been successfully pushed to GitHub by checking my repository on the GitHub website for the file.

Installation of a text editor - VS Code:
Downloading VS Code:
   - First, I navigated to the official Visual Studio Code website at https://code.visualstudio.com/.
   - Once there, I clicked on the download button to get the installer for Windows.
   - The download started automatically, and once it's completed, I located the downloaded file (in my Downloads folder).
Installing VS Code:
   - I double-clicked the downloaded installer to start the installation process.
   - A setup wizard opened up, and I followed the prompts.
   - During installation, I was asked to grant administrative permissions to complete the process.
   - Once the installation finished, I chose to launch VS Code immediately by checking the corresponding option before clicking "Finish."
Setting up VS Code:
   - Upon launching VS Code for the first time, I customized it to my preferences by installing extensions such as Python files, flutter/dart and other themes that suit me.
   - I explored the user interface and configure settings like fonts, key bindings, and integrated terminal preferences through the settings panel.
Integration of Git with VS Code:
   - I installed the Git extension from the Extensions Marketplace by clicking on the Extensions icon in the sidebar, searching for "Git," and installing it.
   - Finally, I tested it by opening a project folder by selecting "File" > "Open Folder" and begin writing and editing code in Visual Studio Code.

Downloading Python:
   - First, I visited the official Python website at https://www.python.org/.
   - On the homepage, I navigated to the Downloads section and click on the link to download the latest version of Python (3.12.64) for Windows 10.
   - The download started automatically, and once it's complete, I located the downloaded installer file (in my Downloads folder).
Installing Python:
   - I double-click the downloaded installer file to start the installation process.
   - A setup wizard opened up, and I ensured to check the box that says "Add Python to PATH" before proceeding with the installation.
   - I chose the installation type as "Install Now," which installed Python to the default location on my system.
   - During installation, I was asked to grant administrative permissions to complete the process.
   - Once the installation completed successfully, I closed the installer.
Setting up Python:
   - To verify that Python was installed correctly, I open the Command Prompt  and type 'python --version'. This command displays the installed Python version, confirming that Python is now accessible from the command line.
   
Setting Virtual Environment:
   - I set up a virtual environment for Python projects by using the 'venv' module. 
   - In the Command Prompt, I navigated to my project directory and create a virtual environment with 'python -m venv myenv'.
   - To start using the virtual environment, I activate it by running 'myenv\Scripts\activate' (for Command Prompt) 
   - Then, I can install Python packages using 'pip' within the virtual environment without affecting the global Python installation.

Download and installing of MySQL database on Windows 10:
   - First, I navigated to the official MySQL website at https://dev.mysql.com/downloads/.
   - On the downloads page, I scrolled to the MySQL Community (GPL) Downloads section.
   - Under MySQL Community Server, I clicked on the "Download" button for the MySQL Installer for Windows.
   - The download starts automatically, and once it’s complete, I located the downloaded installer file (in my Downloads folder).
Installing MySQL,
   - I double-click the downloaded installer file to launch the MySQL Installer.
   - In the MySQL Installer window, I chose the recommended settings.
   - In the product selection screen, I selected MySQL Server and other components I wanted to install, such as MySQL Workbench for a graphical user interface.
   - On the next screen, I reviewed the configuration details. Here, I can chose to configure MySQL Server as a Windows Service, set the root password, and adjust other advanced settings if needed.
   - I proceeded with the installation, and the installer downloads and installs the selected MySQL components. 
   - Once the installation is complete, I clicked on the "Next" button and then "Finish" to exit the installer.
Configuring MySQL,
   - To verify that MySQL Server is running, I opened MySQL Workbench from the Start menu.
   - In MySQL Workbench, I connected to the MySQL Server using the root account and the password I set during installation.
   - I also verified the MySQL Server status by opening a Command Prompt and running the command 'mysqladmin -u root -p status'. This command prompts for the root password and displays information about the MySQL Server status.


<h4> A reflection on the challenges faced during setup and strategies employed to overcome them </h4>
During my first Python installation completion, I tried to confirm by running 'python --version' in Git Bash, but the version that came out was the default by Windows (3.10.64), rather than my installed version of 3.12.64.
So, I made some research on Stack Overflow community on the way out.
I was directed to unistall the two python verions in the system control panel, and then re-install the latest version.
After following this direction, I ran python verion again in Git Bash to confirm successful installation.

Below is a screenshot of the two Python versions that I got listed using the command 'py -0'
![python version](https://github.com/Adeyus2024/se-assignment-1-setting-up-your-developer-environment-Adeyus2024/assets/171816141/5a2e323b-8f38-4abb-9c8a-1ffc9ed24d0d)



#Submission:
Submit your document and GitHub repository link thrgough the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
