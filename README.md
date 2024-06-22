My Report

I executed the following Git commands:

1. cd PLPBasicGitAssignment: I changed the current directory to PLPBasicGitAssignment.

2. git init: I initialized a new Git repository in the current directory.

3. git remote add origin https://github.com/Kau-Molepo/PLPBasicGitAssignment.git: I added a remote repository named origin with the specified URL.

4. git add.: I staged all changes in the current directory and its subdirectories.

5. git commit -m "Add hello.txt with a greeting": I created a new commit with the specified message, adding the hello.txt file to the repository.

6. git push -u origin main: I attempted to push the local main branch to the remote main branch on origin, but failed because the remote branch did not exist.

7. git branch -m master main: I renamed the local master branch to main.

8. git push -u origin main: I attempted to push the local main branch to the remote main branch on origin, but failed because the remote branch was not up to date.

9. git push origin --set-upstream main: I attempted to push the local main branch to the remote main branch on origin and set the upstream tracking information, but failed because the remote branch was not up to date.

10. git pull origin master: I attempted to pull changes from the remote master branch on origin, but failed because the remote branch did not exist.

11. git pull origin main: I attempted to pull changes from the remote main branch on origin, but failed because the histories were unrelated.

12. git ls-remote --heads origin: I listed the heads (branches) on the remote repository origin.

13. git pull origin master: I attempted to pull changes from the remote master branch on origin, but failed because the remote branch did not exist.

14. git pull origin main: I attempted to pull changes from the remote main branch on origin, but failed because the histories were unrelated.

15. git branch -u origin/main: I set the upstream tracking information for the local main branch to track the remote main branch on origin.

16. git pull origin main: I attempted to pull changes from the remote main branch on origin, but failed because the histories were unrelated.

17. git merge: I attempted to merge the current branch with another branch, but failed because the histories were unrelated.

18. git pull origin main --allow-unrelated-histories: I pulled changes from the remote main branch on origin, allowing unrelated histories to be merged.

19. git push -u origin main: I pushed the local main branch to the remote main branch on origin, setting the upstream tracking information.

Note: I noticed that the Git push was done from a different account than the one that created the repository. The repository was created by Kau-Molepo, but the Git push was done by KLG-TECHNOLOGIES. This is evident from the commit history and the contributor list on the GitHub page.

Summary: In summary, I executed a series of Git commands to initialize a new repository, add a remote repository, commit changes, and push and pull changes between the local and remote repositories. However, I encountered issues due to unrelated histories and had to use the --allow-unrelated-histories flag to merge the changes. Additionally, I noticed that the Git push was done from a different account than the one that created the repository.
