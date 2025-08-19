# Investigation Hints

## Getting Started
Start by reading EMERGENCY.txt to understand what happened.

## Useful Git Commands for Your Investigation

### Level 1: Basic Investigation
- `git log --oneline` - See all commits in simple format
- `git log --stat` - See what files changed in each commit
- `git show <commit-hash>` - Examine a specific commit in detail

### Level 2: Deeper Investigation  
- `git log --stat --oneline` - Combine to see files changed per commit
- `git diff <commit1> <commit2>` - Compare two commits
- `git log --author="Name"` - See commits by specific person
- `git log --since="2:00 PM" --until="4:00 PM"` - Check specific time windows

### Level 3: Advanced Detective Work
- `git show --stat <commit>` - Detailed view of changes
- `git log --pretty=format:"%h %an %ad %s" --date=local` - Custom formatted log
- `git blame <file>` - See who last modified each line (if file still exists)

## Investigation Strategy

1. **Find the Crime**: Look for when algorithm.py disappeared
2. **Check Alibis**: Compare witness statements with commit times
3. **Review Evidence**: Check security footage against git history
4. **Look for Motive**: Read through the emails carefully
5. **Notice Contradictions**: Do the commit messages match the actual changes?

## Red Flags to Watch For
- Commit messages that don't match the actual changes
- Suspicious timing of commits
- Someone claiming to be somewhere they weren't
- Deleted files in "innocent" looking commits

## Remember
The truth is in the git history. Every commit tells a story!