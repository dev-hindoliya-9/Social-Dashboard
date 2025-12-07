# Setup Instructions (Hindi/English)

## Problem: PowerShell Script Execution Disabled

Agar aapko "running scripts is disabled" error aa raha hai, to yeh solutions try karein:

## Solution 1: Batch Files Use Karein (Easiest) ✅

Maine 2 batch files banaye hain:

### Step 1: Install Dependencies
- `install.bat` file par **double-click** karein
- Ya right-click karke "Run as administrator" select karein
- Wait karein jab tak dependencies install ho jayein

### Step 2: Start Dashboard
- `start.bat` file par **double-click** karein
- Browser automatically open hoga ya manually `http://localhost:5173` par jayein

---

## Solution 2: Command Prompt (CMD) Use Karein

### Step 1: Command Prompt Open Karein
- Windows Key + R press karein
- Type karein: `cmd`
- Enter press karein

### Step 2: Project Folder Mein Jao
```cmd
cd "C:\Users\devhi\OneDrive\Desktop\DiabetesProject\social media dashboard"
```

### Step 3: Dependencies Install Karein
```cmd
npm install
```

### Step 4: Dashboard Start Karein
```cmd
npm run dev
```

---

## Solution 3: Fix PowerShell Execution Policy (Advanced)

Agar aapko PowerShell use karna hai:

1. **PowerShell ko Administrator ke roop mein open karein:**
   - Start menu se "PowerShell" search karein
   - Right-click karein
   - "Run as administrator" select karein

2. **Execution Policy Change Karein:**
   ```powershell
   Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
   ```

3. **Yes/Yes to All** select karein

4. **Phir normal terminal mein npm commands run karein:**
   ```powershell
   npm install
   npm run dev
   ```

---

## Quick Check: Node.js Installed Hai?

Command Prompt ya PowerShell mein type karein:
```cmd
node --version
npm --version
```

Agar version numbers dikhein, to Node.js installed hai ✅
Agar error aaye, to pehle Node.js install karein: https://nodejs.org/

---

## Troubleshooting

### Error: 'npm' is not recognized
- Node.js install nahi hai
- Node.js install karein: https://nodejs.org/
- Computer restart karein after installation

### Error: Port already in use
- Koi aur application port 5173 use kar rahi hai
- Ya pehle se server chal raha hai
- Terminal close karein aur phir se try karein

### Installation takes too long
- Normal hai, first time thoda time lagta hai
- Internet connection check karein

---

## Need Help?

Agar koi problem ho, to:
1. Screenshot share karein
2. Error message copy karein
3. Batches files use karke try karein

Good luck! 🚀

