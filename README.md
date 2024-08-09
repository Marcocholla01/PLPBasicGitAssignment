
---

# Hands-On Assignment: Basic Git and GitHub Workflow

## **Objective**

Familiarize myself with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

## **Requirements**

- A GitHub account (create one if you don't have it already).
- Git installed on my local machine.
- A code editor of my choice (e.g., Visual Studio Code, Sublime Text).

---

## **Task 1: Repository Setup**

### **1. GitHub Repository Creation**

- Log in to my GitHub account.
- Create a new repository on GitHub:
  - Go to [GitHub's New Repository Page](https://github.com/Marcocholla01).
  - Name my repository `PLPBasicGitAssignment`.
  - Initialize it with a README file.
  - Click "Create repository."

---

## **Task 2: Local Setup**

### **2. Local Folder Setup**

- Create a new folder on my local machine:
  - For example, create a folder named `PLPBasicGitAssignment`.
- Open a terminal or command prompt.
- Navigate to the created folder:
  ```bash
  cd C:\Users\MARCOCHOLLA\Desktop\powerLearnProject\software-dev\PLPBasicGitAssignment
  ```

### **3. Git Initialization**

- Initialize a new Git repository in my local folder:
  ```bash
  git init
  ```

### **4. Connecting to GitHub**

- Link my local repository to the GitHub repository you created in Task 1:
  ```bash
  git remote add origin https://github.com/Marcocholla01/PLPBasicGitAssignment.git
  ```

---

## **Task 3: Making Changes**

### **5. Create a File**

- Inside my local folder, create a new text file:
  - For example, create a file named `hello.txt`.
  - Add a simple text message to the file (e.g., "Hello, Git!").

### **6. Committing Changes**

- Stage the changes:
  ```bash
  git add hello.txt
  ```
- Commit the changes:
  ```bash
  git commit -m "Add hello.txt with a greeting"
  ```

---

## **Task 4: Pushing to GitHub**

### **7. Pushing to GitHub**

- Push the committed changes to my GitHub repository:
  ```bash
  git push -u origin main
  ```

---

## **Task 5: Verification**

### **8. Verify on GitHub**

- Visit my GitHub repository in a web browser:
  - Confirm that the `hello.txt` file and the commit message are visible.

---

## **Submission**

- Ensure all changes are pushed to my GitHub repository.
- Share the link to my GitHub repository with the instructor or submit it as per the class instructions.

---

## **Additional Tips**

- Document the steps and commands used in a text file or in the README of my repository.
- For example, you can add the following to my README file:

  ```markdown
  ## Git and GitHub Workflow

  ### Steps Taken

  1. Created a GitHub repository named `PLPBasicGitAssignment`.
  2. Initialized a local Git repository.
  3. Connected the local repository to the GitHub repository.
  4. Created a file `hello.txt` with a greeting.
  5. Committed the changes with the message "Add hello.txt with a greeting."
  6. Pushed the changes to GitHub.
  7. Verified the presence of `hello.txt` and the commit message on GitHub.
  ```
