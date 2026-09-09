## WSL_GSD

# Description
Getting WSL and GSD setup,
Downloading git, learning github, documenting in Obsidian using MD

# Pre-Req
- Download Git 
		https://git-scm.com/install/windows
- Create repo on GitHub & Version Control pull using SSH >
		https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection 
	- Generate SSH key >
		> ssh-keygen -t ed25519 -C "your_email@example.com"
	- Copy key on cli >
		> $ clip < ~/.ssh/id_ed25519.pub
	- Add key on GitHub
				![GitHub Add Key](WSL_GSD/Images/ssh.png)
	- Test connection on cli >
		> ssh -T git@github.com
	- CD to directory and pull
		> git clone repository-url
		
- Using Obsidian to manage MD for documentation of process <br>
		https://forum.obsidian.md/t/yet-another-obsidian-git-tutorial-desktop-pc-ipad-sync/67531 <br>
		https://dannyhatcher.com/obsidian-git-for-beginners/