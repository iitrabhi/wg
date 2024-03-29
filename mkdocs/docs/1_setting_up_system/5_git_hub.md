### Setting Up and Using Git

#### Setting Up Git:
##### **Create a Git Account**:
-  Visit [GitHub.com](https://github.com/) and sign up for an account.
- Complete the registration process by providing your details.
2. **Download and Install Git Desktop**:
	###### Part 1: Installing GitHub Desktop which looks like this. 
	![](attachments/Screenshot%202024-03-13%20at%207.46.08%20PM.png)
	- You can install GitHub Desktop on any supported operating system. For more information, see "Supported operating systems for GitHub Desktop."
	- To install GitHub Desktop, navigate to https://desktop.github.com/ and download the appropriate version of GitHub Desktop for your operating system. Follow the prompts to complete the installation. For more information, see "Installing GitHub Desktop."
	###### Part 2: Configuring your account
	- If you have an account on GitHub or GitHub Enterprise, you can use GitHub Desktop to exchange data between your local and remote repositories.
		###### **Creating an account**
	- If you do not already have an account on GitHub.com, create one now. For more information, see [Create git account](5_git_hub.md)
		###### **Authenticating to GitHub**
	- To connect to GitHub Desktop with GitHub, you'll need to authenticate your account. For more information, see "Authenticating to GitHub in GitHub Desktop." 
	- After authenticating your account, you are ready to manage and contribute to projects with GitHub Desktop.
	###### Part 3: Configuring Git
	 - You must have Git installed before using GitHub Desktop. If you do not already have Git installed, you can download and install the latest version of Git from https://git-scm.com/downloads.
	![](attachments/Screenshot%202024-03-13%20at%207.44.31%20PM%201.png)
	 - After you have Git installed, you'll need to configure Git for GitHub Desktop. For more information, see "Configuring Git for GitHub Desktop."
	###### Part 4: Customizing GitHub Desktop
	- You can adjust defaults and settings to tailor GitHub Desktop to your needs.
	**Choosing a default text editor**
	- You can open a text editor from GitHub Desktop to manipulate files and repositories. GitHub Desktop supports a variety of text editors and integrated development environments (IDEs) for Windows and macOS. You can choose a default editor in the GitHub Desktop settings. For more information, see "Configuring a default editor in GitHub Desktop."

3. **Login to GitHub Desktop**:
    

#### Creating a Repository Using a Template:

1. **Search for a Template Repository**:
    
    - In your web browser, go to GitHub and search for the user `iitrabhi`.![](attachments/Screenshot%202024-03-13%20at%208.03.44%20PM.png)
    - Find the repository named `project-template`.![](attachments/Screenshot%202024-03-13%20at%208.04.22%20PM.png)
2. **Use the Template**:
    
    - Click on `Use this template`.![](attachments/Screenshot%202024-03-14%20at%205.41.59%20AM.png)
    - Go to create repository. ![](attachments/Screenshot%202024-03-14%20at%205.43.25%20AM.png)
    - Give your new repository a name and set it to a private repository.![](attachments/Screenshot%202024-03-14%20at%205.43.38%20AM.png)
1. **What is a Repository?**:
    
    - A repository, often abbreviated as repo, is a storage space where your project lives. It can contain folders and files, images, videos, spreadsheets, and data sets - anything your project needs.

#### Basic Git Terminology:

- **Commit**: Recording changes to the repository. Think of it as taking a snapshot of your current project state.
- **Stash Changes**: Temporarily shelving (or stashing) changes you've made to your working directory so you can work on something else.
- **Pull**: Updating your local repository to match the newest version in the remote repository.
- **Push**: Sending your committed changes to a remote repository.
- **Clone Repository**: Making a copy of a remote repository to your local machine.
- **Fetch Origin**: Fetching changes from the remote repository without merging them into your local repository.

#### Adding Collaborators:

1. **Go to Repository Settings**:
    - In your GitHub repository, click on `Settings`.![](attachments/Screenshot%202024-03-14%20at%205.47.11%20AM.png)
2. **Add Collaborators**:
    - Navigate to `Collaborators`.![](attachments/Screenshot%202024-03-14%20at%205.47.30%20AM.png)
    - Click on `Add People` and enter their GitHub usernames.![](attachments/Screenshot%202024-03-14%20at%205.47.45%20AM.png)
	- Type the name of collaborator. ![](attachments/Screenshot%202024-03-14%20at%205.48.05%20AM.png)
	- You will find this dialogue on the page. Your work is done.![](attachments/Screenshot%202024-03-14%20at%205.48.25%20AM.png)
#### Workflow Reminder:

- Always remember to `fetch origin` and `pull` before you start working on your local repository.
- Before `pushing` your changes, ensure your local repository is up to date with the remote repository to avoid conflicts.