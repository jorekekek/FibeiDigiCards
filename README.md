# Fibeidigiecards-
# 1. Update your local branch list
git fetch origin

# 2. Switch to your team's shared Parent branch
# Example: git checkout MothersDay-Mangubat,Lim
git checkout [Your-Parent-Branch]

# 3. Create and switch to your private Child branch
# Example: git checkout -b dev/mangubat-mothers-day
git checkout -b dev/[yourname]-[feature]

# Check what files you changed
git status

# Stage your changes
git add .

# Save with a clear message
git commit -m "feat: added responsive navigation bar"

# Push to your private branch on GitHub
git push origin dev/[yourname]-[feature]

