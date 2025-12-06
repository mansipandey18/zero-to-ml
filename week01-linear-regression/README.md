# Week 1 — Linear Regression

Learn Python basics and the math behind linear regression through hands-on practice.

**Goal:** Understand how ML models learn from data → Build confidence → Have fun!

---

## 🎬 Setup & Start

### Step 1: Fork & Clone (Required for Submitting Work)

**Why fork?** So you can save your solutions and submit them!

```bash
# 1. Click "Fork" on the main repository
# 2. Clone YOUR fork
git clone https://github.com/YOUR-USERNAME/zero-to-ml.git
cd zero-to-ml

# 3. Create your student directory
mkdir -p students/YOUR-NAME/week01
```

### Step 2: Choose Your Environment

**Option 1: VS Code Local** ⭐ Recommended
```bash
# Install Python 3.8+ and VS Code
pip install numpy matplotlib jupyter ipykernel
code .
# Open week01-linear-regression/01-python-primer.ipynb
```

**Option 2: GitHub Codespaces**
- On YOUR fork: `Code` → `Codespaces` → `Create codespace`
- Wait for browser VS Code to load
- Open `01-python-primer.ipynb`

**Option 3: Google Colab** (for quick experiments)
- Go to [colab.research.google.com](https://colab.research.google.com/)
- `File` → `Open notebook` → `GitHub` → YOUR fork
- ⚠️ Remember to save work back to your fork manually

**Detailed instructions:** [SETUP_GUIDE.md](../SETUP_GUIDE.md)

---

## 📚 This Week's Content

### Day 1: Python Primer
**File:** `01-python-primer.ipynb`  
**Time:** 1-2 hours

**You'll learn:**
- Variables and data types
- Lists and loops
- Functions
- NumPy for math operations

**Prerequisites:** None!

---

### Day 2: Math Foundations
**File:** `02-math-foundations.ipynb`  
**Time:** 1.5-2 hours

**You'll learn:**
- Understanding points (x, y)
- What a line is: y = mx + b
- Slope and intercept (with visuals!)
- Making predictions
- Understanding error

**Prerequisites:** Day 1 complete

---

## 🎯 By End of Week

You'll be able to:
- ✅ Write basic Python code confidently
- ✅ Understand line equations
- ✅ Explain slope & intercept
- ✅ Make predictions using y = mx + b
- ✅ Calculate prediction error
- ✅ Feel confident, not scared of ML!

---

## 📖 External Resources

Want to dive deeper? These are optional but helpful:

### For Day 1 (Python)

**Videos:**
- [Python Basics (15 min)](https://youtu.be/kqtD5dpn9C8)
- [NumPy Tutorial (1 hour)](https://youtu.be/QUT1VHiLmmI)

**Practice:**
- [W3Schools Python Exercises](https://www.w3schools.com/python/python_exercises.asp)
- [Python Tutor (visualize code)](https://pythontutor.com/)

**Reading:**
- [Official Python Tutorial](https://docs.python.org/3/tutorial/)

---

### For Day 2 (Math)

**Videos:**
- [Khan Academy - Slope](https://www.khanacademy.org/math/algebra/x2f8bb11595b61c86:forms-of-linear-equations/x2f8bb11595b61c86:intro-to-slope-intercept-form/v/slope-intercept-form)
- [StatQuest - Linear Regression](https://youtu.be/nk2CQITm_eo)

**Interactive:**
- [Desmos Graphing Calculator](https://www.desmos.com/calculator) - Play with lines!
- [GeoGebra - Slopes](https://www.geogebra.org/m/sS8wBW6U)

**Reading:**
- [Better Explained - Linear Regression](https://betterexplained.com/articles/linear-regression/)

---

### General ML Resources

**Courses:**
- [Andrew Ng's ML Course (Coursera)](https://www.coursera.org/learn/machine-learning) - The classic
- [Google ML Crash Course](https://developers.google.com/machine-learning/crash-course)
- [Fast.ai](https://course.fast.ai/) - Code-first approach

**Communities:**
- [r/learnmachinelearning](https://www.reddit.com/r/learnmachinelearning/)
- [Kaggle Learn](https://www.kaggle.com/learn)

---

## 💡 Tips for Success

1. **Don't just read** → Type the code yourself
2. **Experiment** → Change values, see what happens
3. **Take breaks** → Your brain needs time to process
4. **Ask questions** → Open an Issue if stuck
5. **Teach someone** → Best way to solidify understanding

---

## 🧩 How to Use This Week

### Recommended Pace

| Day | Activity | Time |
|-----|----------|------|
| 1 | Complete Python Primer | 1-2 hrs |
| 2 | Complete Math Foundations | 1.5-2 hrs |
| 3 | Review & practice exercises | 1 hr |
| 4+ | Explore bonus challenges | Optional |

**Go at your own pace!** Quality > Speed

---

## 🤝 Submit Your Solutions

**After completing each day, submit your work!**

### Step-by-Step Submission:

1. **Copy your completed notebooks:**
```bash
# Copy from week01 folder to YOUR student folder
cp week01-linear-regression/01-python-primer.ipynb students/YOUR-NAME/week01/
cp week01-linear-regression/02-math-foundations.ipynb students/YOUR-NAME/week01/
```

2. **Add reflections** (optional but valuable):
```bash
# Create a notes file
cat > students/YOUR-NAME/week01/NOTES.md << 'EOF'
# Week 1 Reflections

## Day 1 - Python Primer
- What clicked: ...
- What was challenging: ...
- Questions: ...

## Day 2 - Math Foundations
- Key takeaway: ...
- Favorite visualization: ...
- Areas to review: ...
EOF
```

3. **Commit your work:**
```bash
git add students/YOUR-NAME/
git commit -m "Complete Week 1 - Days 1 & 2"
git push origin main
```

4. **Create Pull Request:**
   - Go to your fork on GitHub
   - Click "Pull requests" → "New pull request"  
   - **Title:** "Week 1 Solutions - [Your Name]"
   - **Description:** 
     ```
     Completed Week 1 exercises!
     
     - ✅ Day 1: Python Primer
     - ✅ Day 2: Math Foundations
     
     **Challenges faced:** ...
     **What I learned:** ...
     **Questions:** ...
     ```
   - Click "Create pull request"

### What to Include in Your Submission:

**Required:**
- ✅ Completed `01-python-primer.ipynb` with all exercises solved
- ✅ Completed `02-math-foundations.ipynb` with all exercises solved

**Optional (but encouraged):**
- 📝 NOTES.md with your reflections
- 💡 Additional exercises you created
- 🎨 Visualizations or diagrams you made
- ❓ Questions or areas where you struggled

### Benefits of Submitting:

1. **Get feedback** from maintainers and peers
2. **Help future learners** by showing different approaches
3. **Build your GitHub portfolio** with real projects
4. **Join the community** of zero-to-ml learners
5. **Stay motivated** by sharing your progress

**Don't worry about "perfect" solutions!** We value:
- Your thought process
- What you tried
- Questions you have
- Creative approaches

---

## ❓ Need Help?

### Stuck on Setup?
See [SETUP_GUIDE.md](../SETUP_GUIDE.md) for detailed instructions.

### Stuck on Content?
Open an Issue: **"Week 1 - Day X - [Your Question]"**

Include:
- What you tried
- What happened
- What you expected

### Just Want to Discuss?
Use [GitHub Discussions](https://github.com/YOUR-USERNAME/zero-to-ml/discussions)

---

## ✨ What's Next?

After completing Week 1:
- 🔜 Day 3-5 content (coming soon)
- 🔜 Practice exercises
- 🔜 Mini-projects

Stay tuned! ⭐ Star the repo for updates.

---

**Ready?** → Open `01-python-primer.ipynb` and start learning! 🚀
