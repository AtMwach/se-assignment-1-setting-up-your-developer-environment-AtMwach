[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15281120&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
   -In order to achieve succesful installation I carefully followed the directives under the above link which were as follows:
   - Check for compatibility
   - Download the Media Creation Tool
   - Run the Media Creation Tool
   - Accept the licensing agreement
   - Choose what to keep
   - Choosing a suitable location and finally commencing the download which launches to the outstanding Windows 11.
   - Navigation of the interface to familiriase myself more.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   -I downloaded the Visual Studio Code installer from the above link selecting 64 bit since that is compatible to my system. 
   -I ran the installer and followed the prompts to install the software.
   -I launched Visual Studio Code and familiarized myself with the interface, exploring the various features on how to create a file type, launching the vs from git bash succesfully and extensions available like prettier, codeium, live server just to name a few that make make coding both fun and enjoyable.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
   -I downloaded the Git installer from the official Git website https://git-scm.com/downloads
   -I ran the installer and followed the prompts to install the software.
   -I launched Git Bash and configured my username and email using the commands git config --global user
   -I created a GitHub account and initialized a Git repository for my project using the command git init
   -I made my first commit using the command git add . and git commit -m "Initial
   commit"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
  -I downloaded the Python installer from the official Python website https://www.python.org/downloads/
  -I ran the installer and followed the prompts to install the software.
  -I launched Python from the command line and verified that it was installed correctly by running the command
  python --version

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
   -I installed pip by running the command python -m ensurepip
   -I verified that pip was installed correctly by running the command pip --version
   -I installed necessary packages using pip install command

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
   -I downloaded the MySQL installer from the above link
   -I ran the installer and followed the prompts to install the software.
   -I launched MySQL from the command line and verified that it was installed correctly by running the command
   mysql -u root -p
   -I created a new database and a new user using the commands CREATE DATABASE database_name and CREATE
   -I configured the database connection using the necessary configuration files and environment variables.
   -I tested the database connection using a Python script.
   -I created a new table using the command CREATE TABLE table_name (column1 datatype, column
   2 datatype, ...)
   -I inserted data into the table using the command INSERT INTO table_name (column1, column
   2, ...) VALUES (value1, value2, ...)
   -I queried the data using the command SELECT * FROM table_name
   -Just to name a few of the functionalities that I undertook in understanding MYSQL well.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
   -I explored the extensions available in Visual Studio Code and installed the following extensions: Prettier
   -Codeium, Live Server, Python, and MySQL extensions to enhance my coding experience.
   -I configured the extensions to work seamlessly with my project, including setting up code formatting, linting, and syntax highlighting.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
    -I documented my setup process in a markdown file, including the steps I took to install and configure each tool, as well as any troubleshooting steps I encountered along the way.
    -I included screenshots and code snippets to illustrate the process and make it easier for others to follow.

    Challenges faced.
    -I faced challenges in setting up the MySQL database, including configuring the database connection and creating a new user.
    -I encountered issues with installing some of the extensions in Visual Studio Code, which required troubleshooting and after the troubleshoot process they worked seamlesly.
    -I had to spend some time learning the basics of MySQL and how to interact with it using
    Python.
    -I had to troubleshoot some issues with the Python interpreter and pip, which required
    reinstalling Python and pip.




#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
