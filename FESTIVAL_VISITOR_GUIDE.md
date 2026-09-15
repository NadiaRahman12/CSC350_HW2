# Festival Visitor Guide

## Student Information

- Name: Nadia Rahman
- Course and section: CSC350H 1300
- Date: 09/14/2026

## Repository Evidence

- Current branch: main
- Personal Homework 2 GitHub URL: https://github.com/NadiaRahman12/CSC350_HW2.git
- Starting `git status`: Clean working tree on `main`
- Starting preparation commit ID: bd125dd

## Festival Identity

- Festival name: Lanterns on the Lake
- Location: Lake Merritt Pergola, Oakland, California
- Intended audience: Local families, students, and anyone interested in community arts
- Theme: An evening of light, music, and handmade art celebrating the many cultures of Oakland.

## Prediction Before the First Commit

1. Where does the saved change currently live?

   In my local working tree

2. Has it been staged or committed?

   It has not been staged or committed yet. It is currently an unstaged working-tree change.

## Arrival Information

- Transit or parking: Take AC Transit line 12 to the Lake Merritt BART station, then walk east along Lakeside Drive for about ten minutes.
- Entrance or meeting location: Meet at the Lake Merritt Pergola's main north entrance beside the community garden.

## Accessibility Information

1. The main path and event area have step-free access for wheelchairs and mobility devices.
2. Accessible restrooms and reserved seating are available near the north entrance.

## Visitor Reminder

Keep valuables with you and stay within the lit festival area after sunset.

## GitHub Verification

Verified on GitHub by Nadia Rahman.

## Commit Evidence

| Checkpoint | Short commit ID | Required message |
|---|---|---|
| Personalized guide | `66bf20e` | `docs: personalize festival visitor guide` |
| Visitor access information | `808fd06` | `docs: add visitor access information` |
| GitHub verification | `eedad95` | `docs: verify independent homework on GitHub` |
| Final reflection | **See latest commit ID in `git log`** | `docs: complete independent Git reflection` |

## Final Evidence and Submission

The repository has four required student commits, a clean working tree, matching local and GitHub history, and a completed FESTIVAL_VISITOR_GUIDE.md.

## Individual Reflection

1. What is the difference between saving a file and committing it?

   Saving a file means the changes are stored on my computer. Committing means I save a version of those changes in Git so that I can keep track of what I changed and go back to it later if needed.

2. What is the difference between `git diff` and `git diff --staged`?

   git diff shows changes that are saved but not staged. git diff --staged shows the changes currently included in the staging area and ready for the next commit.

3. Why did the GitHub verification sentence not appear locally before `git pull`?

   The GitHub verification sentence did not appear locally because the changes had not been pulled from the GitHub repository yet. After running git pull, Git downloaded the latest changes from GitHub, so the verification sentence appeared in the local file.

4. What did `-u` accomplish in `git push -u origin main`?

   The -u connects the local main branch to the main branch on GitHub. It sets the remote branch as the default, so later we can use simple git push and git pull commands without specifying the branch each time.

5. What evidence proves that the local and GitHub repositories are synchronized at the end?

   git status shows a clean main branch, local mead matches origin/main, and the newest commit ID matches the commit shown on GitHub.
