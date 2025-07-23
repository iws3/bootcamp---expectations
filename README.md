
---

# 🌱 DeepSeeds – First Contribution Playground  
*“From Seed to Sequoia”*

Welcome, DeepSeed!  
This repository is a safe place to practise the complete **fork → clone → branch → pull-request** workflow you will use in every open-source project.

---

## 🎯 Your Mission (5 min)

1. Fork this repo.  
2. Clone your fork.  
3. Create a branch called `add-<your-first-name>` (e.g. `add-gita`).  
4. In the `students/` folder, create a file named **exactly** `<your-first-name>.py` (e.g. `gita.py`).  
5. Inside that file place **one** line:  
   ```python
   print("At the end of the Ultimate GenAI Course Bamenda 2025, I expect to <write your expectation here!>")
   ```  
6. Commit, push, and open a Pull Request (PR) back to this repo.

That’s it—you will have made your first open-source contribution! 🎉

---

## 🛠️ Step-by-Step (Command Line)

> If you prefer a GUI, GitHub Desktop works the same—adapt the steps below.

### 1. Fork  
Click **Fork** (top-right of this page) so the repo appears under *your* GitHub account. 

### 2. Clone your fork


### 3. Keep your fork in sync (optional - infact skip)
```bash
git remote add upstream https://github.com/iws3/bootcamp---expectations.git
git checkout master
git merge upstream/m
```

### 4. Create & switch to a new branch
```bas
git checkout -b add-<your-first-name>
```

### 5. Make your change
```bash
echo 'print("At the end of the Ultimate GenAI Course Bamenda 2025, I expect to <your expectation>")' > students/<your-first-name>.py
```

### 6. Stage, commit & push
```bash
git add students/<your-first-name>.py
git commit -m "Add <your-first-name> expectation"
git push -u origin add-<your-first-name>
```

### 7. Open a Pull Request  
- Go to **your fork** on GitHub.  
- Click **Compare & pull request**.  
- Title: `Add <your-first-name> expectation`  
- Description: Feel free to say hi 👋  
- Submit!

---

## ✅ Checklist before submitting

- [ ] My file is inside `students/`.  
- [ ] File name is `<my-first-name>.py`.  
- [ ] It contains exactly one `print()` statement with my expectation.  
- [ ] I created a branch named `add-<my-first-name>`.  
- [ ] I opened the PR against the `main` branch of the original repo.

---

## 📚 Need Help?

- **Git not installed?** https://git-scm.com/downloads  
- **VS Code not set up?** https://code.visualstudio.com/docs/sourcecontrol/overview  
- **Authentication errors?** Use a [Personal Access Token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) instead of password. 

---

## 🤝 Code of Conduct

Be kind. Be welcoming. We’re all learning.

---

Happy planting, DeepSeed! 🌳