# WSL_GSD
### Description (H3)
Getting WSL and GSD setup

Download Git 
https://git-scm.com/install/windows

Using Obsidian to manage MD for documentation of process 
https://forum.obsidian.md/t/yet-another-obsidian-git-tutorial-desktop-pc-ipad-sync/67531 
https://dannyhatcher.com/obsidian-git-for-beginners/

Version Control using GitHub, connecting using SSH > 
https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection
Generate SSH key >
ssh-keygen -t ed25519 -C "your_email@example.com"
Copy the key to clipboard on BASH >
$ clip < ~/.ssh/id_ed25519.pub
\# Copies the contents of the id_ed25519.pub file to your clipboard
Test connection >
ssh -T git@github.com
\# Attempts to ssh to GitHub

test test
