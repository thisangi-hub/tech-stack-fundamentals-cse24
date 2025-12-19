# Tech Stack Fundamentals Workshops

## 👨‍🏫 Session Conductors

<a href="https://github.com/HimathX"><img src="https://github.com/HimathX.png" width="60" height="60" style="border-radius:50%" alt="HimathX"/></a>
<a href="https://github.com/SuhasDissa"><img src="https://github.com/SuhasDissa.png" width="60" height="60" style="border-radius:50%" alt="SuhasDissa"/></a>
<a href="https://github.com/NipunSGeeTH"><img src="https://github.com/NipunSGeeTH.png" width="60" height="60" style="border-radius:50%" alt="NipunSGeeTH"/></a>
<a href="https://github.com/Kalana-Pankaja"><img src="https://github.com/Kalana-Pankaja.png" width="60" height="60" style="border-radius:50%" alt="Kalana-Pankaja"/></a>

---

## Repository Structure

```
tech-stack-fundamentals-cse24/
├── README.md
├── WORKSHOP_OVERVIEW.md
├── SCHEDULE.md
├── Task 01/
│   ├── README.md
│   ├── task_instructions.pdf
│   └── submissions/
│       └── [Your_Name]/
│           ├── index.html
│           ├── style.css
│           └── images/
├── Task 02/
│   ├── README.md
│   ├── task_instructions.pdf
│   └── submissions/
│       └── [Your_Name]/
│           └── index.html
└── Task 03/
    ├── README.md
    ├── task_instructions.pdf
    └── submissions/
        └── [Your_Name]/
            └── index.html
```

---

## How to Submit Your Work

> ⚠️ **Important:** You cannot push directly to this repository. All submissions must be made through **Pull Requests**.

### Step 1: Fork the Repository

1. Go to [https://github.com/HimathX/tech-stack-fundamentals-cse24](https://github.com/HimathX/tech-stack-fundamentals-cse24)
2. Click the **"Fork"** button (top-right corner)
3. This creates a copy of the repository under your GitHub account

### Step 2: Clone Your Forked Repository

1. On your forked repo page, click the green **"Code"** button
2. Copy the URL
3. Open **Terminal** (or Git Bash) and run:

```bash
git clone https://github.com/YOUR_USERNAME/tech-stack-fundamentals-cse24.git
```

> 💡 Replace `YOUR_USERNAME` with your GitHub username

### Step 3: Create Your Submission Folder

1. Open the cloned folder in **File Explorer**
2. Navigate to `Task 01` → `submissions`
3. Create a new folder with your name: `Firstname_Lastname`
4. Inside your folder, create:
   - `index.html`
   - `style.css`
   - `images/` folder (for any images)

**Example folder structure:**
```
submissions/
└── Himath_Jayasinghe/
    ├── index.html
    ├── style.css
    └── images/
```

### Step 4: Complete Your Task

Write your code according to the task instructions in the `README.md` of that task folder.

### Step 5: Commit and Push to Your Fork

1. Open **Terminal** in the repository folder
2. Run these commands:

```bash
git add .
git commit -m "Task 1 Submission: Your Name"
git push
```

### Step 6: Create a Pull Request

1. Go to your forked repository on GitHub
2. Click the **"Contribute"** button → **"Open pull request"**
3. Or click the **"Compare & pull request"** button if it appears
4. Add a clear title: `Task 1 Submission: Your Name`
5. Add a description of your work (optional)
6. Click **"Create pull request"**
7. Wait for your submission to be reviewed and merged! ✅

---

## Keeping Your Fork Updated

Before starting a new task, sync your fork on GitHub:

1. Go to your forked repository on GitHub
2. Click **"Sync fork"** button (below the green Code button)
3. Click **"Update branch"**
4. Pull the changes to your computer:

```bash
git pull
```

---

## ❓ Troubleshooting

**Cannot push to repository?**

Make sure you cloned YOUR fork (not the original). Your URL should have YOUR username in it.

**Pull Request has conflicts?**

Sync your fork using the "Sync fork" button on GitHub, then run `git pull` locally.

**Need help?**

Ask one of the session conductors! 👆

---

## 🖥️ Using GitHub Desktop (Alternative Method)

If you prefer a graphical interface instead of command line:

### Step 1: Install GitHub Desktop

Download from [https://desktop.github.com/](https://desktop.github.com/) and sign in with your GitHub account.

### Step 2: Fork the Repository

1. Go to [https://github.com/HimathX/tech-stack-fundamentals-cse24](https://github.com/HimathX/tech-stack-fundamentals-cse24)
2. Click the **"Fork"** button (top-right corner)

### Step 3: Clone Your Fork in GitHub Desktop

1. Open GitHub Desktop
2. Go to **File** → **Clone Repository**
3. Select the **GitHub.com** tab
4. Find `tech-stack-fundamentals-cse24` in your repositories list
5. Choose where to save it on your computer
6. Click **Clone**

### Step 4: Create Your Submission

1. Open the repository folder in File Explorer
2. Navigate to `Task 01/submissions/`
3. Create a new folder with your name (e.g., `Himath_Jayasinghe`)
4. Add your files: `index.html`, `style.css`, and `images/` folder

### Step 5: Commit Your Changes

1. Open GitHub Desktop - it will show your changes
2. In the bottom-left, add a **Summary**: `Task 1 Submission: Your Name`
3. Click **Commit to main**

### Step 6: Push to GitHub

1. Click **Push origin** (or **Publish branch**)

### Step 7: Create a Pull Request

1. In GitHub Desktop, go to **Branch** → **Create Pull Request**
2. This opens GitHub in your browser
3. Add a title: `Task 1 Submission: Your Name`
4. Click **Create pull request**
5. Done! Wait for your submission to be reviewed ✅

### Keeping Your Fork Updated (GitHub Desktop)

1. Click **"Fetch origin"** at the top
2. If there's a **"Sync fork"** option, click it
3. Click **"Pull origin"** to get the latest changes

---

Last Updated: 19th December 2025
