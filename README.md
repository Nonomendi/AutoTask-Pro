# 1. Initialize the local folder as a git repo
git init

# 2. Add all your files (index.js, package.json, README.md)
git add .

# 3. Create your first commit
git commit -m "Initial commit: AutoTask Pro script"

# 4. Rename the main branch (standard practice)
git branch -M main

# 5. Link your local folder to your GitHub repo 
# (Copy the URL from your GitHub repo page)
git remote add origin https://github.com/YOUR_USERNAME/AutoTask-Pro.git

# 6. Push your code to GitHub
git push -u origin main
