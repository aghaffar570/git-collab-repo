# TTP Summer 2026 — Class Introductions

Welcome to our shared repo. This is a live collaboration exercise — by the end, every person in this class will have contributed a file to this repository.

---

## What You'll Practice (done locally on your machine)

- Cloning a remote repository (an existing project)
- Creating a branch
- Making a commit
- Pushing to GitHub
- Opening a Pull Request (done on github)

---

## Instructions

### 1. Clone the repo

If you haven't already:

```
git clone <repo-url>
cd <repo-name>
code .
```

`code .` -> opens current directory with vscode 

### 2. Create a branch

Name your branch using this format: `add/firstname-lastname`

```
git branch add/jane-doe
git switch add/jane-doe

OR

git checkout -b add/jane-doe
```

### 3. Create your file

Create a new file in the repo named `firstname-lastname.md` (use your actual name).

```
touch jane-doe.md

OR

create the file within vscode
```

Open the file and add **one line** about yourself. Anything — where you're from, what you're excited to build, a fun fact.

```md
Hi, I'm Jane — I'm from Brooklyn and I want to build a recipe app.
```

### 4. Stage and commit

```
git add jane-doe.md
git commit -m "add: jane doe intro"
```

### 5. Push your branch

```
git push origin <yourBranchName>

like:

git push origin add/jane-doe
```

### 6. Open a Pull Request

Go to the repo on GitHub. You should see a prompt to open a Pull Request from your branch. Click it, give it a title, and submit.

Your instructor will review and merge it.

---

## After Your PR Is Merged

Run this to pull down everyone's changes:

```
git pull origin main

or just:

git pull
```

You should now see your classmates' files on your machine.
