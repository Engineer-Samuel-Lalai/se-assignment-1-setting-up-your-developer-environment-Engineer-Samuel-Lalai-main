[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15237781&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment
ANSWERS FOR ASSIGNMENT. 
A SEPARATE FULL INFORMATION DOCUMENT IS ATTACHED TO IT
#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

<!-- 1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11 -->
   # **WINDOWS 11 DOWNLOAD AND  INSTALLATION **
1.	From the Start Menu Search any internet browser of your choice to open.
2.	Select the browser e.g. Google Chrome as shown below 
3.	From the search engine, search windows 11 download and load to open Microsoft website as shown https://www.microsoft.com/software-download/windows11.
5. If it’s an upgrade from windows 10 to 11, Select Windows 11 Installation Assistant and download. If it’s a new installation select download windows 11 disk image or create windows 11 disk media. 
6.  Open the setup and accept access request 
7. At the Windows 11 setup screen, select the Language, Time, and Keyboard Layout from the dropdown menus and select ‘Next’.
8. Select ‘Install now’.  
9. For a multiple Windows 11 version operating system media, select the type of Windows 11 operating system to install, then next and accept the license agreements. 
10. Choose the type of installation to perform. To upgrade to Windows 11 from an earlier version of Windows, select the “Upgrade” option below. To perform a clean OS installation, select “Custom: Install Windows only (advanced)” option below. (This option was selected below). 
11. Select the drive to install the operating system on from the list and select ‘Next’. The Windows 11 operating system will begin to install on the drive selected as shown below.
12. After the installation completes, the system should automatically reboot.  
13. When done after restarting select the prompts for the appropriate location, language keyboard type. Ignore the Wi-Fi connectivity selection if not connected and Type your preferred name and password to secure the device.
14. Choose the appropriate privacy settings and select ‘Next’ to finish. Welcome to windows 11.


<!-- 2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download -->

   # VISUAL STUDIO CODE INSTALLATION AND SETUP IN WINDOWS.
1.	First, download the relevant installer from https://code.visualstudio.com .The page with figure below will open. Select on the stable version drop down arrow and select one as per your operating system version i.e. Windows, Mac Os or Ubuntu. NB: VS code requires x64 bit version.  
2.	For the purpose of this installation I will use Windows.  
3.	Click Download and open the downloads folder for installation. Run the Setup as shown below. Accept the license aggrement and click ‘Next’.  
4.	Click next to Install in C:/    . On start menu name leave it as Visual Studio Code and click next
5.	On additional paths select Register code and Add to path.
6.	Click install to install VS code.  
7.	When done click finish as shown below and you are set. 

<!-- 3. **Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com** -->
   # GIT INSTALLATION PROCESS
1.	Open preferred search engine and search Git download as shown below. Select the link which directs to git homepage https://www.git-scm.com/downloads.  
2.	Under the downloads select the download as per your operating system. Fon now I will use Windows.  
3.	Select the version of your Operating System and download. 
4.	Go to to downloads and open the Git setup and open to install. Click next to proceed as shown below and next again to select System folder C:/           
5.	Under Select Components, leave the default as shown below. For menu folder name Git:      
6.	For default editor leave Vim as default. For initial new repository, set as let Git decide      
7.	For path environment select the recommended and click ‘Next’. For SSH select bundled open SSH      
8.	Follow prompts shown  
9.	Click Install and the installation process will continue as shown. When done click Finish.

# GITHUB ACCOUNT
1.	Open the search engine of your choice and search github as shown below. Hover to github website and open https://github.com/ . Select Sign up to open a new account or Sign in to log in to your account if already created.
2.	 For new account enter your email address on the link provided below and press continue. 
4.	Create a password   
5.	Enter User name  
6.	Pass the Robot test and verify account to proceed and finish. When done Click sign in to log in.
7.	Enter Email and Password to sign in in the prompted window as shown below.  
8.	When done on the right corner click on the button and select your repository to create a new repository. Then, click New to open a new repo as shown below. 
9.	Under Repository name, write your preferred name for your repo e.g. FirstCommit, Add a description (Optional) to remind you in future of the content. Click Create Repository as shown below. Select Public (if to be viewed by everyone) or private (if for only you). 
10.	Congratulations for creating your first Commit

# COMMITTING FIRST REPOSITORY
# INITIALIZING FIRST COMMIT IN GITHUB REPOSITORY USING GIT
1.	Under Start menu, Search for Git Bash and open as administrator. 
2.	Type cd ‘directory id’ to open the folder you want to open. E.g. cd h: /
3.	Create a folder in the disk to save content by using mkdir ‘folder name eg sample’. mkdir sample
4.	Open the created folder as shown below by sample: cd sampleFile 
NB: from main folder the other folders will follow like h/…/.././././sampleFile		 
5.	Install the various extensions required like python and virtual environment using the following commands.
Install pip by first running the following command in git bash or powershell. 
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
Then: Run; py get-pip.py
6.	After installing pip then install python and virtual environment using the following commands.
py –m pip install python  	or 	py –m pip install python  
py –m pip install virtualenv 	or 	py –m pip install virtualenv
7.	When done check versions to confirm if installed fully. 
pip –version
python –version
Virtualenv --version 
8.	In the folder created, initialize git by: git init
9.	Create a file e.g. index.py by: 	vim index.py	or vim README.md
10.	Opens notepad, press i to start INSERT command for typing in file. When done press Esc, followed by 	: wq to save and quit the file.
11.	Check for status of file by: git status ‘you will find the files created’.
12.	Add all files to commit by: git add .
13.	Link git to user account to create repository by adding username as shown: 
git config –global user.name “YourUserName”
14.	Link the email address registered with account: git config –global user.email “YourEmail”
15.	Run: git commit –m “My First Commit”  NB: inside the “ ” put the message to pass 
16.	Run: git fetch (This fetches the repository created so as to commit and push/save file to it) Open the repository and copy the link for the repository eg. git remote add origin https://github.com/..../FirstCommit.git
17.	 Run: git push –u origin master NB: If the origin name is not master but main you need to change to main to push
18.	Open Github and refresh to check if updated. Done

<!-- 4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
5. Install Package Managers:
   If applicable, install package managers like pip (Python). -->
# PYTHON INSTALLATION
1.	Open the preferred search engine and type the url for python website http://www.python.org to open.  
2.	Click on Downloads. Select Download Python (Select latest version) as shown below. 
3.	Open the downloaded setup form the downloads folder and install. Select Use Admin priviledges  and Add python to PATH. 
4.	 When done click close

<!-- 6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html -->
   # MySQL INSTALLATION FOR DATABASE
1.	Open Preferred Search engine e.g. Google Chrome, Mozilla Firefox, Microsoft edge etc. and search MySQL download as shown below.
2.	Select Download from the MySQL website to link https://dev.mysql.com/downloads/installer.  
3.	Select the latest version and operating system, in this case windows. Select the second option with more size to download. On the MySQL homepage, Click on the “No thanks, just start my download” link to proceed MySQL downloading.
4.	From downloads in your computer open the MySQL setup and install. The installer will instruct you to choose the setup type. For most users, the “Developer Default” is suitable. Click “Next” to proceed
5.	Check Requirements
7.	Click next to download the files and execute.  
8.	Proceed to “Product Configuration” > “Type and Networking” > “Authentication Method” Pages by clicking the “Next” button. Create a password for the MySQL root user. Ensure it’s strong and memorable. Click “Next” to proceed. 
9.	Once done select the workbench and Shell to install and complete the installation. Click Finish.  
10.	Search MySQL Command Line on start menu to check if fully installed. Open and put the root password to open.

<!-- 7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them. -->


#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
