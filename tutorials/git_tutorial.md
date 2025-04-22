# 🌱 Git Basics: A Quick Tutorial

This README walks you through the essential Git commands and workflow for contributing to a GitHub project. Perfect for beginners!

---

## 📦 1. Forking a Repository

A **fork** is a personal copy of someone else's project. You can make changes in your fork and propose them to the original repo.

### 🔧 How to fork:

1. Go to the repository on GitHub (https://github.com/nosportugal/nos-gen-ai-hackathon.git)
2. Click the **Fork** button at the top-right.
3. GitHub creates a copy of the repo under your account.

![My Feature](fork.png)

---

## 📥 2. Cloning Your Fork

To get started with your fork of the repository, you'll need to clone it to your local machine. Here’s how to do it using HTTPS:

🔗 Where to find the link:
1. **Navigate to Your Fork**:  
   Go to your GitHub account and find your fork of the repository. It will be listed under your username.
2. **Get the Clone URL**:  
   - Click the green **Code** button located near the top right of the repository page.
   - Ensure that the **HTTPS** option is selected (you can toggle between **HTTPS** and **SSH**).
   - Click the copy icon next to the URL to copy it to your clipboard. It will look like this:  
     `https://github.com/nosportugal/nos-gen-ai-hackathon.git`

![My Feature](clone.png)

3. **Open Your Terminal**:  
   Launch your terminal or command prompt.
4. **Navigate to Your Desired Directory**:  
   Use the `cd` command to change to the directory where you want to clone your fork. For example:
   ```
   cd path/to/your/directory
    ```
5. **Clone Your Repository**:
    ```
    git clone https://github.com/nosportugal/nos-gen-ai-hackathon.git

    cd repository-name
    ```

---

## 🌿 3. Creating and Switching to a Branch

Always create a new branch for your work to keep things organized.

```
git checkout -b my-feature-branch
```

---

## ✏️ 4. Making Changes & Committing

After making changes to your code:

1. Add your changes:
    ```
    git add .
    ```
2. Commit them with a meaningful message:
    ```
    git commit -m "Add feature: meaningful description"
    ```

---

## 🚀 5. Pushing to GitHub

Push your branch to your fork on GitHub:

```
git push origin my-feature-branch
```

---

## 📬 6. Opening a Pull Request (PR)

Once your branch is pushed:

1. Go to your fork on GitHub.
2. Click **"Compare & pull request"**.
3. Review your changes and submit the PR.
