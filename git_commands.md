# the three important git commands are

- git add
- git commit -m "anything"
- git push


# github_basics



# Pull Project from GitHub to VS Code

### 1. Open Terminal in VS Code

### 2. Clone the Repository

```bash
git clone <repository-url>
```

### 3. Move into the Project Folder

```bash
cd <repository-name>
```

### 4. Pull the Latest Changes (Optional)

```bash
git pull origin main
```

> Replace `main` with `master` if your repository uses the master branch.



# Push Project from VS Code to GitHub

### 1. Open Terminal in VS Code

### 2. Initialize Git

```bash
git init
```

### 3. Add All Files

```bash
git add .
```

### 4. Commit Files

```bash
git commit -m "Initial commit"
```

### 5. Connect GitHub Repository

```bash
git remote add origin <repository-url>
```

### 6. Set Main Branch

```bash
git branch -M main
```

### 7. Push to GitHub

```bash
git push -u origin main
```


