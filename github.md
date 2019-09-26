  
The Glory of Git

1. Only merge when absolutely necessary (heuristic, not rule)
Better: Use git pull rebase
Why: Rebase notes your commits and applies those to the branch head

2. Make commits descriptive and meaningful 
- Add the jira number to front of commit message
- first line of commit should be sort summary
Why: helps with end-to-end design tracability 

3. Do trunk based development
- Keep feature branches legal, safe and rare
- Automate testing
- must have testable success criteria (ask questions until requirement is clear)
- use feature flags (disables sections of code)
Why: https://trunkbaseddevelopment.com/

Useful Git tools:
Git reflog - gives you the history of local development
Git bisect - automates finding bugs in commit history 

Learning Resources:
http://stevelosh.com/blog/2013/04/git-koans/
https://ohshitgit.com/

Platform Resources:
https://github.com/magit/magit
https://desktop.github.com/
https://www.gitkraken.com/
