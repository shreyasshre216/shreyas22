git config --global user.name "YourGitHubUsername"
git config --global user.email "YourEmail@example.com"
git config --list
cd path/to/your/folder

git clone https://github.com/YourGitHubUsername/YourRepository.git
code .
cd YourRepository
git remote -v
git add .
git commit -m "Your commit message"
git push origin main
