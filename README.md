# M3A Age Group Sets

Swim practice workouts for M3A Age Group teams.

## Season Structure

-**2025-26 SC/**: Sets from 2025-26 Short Course season. These have been retroactively converted into .tex and pushed to Git, so formatting may be a bit inconsistent.
-**2026 LC**: Sets from 2026 Long Course season.

## Folder Structure

- **Templates/**: Blank templates for creating new workouts
- **2026 LC/**: Long course workouts for 2026 season

## Workflow for Adding a New Workout

1. Create your workout from the template (in Templates folder)
2. Save both .tex and .pdf files in the appropriate folder (e.g., `2026 LC/`)
3. Run these commands in Terminal:

```bash
cd ~/m3a-ag-sets
git add .
git commit -m "Add workout for [DATE]"
git push
```

That's it! Your workout is now backed up on GitHub.

## Quick Commands

```bash
# To see what files have changed:
git status

# To add a specific workout:
git add "2026 LC/workout-name.tex" "2026 LC/workout-name.pdf"

# To pull latest changes from GitHub:
git pull
```
