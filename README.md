# NewDay
NewSetOfQuestions
Q1) blob 
A1)A Git blob (binary large object) is the object type used to store the contents of each file in a repository. The file's SHA-1 hash is computed and stored in the blob object.
BLOBs are used primarily to hold multimedia objects such as images, videos, and sound, though they can also be used to store programs or even fragments of code. Not all DBMSs support BLOBs.

Q2)trees
A2)A Git tree object creates the hierarchy between files in a Git repository. You can use the Git tree object to create the relationship between directories and the files they contain. These endpoints allow you to read and write tree objects to your Git database on GitHub.

Q3)commit 
A3)The commit object contains the directory tree object hash, parent commit hash, author, committer, date and message. I'll use git cat-file to show the contents of the hashed files in . git/objects , but cat-file is a relatively obscure git command that you will probably not need in your daily git work.

Q4)branches
A4)The way git, and GitHub, manage this timeline — especially when more than one person is working in the project and making changes — is by using branches. A branch is essentially is a unique set of code changes with a unique name. Each repository can have one or more branches. ... One word: the master branch is deployable.

Q5)tags
A5)Git tags are like milestones, markers or a specific point in the repo's history marked as significant. Tags are usually used to mark stable releases or achievement of very important milestones. Tags can help the users of the repo to easily navigate to the important parts of the code history like release points.

Q6)clone
A6)Cloning a repository means that you're downloading a copy of the source code from source control. To use the iOS SDK you have to download the code from GitHub (ie- clone the iOS SDK repository).

Q7)push
A7)The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch , but whereas fetching imports commits to local branches, pushing exports commits to remote branches.

Q8)pull
A8) Pull requests let you tell others about changes you've pushed to a GitHub repository. Once a pull request is sent, interested parties can review the set of changes, discuss potential modifications, and even push follow-up commits if necessary.

Q9)head
A9)Git Head. The HEAD points out the last commit in the current checkout branch. It is like a pointer to any reference. The HEAD can be understood as the "current branch." When you switch branches with 'checkout,' the HEAD is transferred to the new branch.
