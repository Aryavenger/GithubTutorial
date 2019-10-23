# Github Tutorial
Tutorial for github

# How Upload project to github
1. git init
2. git add *
3. git status
4. git commit -m "Commit Pertama"
5. git remote add origin https://github.com/gedelumbung/OptionMenu.git
6. git push origin master kalau error git pull --rebase kemudian git push origin master
7. masukkan username & password Github
8. selesai

# How to add/change username & email
1. git config --global user.name "John Doe" //setting username
2. git config --global user.email johndoe@example.com //settting email
3. git config --list //untuk mendapatkan list akun
4. git config user.name //untuk mendapatkan username

# How to change account github in windows
1. Open Control Panel from the Start menu
2. Select User Accounts
3. Select "Manage your credentials" in the left hand menu
4. Delete any credentials related to Git or GitHub
5. Done

# How to handle error  refusing to merge unrelated histories
1. git pull origin master --allow-unrelated-histories

# Another Function
1. git pull --ff-only

# How to handle error Updates were rejected because the tip of your current branch is behind
1. git pull https://github.com/Aryavenger/Harrisma.git master
2. git pull origin master --allow-unrelated-histories
3. git push origin maste
