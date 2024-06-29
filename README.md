# -PLPBasicGitAssignment-
##  Document the steps and commands used in a text file or in the README of your repository.
 ### GitHub Repository Creation
  - Log in to your GitHub account
 ### Create a new repository on GitHub
  - I clicked on the "+" (plus) sign icon in the top right corner of GitHub homepage and selected "New repository" from the dropdown menu.
  - Entered a name for my repository. For example, "PLPBasicGitAssignment".
  - Optionally, provide a description for my repository to give others a brief idea of what it’s for.
  - I initialize the repository with a README file by checking the box next to "Initialize this repository with a README". This adds a README.md file to your repository, which is useful for providing information about your project.
 ### Initialize it with a README file
  - By initializing the repository with a README file, you create an initial placeholder document that can include project details, instructions, or documentation.
  - The README.md file is typically written in Markdown format, which allows you to format text, add headings, lists, links, and images easily.
 ### Create Repository
  - After filling out the necessary details and selecting the options, click on the "Create repository" button to finalize the creation of your GitHub repository
## Connecting to GitHub
 ### Get the Repository URL from GitHub
  - Go to your GitHub repository my-repo.
  - Click on the green "Code" button. This will reveal a dropdown with a URL.
  - Copy the URL provided. It should look something like https://github.com/your-username/my-repo.git.
 ### Link Your Local Repository
  - Open your terminal or command prompt.
  - Navigate to the directory of your local repository using cd path/to/your/repository.
  - Use the git remote add command to add a remote named origin (conventionally used for the default remote repository in Git) with the URL you copied earlier:
  git remote add origin https://github.com/your-username/my-repo.git
 ### Verify the Remote
  - To verify that the remote is set correctly, you can use
  - This command will list all the remotes associated with your repository. You should see origin listed with the URL you just added.
  - Now, your local repository is linked to your GitHub repository under the name origin. You can proceed to push your local changes to GitHub using git push -u origin main (assuming your main branch is named main; replace main with master if that's the case for your repository).
## Create a File
 ### Navigate to Your Local Repository
  - Open your terminal or command prompt.
  - Use the cd command to navigate to the directory where your local repository is located. For example cd path/to/your/repository
 ### Create a New Text File
  - Inside your repository directory, create a new text file named hello.txt. You can do this using a text editor or directly from the command line
  - echo Hello, Git! > hello.txt 
 ### Add Content to hello.txt:
  - Open hello.txt with a text editor and add the following text
  - Hello, Git!
  - Save the file.
  - That's it! You have now created a new text file (hello.txt) inside your local repository and added the text "Hello, Git!" to it.
  To commit the changes you made to hello.txt in your local Git repository, follow these steps:
 ### Stage the Changes
  - First, you need to stage the changes you made to hello.txt so that Git is aware of them and ready to commit them.
  - git add hello.txt
  - This command adds hello.txt to the staging area, which prepares it for the next commit.
 ### Commit the Changes
  - Once the changes are staged, you can commit them along with a commit message that describes what changes you made.
  - git commit -m "Add hello.txt with a greeting"
  - -m "Add hello.txt with a greeting": This part of the command adds a commit message. It's important to provide a clear and concise message that explains the purpose of the commit.
  - After running these commands, your changes to hello.txt will be committed to your local Git repository. Remember, committing changes locally does not automatically push them to your remote repository on GitHub. If you want to update your GitHub repository with these changes, you would need to use git push after committing.
## Pushing to GitHub
 ### Commit Changes:
  - Before pushing, you should commit your changes locally using git commit -m "Your commit message".
 ### Push to Remote: 
  - The git push command uploads your committed changes from your local branch to the remote repository (origin).
 ### Set Upstream Branch:
  - The -u option establishes a tracking relationship between your local branch and the remote branch. After setting this up once, you can simply use git push and git pull without specifying the remote and branch every time.
 ### Branch Name:
  - Specify the branch name (main in this case) that you want to push to on the remote repository. This branch should already exist on GitHub.
## Verify on GitHub
  - Visit GitHub Repository
  -Locate Repository typically in the format https://github.com/username/repositor
  - View Commits Look for a tab or link named "Commits" or "Code". Click on it to see the list of commits made to the repository.
  - Verify Commit Message and File In the list of commits, find the most recent one that corresponds to your hello.txt file change. Each commit message is usually displayed along with the changed files. Ensure that
  - File Content Check







