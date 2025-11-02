Hi, This Repository is created to Learn Virtual Machines , controol them from the command line itself , Make changes without GUI .
Step 1 - Installed Ubuntu Server By Allocating 50Gb Disk Space , 8888mb Memory Ram , 8 Cpu Cores.
Step 2 - Instaeed Git , Curl , Node , Npm
Step 3 - Created Server Locally using CLI
Step 4 - Cloned a Git Repo
Step 5- Logged in to Github Followed Steps - git config --global user.name "Your GitHub Username"
git config --global user.email "your_email@example.com"
Pushing For the First Time - git clone https://github.com/USERNAME/REPO.git

# or if already cloned

git push https://USERNAME@github.com/USERNAME/REPO.git

When prompted for a password, paste your personal access token instead of your GitHub password."
Step 6 - To avoid Manually entering credentials , I ran this command - git config --global credential.helper store
" Will test and input if git is able to reme,ber credentials .Also The token validity is set for one year so by 2026 the token will be expired.
Step - 7 - Every Change on the readme is being done through nano . ctrl + o , saves thing , give name or make change to filename. ctrl + x exits. Using cat comand to view contents of the file.
Step - 8 - Line change to test if git remeber credentials
Step 9 - Before Restart git remembered Credentials. Lets check after reboot of system
Step 10 - Installed Prettier Gloabally 
		-----
sudo npm install -g prettier

Step 11 - Prettiied the File using - prettier --write filename.js
