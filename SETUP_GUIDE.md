# 🚀 Setup Guide - How to Run zero-to-ml Notebooks

This guide will help you set up your environment to run the notebooks. Choose the method that works best for you!

---

## 🌟 Recommended for Beginners: Google Colab

**Why?** No installation, runs in browser, completely free!

### Step-by-Step:

1. **Open Google Colab**
   - Go to: [colab.research.google.com](https://colab.research.google.com/)
   - Sign in with your Google account

2. **Open from GitHub**
   - Click `File` → `Open notebook`
   - Select the `GitHub` tab
   - Paste: `https://github.com/YOUR-USERNAME/zero-to-ml`
   - OR search: `YOUR-USERNAME/zero-to-ml`

3. **Select Notebook**
   - Click on `week01-linear-regression/01-python-primer.ipynb`
   - Notebook opens in a new tab

4. **Start Learning!**
   - Run cells by clicking the play button or pressing `Shift+Enter`
   - All libraries are pre-installed
   - Your work auto-saves to Google Drive

### Tips for Google Colab:

- 📁 **Save a copy:** `File` → `Save a copy in Drive` to keep your changes
- ▶️ **Run all cells:** `Runtime` → `Run all`
- 🔄 **Reset:** `Runtime` → `Restart runtime` if something breaks
- 💾 **Download:** `File` → `Download` → `.ipynb` to save locally

### Helpful Video:
- [Google Colab Tutorial for Beginners (5 min)](https://www.youtube.com/watch?v=inN8seMm7UI)

---

## 💻 GitHub Codespaces - VS Code in Browser

**Why?** Full VS Code experience without installing anything!

### Step-by-Step:

1. **Fork the Repository**
   - Go to: `https://github.com/YOUR-USERNAME/zero-to-ml`
   - Click the `Fork` button (top right)
   - Wait for fork to complete

2. **Create Codespace**
   - On YOUR forked repository
   - Click the green `Code` button
   - Select the `Codespaces` tab
   - Click `Create codespace on main`

3. **Wait for Setup**
   - VS Code will load in your browser
   - Wait 1-2 minutes for environment to initialize
   - You'll see a full VS Code interface

4. **Install Jupyter Extension**
   - Click Extensions icon (left sidebar)
   - Search: "Jupyter"
   - Click "Install" on "Jupyter" by Microsoft
   - Also install "Python" by Microsoft if not already installed

5. **Open Notebook**
   - Navigate to `week01-linear-regression/`
   - Click `01-python-primer.ipynb`
   - Select Python kernel when prompted
   - Start running cells!

6. **Install Dependencies** (if needed)
   - Open terminal: `Ctrl+\`` (backtick) or `Terminal` → `New Terminal`
   - Run: `pip install numpy matplotlib`

### Tips for Codespaces:

- 💾 **Auto-saves:** Your work is automatically saved
- 📱 **Free tier:** 60 hours/month for free accounts
- 🔄 **Stop codespace:** Click your codespace name → `Stop codespace` when done
- 📤 **Commit changes:** Use Source Control (left sidebar) to save changes to GitHub

### Helpful Videos:
- [GitHub Codespaces Introduction (10 min)](https://www.youtube.com/watch?v=ozuDPmcC1io)
- [VS Code for Beginners](https://www.youtube.com/watch?v=B-s71n0dHUk)

---

## 🖥️ Local Setup - VS Code on Your Computer

**Why?** Full control, works offline, fastest performance!

### Step 1: Install Python

**Windows:**
1. Go to [python.org/downloads](https://www.python.org/downloads/)
2. Download Python 3.11 or higher
3. Run installer
4. ✅ **IMPORTANT:** Check "Add Python to PATH"
5. Click "Install Now"
6. Verify: Open Command Prompt → type `python --version`

**Mac:**
1. Go to [python.org/downloads](https://www.python.org/downloads/)
2. Download Python 3.11 or higher for macOS
3. Run the installer
4. Verify: Open Terminal → type `python3 --version`

**Linux (Ubuntu/Debian):**
```bash
sudo apt update
sudo apt install python3 python3-pip
python3 --version
```

### Step 2: Install VS Code

1. Go to [code.visualstudio.com](https://code.visualstudio.com/)
2. Download for your operating system
3. Install and open VS Code

### Step 3: Install VS Code Extensions

1. Open VS Code
2. Click Extensions icon (left sidebar) or press `Ctrl+Shift+X`
3. Search and install these extensions:
   - **Python** by Microsoft
   - **Jupyter** by Microsoft

### Step 4: Clone the Repository

**Option A: Using VS Code**
1. Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on Mac)
2. Type: "Git: Clone"
3. Paste: `https://github.com/YOUR-USERNAME/zero-to-ml.git`
4. Choose a folder location
5. Click "Open" when clone completes

**Option B: Using Terminal**
```bash
# Navigate to where you want the project
cd ~/Documents

# Clone the repository
git clone https://github.com/YOUR-USERNAME/zero-to-ml.git

# Enter the directory
cd zero-to-ml

# Open in VS Code
code .
```

### Step 5: Install Python Packages

1. Open Terminal in VS Code: `Ctrl+\`` (backtick) or `View` → `Terminal`
2. Run this command:

```bash
pip install numpy matplotlib jupyter ipykernel
```

**On Mac/Linux, use:**
```bash
pip3 install numpy matplotlib jupyter ipykernel
```

### Step 6: Open and Run Notebooks

1. In VS Code file explorer, navigate to:
   `week01-linear-regression/01-python-primer.ipynb`
2. Click to open the notebook
3. VS Code will ask you to select a kernel
4. Choose "Python 3.x.x" (whichever version you installed)
5. Click the "Run All" button or run cells individually

### Troubleshooting Local Setup:

**Problem: "python is not recognized"**
- Solution: Reinstall Python and CHECK "Add Python to PATH"

**Problem: No Python kernel showing**
- Solution: `pip install ipykernel` then restart VS Code

**Problem: ImportError for numpy/matplotlib**
- Solution: `pip install numpy matplotlib`

**Problem: Can't run cells**
- Solution: Make sure Jupyter extension is installed and enabled

### Helpful Videos:
- [Python in VS Code - Full Setup (15 min)](https://www.youtube.com/watch?v=W--_EOzdTHk)
- [Jupyter Notebooks in VS Code (10 min)](https://www.youtube.com/watch?v=FSdIoJdSnig)

---

## 📓 Classic Jupyter Notebook/Lab

**Why?** Traditional Jupyter experience, lightweight!

### Setup:

1. **Install Jupyter**
```bash
pip install jupyterlab numpy matplotlib
# or for classic notebook
pip install notebook numpy matplotlib
```

2. **Clone Repository**
```bash
git clone https://github.com/YOUR-USERNAME/zero-to-ml.git
cd zero-to-ml
```

3. **Launch Jupyter**
```bash
# For JupyterLab (recommended)
jupyter lab

# OR for classic Notebook
jupyter notebook
```

4. **Open in Browser**
   - Browser opens automatically
   - Navigate to `week01-linear-regression/`
   - Click `01-python-primer.ipynb`

### JupyterLab Tips:

- 📁 **File browser:** Left sidebar shows all files
- ▶️ **Run cell:** Click play button or `Shift+Enter`
- ➕ **Add cell:** Click `+` button in toolbar
- 💾 **Save:** `Ctrl+S` or `File` → `Save`
- 🛑 **Stop kernel:** `Kernel` → `Shutdown Kernel`

---

## 🆚 Which Method Should I Choose?

| Your Situation | Recommended Method | Why |
|----------------|-------------------|-----|
| Complete beginner | Google Colab | Zero setup, start in 30 seconds |
| Want VS Code experience | GitHub Codespaces | VS Code in browser, no install |
| Regular practice | VS Code Local | Full control, works offline |
| Low bandwidth | VS Code Local | Works offline after setup |
| Chromebook user | Google Colab | Works on any device with browser |
| Want to contribute | GitHub Codespaces or Local | Easy to commit changes |

---

## 🎯 Quick Start Summary

### Absolute Fastest (30 seconds):
1. Go to [colab.research.google.com](https://colab.research.google.com/)
2. `File` → `Open notebook` → `GitHub` tab
3. Enter repo URL
4. Start learning!

### Best Long-term (10 minutes):
1. Install Python + VS Code
2. Clone repository
3. `pip install numpy matplotlib jupyter`
4. Open notebooks in VS Code

---

## ❓ Common Questions

**Q: Do I need to pay for anything?**
A: No! All methods have free tiers that are sufficient for this course.

**Q: Can I use iPad/tablet?**
A: Yes! Use Google Colab - works great on tablets.

**Q: What if I don't have a Google account?**
A: Use GitHub Codespaces or set up locally.

**Q: How much disk space do I need?**
A: For local setup: ~2-5 GB (Python + libraries + this repo)

**Q: Can I switch methods later?**
A: Absolutely! The `.ipynb` files work everywhere.

**Q: What Python version do I need?**
A: Python 3.8 or higher. We recommend 3.11+.

---

## 🆘 Still Stuck?

1. **Check our Issues:** [GitHub Issues](https://github.com/YOUR-USERNAME/zero-to-ml/issues)
2. **Ask for help:** Open a new Issue with tag `setup-help`
3. **Include:**
   - Your operating system
   - Which method you're trying
   - Screenshot of error
   - What you've tried

We're here to help! 💚

---

## 📚 Additional Resources

### Video Tutorials:
- [Google Colab Complete Guide](https://www.youtube.com/watch?v=inN8seMm7UI)
- [VS Code Python Setup](https://www.youtube.com/watch?v=W--_EOzdTHk)
- [GitHub Codespaces Tutorial](https://www.youtube.com/watch?v=ozuDPmcC1io)

### Documentation:
- [Google Colab FAQ](https://research.google.com/colaboratory/faq.html)
- [VS Code Python Tutorial](https://code.visualstudio.com/docs/python/python-tutorial)
- [GitHub Codespaces Docs](https://docs.github.com/en/codespaces)
- [Jupyter Documentation](https://jupyter.org/documentation)

### Interactive Practice:
- [Python Tutor](https://pythontutor.com/) - Visualize code execution
- [Codecademy Python](https://www.codecademy.com/learn/learn-python-3) - Interactive lessons

---

**Ready to start learning?** Head to [Week 1](../week01-linear-regression/) 🚀

---

## 📤 Submitting Your Solutions

After completing exercises, submit your work to build your portfolio and help others!

### Complete Workflow:

```
1. Fork Repository (GitHub)
   ↓
2. Clone to Local / Open in Codespaces
   ↓
3. Create: students/YOUR-NAME/week01/
   ↓
4. Complete Exercises
   ↓
5. Copy Notebooks to Your Folder
   ↓
6. Commit & Push
   ↓
7. Create Pull Request
   ↓
8. Get Feedback & Merge!
```

### Detailed Steps:

**1. Fork the Repository**
- Go to main zero-to-ml repository
- Click "Fork" button (top right)
- Wait for fork to complete
- Now you have: `github.com/YOUR-USERNAME/zero-to-ml`

**2. Create Your Student Folder**
```bash
# In your cloned repository
cd zero-to-ml
mkdir -p students/YOUR-NAME/week01
```

**3. Complete the Exercises**
- Work through notebooks in `week01-linear-regression/`
- Solve all exercises
- Experiment and learn!

**4. Copy Your Work**
```bash
# Copy completed notebooks
cp week01-linear-regression/01-python-primer.ipynb students/YOUR-NAME/week01/
cp week01-linear-regression/02-math-foundations.ipynb students/YOUR-NAME/week01/

# Create reflection notes (optional)
nano students/YOUR-NAME/week01/NOTES.md
```

**5. Commit Your Changes**
```bash
# Check what you've changed
git status

# Add your student folder
git add students/YOUR-NAME/

# Commit with a clear message
git commit -m "Complete Week 1: Python Primer & Math Foundations"

# Push to YOUR fork
git push origin main
```

**6. Create Pull Request**
- Go to your fork on GitHub
- You'll see: "This branch is X commits ahead"
- Click "Contribute" → "Open pull request"
- Fill in:
  - **Title:** "Week 1 Solutions - [Your Name]"
  - **Description:** What you learned, challenges, questions
- Click "Create pull request"

**7. Engage with Feedback**
- Maintainers may comment on your PR
- Answer questions or make changes if requested
- Learn from feedback!

### Example Folder Structure:

```
students/
├── jane-smith/
│   └── week01/
│       ├── 01-python-primer.ipynb          # ✅ Required
│       ├── 02-math-foundations.ipynb       # ✅ Required
│       ├── NOTES.md                         # 📝 Optional
│       └── bonus-visualizations.ipynb       # 💡 Optional
│
└── john-doe/
    └── week01/
        ├── 01-python-primer.ipynb
        ├── 02-math-foundations.ipynb
        └── my-custom-exercise.ipynb
```

### Tips for Good Submissions:

✅ **Complete all exercises** before submitting  
✅ **Add comments** explaining your thinking  
✅ **Include questions** where you're unsure  
✅ **Share insights** you discovered  
✅ **Be honest** about struggles  

❌ Don't copy solutions without understanding  
❌ Don't wait for "perfect" - submit and improve!  
❌ Don't skip the learning process  

### Common Questions:

**Q: What if my solution is different from others?**  
A: Great! Different approaches help everyone learn.

**Q: What if I didn't solve everything?**  
A: Submit anyway! Ask for help on specific exercises.

**Q: Will my PR be merged?**  
A: Yes! All genuine learning submissions are welcomed.

**Q: Can I update my submission later?**  
A: Absolutely! Just push more commits to your fork.

---