# Fibeidigiecards-
1. Update your local branch list
git fetch origin

2. Switch to your team's shared Parent branch
Example: git checkout MothersDay-Mangubat,Lim
git checkout [Your-Parent-Branch]

3. Create and switch to your private Child branch
Example: git checkout -b dev/mangubat-mothers-day
git checkout -b dev/[yourname]-[feature]

4. Check what files you changed "git status"

5. Stage your changes "git add"

6. Save with a clear message
git commit -m "feat: added responsive navigation bar"

7. Push to your private branch on GitHub
git push origin dev/[yourname]-[feature]

