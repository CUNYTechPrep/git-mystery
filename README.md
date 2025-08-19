# 🔍 Git Mystery: The Case of the Missing Algorithm

## Welcome, Detective!

A terrible crime has been committed at TechCorp! The revolutionary algorithm that could change the future of computing has been STOLEN! Professor Git needs your help to solve this mystery using the power of Git.

## 🎯 Your Mission

Use Git commands to:
1. Investigate the crime scene (the repository history)
2. Examine the evidence (files in `case-files/`)
3. Interview witnesses (check their statements)
4. Find contradictions and lies
5. Identify the thief!

## 🚀 Getting Started

1. **Read the emergency notice:**
   ```bash
   cat EMERGENCY.txt
   ```

2. **Check the crime scene:**
   ```bash
   git log --oneline
   ```

3. **Look for clues:**
   ```bash
   git log --stat
   ```

4. **Examine evidence:**
   ```bash
   ls case-files/evidence/
   ```

5. **Read witness statements:**
   ```bash
   cat case-files/evidence/witness_statements.md
   ```

## 📁 Repository Structure

```
git-mystery/
├── EMERGENCY.txt           # The crime report
├── HINTS.md               # Investigation hints
├── case-files/            # Evidence and suspect information
│   ├── evidence/          # Witness statements, security logs, emails
│   └── suspects/          # Suspect profiles
├── investigation-notes/   # YOUR investigation notes go here
└── src/                   # The crime scene (source code)
```

## 🕵️ How to Investigate

### Essential Git Detective Commands:
- `git log --stat --oneline` - See what files changed in each commit
- `git show <commit-hash>` - Examine a specific commit in detail
- `git log --since="2:00 PM" --until="4:00 PM"` - Check specific time periods
- `git log --author="Name"` - See commits by specific person

### Evidence to Examine:
1. **Witness Statements** - Do their alibis check out?
2. **Security Footage** - Who was where and when?
3. **Emails** - Any suspicious communications?
4. **Git History** - The commits never lie!

## 📝 Document Your Findings

Create files in `investigation-notes/` as you discover clues:
```bash
echo "Found something suspicious in commit abc123" >> investigation-notes/clues.md
git add investigation-notes/clues.md
git commit -m "Document suspicious commit finding"
```

## 🎯 Making Your Accusation

When you think you've solved the case, create `investigation-notes/accusation.md` with:
- **WHO** did it (name of the perpetrator)
- **WHEN** they did it (time from the commit)
- **HOW** they did it (what Git command/action)
- **WHY** they did it (motive from evidence)
- **EVIDENCE** (list your proof)

## 💡 Need Help?

- Check `HINTS.md` for investigation tips
- Look for contradictions between evidence files
- Remember: The commit message might be lying!
- The truth is always in `git log --stat`

## 🏆 Success Criteria

You've solved the mystery when you can:
1. Identify who deleted algorithm.py
2. Prove when they did it
3. Show evidence of their motive
4. Explain why their alibi is false

## ⚠️ Warning

One of the five suspects is lying. Their commit message says one thing, but they did something entirely different. Trust the Git history, not what people say!

---

*Good luck, Detective! The future of TechCorp depends on you!*

**Start with:** `cat EMERGENCY.txt` and then `git log --stat --oneline`