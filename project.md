## Step By Step Tutorial

### How to Set Up Git
1. Make sure you download and install the latest version of Git.
2. Set your username in Git.
3. Set your commit email address in Git.

### Authenticating Github from Git
When you are connecting to a Github repository from Git, an authentication is need with Github using HTTPS or SSH. If you clone with HTTPS, you can cache your Github password in Git using a helper. The helper will provide a step by step tutorial on how to connect it together.

### Collaborating wih More than One Person
1. Go to Github and click the "+" button in the top right corner where your display icon is and select 'New Repository'. Then fill out the Repository name and the Description fields. Make sure to change the settings according to what your professor wants.
2. Make sure to have "READ.md" file accessible to be able to commit or make other changes and choose whether you would like it to be private or public.

Just make sure when you know the difference between forking vs. cloning. When forking a repository you are creating a copy of the original repository but the repository remains on your Github account. As compared to cloning, the repository is copied onto whichever machine being used with the help of Git. So when doing a project, make sure you are using the right one.

### Setup Your Team
Once you have your team members to be able to work collaboratively. You need to add the other members of the team to be as collaborator. Once your team members are added as collaborators they'll be able to push, merge, commit to the repository.

To add collaborators, you click on the "Settings" tab, then "Collaborators" then search for the users by their username and add them by clicking "Add Collaborator".
The team members should recieve an e-mail with an invitation to be listed as a collaborator, the members should accept the invite and work from there.

### Collaborating
The Master branch should always be deployable. To keep the Master deployable you have to create new branches for new features and merge them into Master when they're completed. Branches are defined as a duplicate of the original repository which someone can make changes to without affecting the original repository. 

When working on the same project with other team members, it could cause some conflict. It could cause the codes to overlap and will also cause an error when its time to run it. 

To avoid merge conflict, you will see that it will pop up as "Merge conflict" in whichever file you are trying to merge or edit. After that message pops up, you will see it will give you the option to "fix conflict" then commit the result. Afer all of that is done, you will no longer see an issue.

Pull requests lets you tell the other members you are collabrating with that you have made changes to the repository. Once a pull request is sent, the members can review what changed were made and do whatever is necessary.
