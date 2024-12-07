[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15328987&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
Since you've chosen Windows 11, ensure your system meets the minimum requirements and proceed with installation from the official Microsoft website.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   Download and install Visual Studio Code (VS Code):
- Go to [Visual Studio Code Download Page](https://code.visualstudio.com/Download).
- Download the installer suitable for Windows.
- Run the installer and follow the installation instructions.

4. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
Install Git and configure it:
- Download Git from [git-scm.com](https://git-scm.com/download/win).
- Run the installer, ensuring to select appropriate options (e.g., adjusting PATH environment, line ending configurations).
- Open Git Bash to configure your username and email:
  ```bash
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"
  ```
- Create a GitHub account at [github.com](https://github.com).
- Initialize a Git repository for your project:
  ```bash
  mkdir myproject
  cd myproject
  git init
  ```
- Make your first commit:
  ```bash
  echo "# My Project" >> README.md
  git add README.md
  git commit -m "Initial commit"
  ```
- Create a repository on GitHub and push your local repository to GitHub:
  ```bash
  git remote add origin https://github.com/yourusername/myproject.git
  git push -u origin master

5. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
- Download Python from [python.org](https://www.python.org/downloads/windows/).
- Run the installer and ensure to add Python to PATH during installation.
- Verify installation by opening a command prompt and typing `python --version`.


6. Install Package Managers:
   If applicable, install package managers like pip (Python).
For Python, install pip:
- Ensure pip is installed by default with Python (newer versions).
- Upgrade pip if needed:
  ```bash
  python -m pip install --upgrade pip
  ```

7. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Install MySQL:
- Download MySQL Installer from [dev.mysql.com](https://dev.mysql.com/downloads/windows/installer/).
- Run the installer and choose MySQL Server and other components you need (e.g., MySQL Workbench).
- Follow the installer instructions to complete the installation.

8. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
Consider using Docker for virtualization:
- Download Docker Desktop from [docker.com](https://www.docker.com/products/docker-desktop).
- Install Docker Desktop and follow the setup instructions.

9. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
In VS Code, explore extensions:
- Open VS Code and navigate to Extensions (Ctrl+Shift+X).
- Search for and install extensions relevant to your workflow (e.g., Python, MySQL, Docker).

10. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
Create a comprehensive document:
- Use a text editor to document each step, configurations made, and any troubleshooting steps encountered.
- Include screenshots where necessary to illustrate configurations and setups.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.
Document: Detailed setup process with step-by-step instructions and screenshots.
- GitHub Repository: Include a sample project initialized with Git, with necessary configuration files like `.gitignore`.
- Reflection: Provide insights on challenges faced and strategies employed during setup.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
