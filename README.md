# PlaywrightAutomation

A Playwright automation project for testing and automation workflows.

## Project Structure

```
PlaywrightAutomation/
├── Chapter1_Basics/
│   ├── baiscs.js
│   ├── hot_code.js
│   ├── JS_step_by_step.js
│   └── Verify_setup.js
├── .gitignore
└── README.md
```

## Contents

### Chapter1_Basics
- **baiscs.js** - Basic Playwright examples and setup
- **hot_code.js** - Hot code/reloading examples
- **JS_step_by_step.js** - Step-by-step JavaScript examples
- **Verify_setup.js** - Script to verify Playwright setup

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rohit88kmr19/playwrightAutomation.git
cd playwrightAutomation
```

2. Install dependencies:
```bash
npm install
```

3. Install Playwright browsers:
```bash
npx playwright install
```

### Running Tests

To verify your setup is working correctly:
```bash
node Chapter1_Basics/Verify_setup.js
```

## Basic Git Commands

Here are some common Git commands used in this project:

### Clone the Repository
```bash
git clone https://github.com/rohit88kmr19/playwrightAutomation.git
```

### Check Repository Status
```bash
git status
```

### Stage Changes
```bash
git add .                # Stage all changes
git add <filename>       # Stage specific file
```

### Commit Changes
```bash
git commit -m "Your commit message"
```

### Push Changes to Remote
```bash
git push                 # Push to current branch
git push origin main     # Push to main branch
```

### Pull Latest Changes
```bash
git pull
```

### Create a New Branch
```bash
git branch <branch-name>
git checkout -b <branch-name>    # Create and switch to new branch
```

### Switch Branches
```bash
git checkout <branch-name>
```

### View Commit History
```bash
git log                  # View all commits
git log --oneline        # View commits in compact format
```

### Undo Changes
```bash
git restore <filename>        # Discard changes in working directory
git reset HEAD~1              # Undo last commit (keep changes)
git reset --hard HEAD~1       # Undo last commit (discard changes)
```

## Resources

- [Playwright Documentation](https://playwright.dev)
- [Playwright API Reference](https://playwright.dev/docs/api/class-playwright)

## License

This project is open source and available under the MIT License.

---

**Author:** playwrightAutomation  
**Repository:** https://github.com/rohit88kmr19/playwrightAutomation.git
