# First Time Local Development Setup

This is a README to get started with our community, and most development projects using Github, Python3, JavaScript and/or Docker. It also includes our standard tools we use to test our code effectively. Your tools are what make you go 10 times as fast as a developer, so don't skimp. You will understand your code and other people's code quicker.

Oh boy. Get ready. You will install a lot of stuff. Fortunately you only have to do this once.

# Community

[Sign up for our Solvestack Slack](https://join.slack.com/t/solvestack/shared_invite/zt-9l9a253a-uCsIlUe8Gz4fllRGmEa~pw)

👋 See you there! We'll guide you during the meetup or with literally ANY question you have about coding. We like to help each other get unstuck.

# Dictionary

Local machine: your physical laptop or desktop you're using right meow.

Terminal (uses a shell):
* Plain English (PE): Text only application present on all computers that lets you type some commands to run other programs. Executes after hitting the enter key, and usually provides text output responses. Mac/Linux default application: Terminal, Windows default application: Powershell
* Jargon you should eventually know (JUSEK): there is a difference between a shell and a terminal. Exit codes.

CLI:
* Plain English: program you type in a terminal. It usually has required and/or optional arguments
* JUSEK: Command Line Interface

Code Repository ("Repo" for short):
* Plain English: a magical codebase folder that is like Google Drive / One Drive on steroids for developers, with a lot more granular of version control
* JUSEK: Distributed source control

IDE:
* Plain English: Fancy code editor (like a text editor). IDEs increase programmer productivity by combining common activities of writing software into a single application: editing source code, provides sexy syntax highlighting and auto complete, compiling or building, and debugging.
* JUSEK: Integrated Development Environment

# 0 - Git and Github Intro

Git is the CLI and software run to keep track of code as it changes between versions and collaborators.

Github is the remote repository source control website that hosts the code. Developers push new code changes to the repository and pull down from the repository using the Git CLI from their local machine [physical laptop or desktop].

# 0.1 - Github

1. [Sign up for a Github account](https://github.com/signup) if you don't have one.

2. Send your Github Username and your email address you signed up for Github with to one of the Solvestack mentors so you can be added to the Solvestack Github organization.

3. [Create a Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)

4. Accept your email invitation or notification to join the team `@py101-students`


# 0.2 - Git

## Mac Users

1. Install Git
 
Open your Terminal Application and run the following command:

```bash
sudo xcodebuild -license accept
```

XCode comes on Mac preinstalled, and it already includes Git as a toolkit.

2. Install Homebrew if you haven't yet:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Install gh CLI.

```bash
brew install gh
```

4.  Open a new Terminal window, and run the following to log into Github locally from your terminal.

```shell
gh auth login
```

This will ask you a series of questions to answer by using the arrow keys and the return key.

**What account do you want to log into?** Github.com

**What is your preferred protocol for Git operations?** HTTPS

**Authenticate Git with your Github Credentials?** Yes

**How would you like to authenticate Github CLI?** Paste an authentication token

**Paste your authentication token** _Proceed to copy the key using the copy icon from your developer settings area, then right-click the  powershell window to paste. It will show up as a bunch of asterisks:_ \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*


## Windows Users

1. [Install Git for Windows](https://git-scm.com/download/win). This includes Git Bash.
<!--2. Open Powershell, then run:

```shell
winget install --id GitHub.cli
```
This will install gh CLI.

Press "y" key to accept the agreement.

3. Open a new Powershell window, and run the following to log into Github locally from your Powershell terminal.

```shell
gh auth login~-->
```

This will ask you a series of questions to answer by using the arrow keys and the return key.

**What account do you want to log into?** Github.com

**What is your preferred protocol for Git operations?** HTTPS

**Authenticate Git with your Github Credentials?** Yes

**How would you like to authenticate Github CLI?** Paste an authentication token

**Paste your authentication token** _Proceed to copy the key using the copy icon from your developer settings area, then right-click the  powershell window to paste. It will show up as a bunch of asterisks:_ \*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*


# 1.0 - Docker

The following link will give steps on how to install Docker on each OS type.

[Install Docker](https://www.docker.com/get-started)

Make sure to start Docker Desktop if it's not running! It looks like a whale icon in the notification area.

# 2.0 - Install Python 3

The following link will give steps on how to install Python 3 on each OS type.

[Install Python 3](https://installpython3.com/)

# 3.0 - Install NVM

Node Version Manager is useful to use different versions of Node.js for different projects.

The following section will give steps on how to install Node.js, NPM, and yarn.

[Install NVM - Windows](https://github.com/coreybutler/nvm-windows#installation--upgrades)
[Install NVM - Mac/Linux](https://github.com/nvm-sh/nvm#install--update-script)

Then run:

```bash
nvm install 14
nvm use 14
npm install -g yarn
```

# 4.0 - Install Visual Studio Code (VSCode)

VSCode (not to be confused with Visual Studio), is a very simple IDE (translation: editor) with powerful extensions that make stuff really easy. You open your code files and edit the documents.

The following link will give steps on how to install VSCode:
[Install VSCode](https://code.visualstudio.com/)

# 5.0 - Install DBeaver

DBeaver is a free database manager and browser. Using DBeaver can look at your data your programs are producing very quickly.

The following link will give steps on how to install DBeaver:

[Install DBeaver](https://dbeaver.io/download/)

# 6.0 - Install Postman

Postman is an API testing tool. It helps us send requests and receive responses from our locally running server (and other servers on the web too!).

The following link will give steps on how to install Postman:

[Install Postman](https://www.postman.com/downloads/)
