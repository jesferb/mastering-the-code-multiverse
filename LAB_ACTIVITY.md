# 🚀 Lab Activity: The Code Multiverse Challenge

**Total Duration:** 4 Hours (240 Minutes)  
**Target Audience:** IT College Students  
**Mission:** Transition from a "Local Developer" to a "Global Contributor" by navigating the Git workflow.

---

## 🏁 Mission 1: The Forge (Environment Setup)

**⏱️ Suggested Time:** 45 Minutes  
**Objective:** Prepare your workstation and establish your digital identity.

### 1.1 Tool Checklist (30 Mins)

Ensure your machine is equipped with the following. If missing, acquire them from their official sources:

1. **Git Engine:** (Verify via terminal using a version check command).
2. **The Editor:** VS Code.
3. **The Cloud Vault:** A registered GitHub account.

### 1.2 Establish Identity (15 Mins)

Git needs to "sign" every save point you create.

- **Task:** Configure your global settings so your name and email are attached to every commit.
- **Critical Thinking:** Why is it important to use the same email address here as the one on your GitHub account?

---

## 🕒 Mission 2: Tracking Time (Local Workflow)

**⏱️ Suggested Time:** 60 Minutes  
**Objective:** Move a project through the "Three Stages of Git."

### 2.1 The Project Start (15 Mins)

1. Create a workspace named `multiverse-lab`.
2. Inside, create a file named `profile.md` containing a brief professional bio.

### 2.2 The Three-Stage Loop (30 Mins)

Your goal is to successfully take a "Snapshot" of your work.

- **Task A (Initialize):** Tell Git to start watching this folder.
- **Task B (Staging):** Move your file to the "Outbox" (Staging Area).
- **Task C (Commit):** Permanently seal the vault with a descriptive message.
- **Observation:** Run a status command after each task. What changes in the terminal output at each step?

### 2.3 The Time Machine (15 Mins)

1. Add a "Technical Skills" section to your bio.
2. Use a command to see exactly what lines were added/removed before you save.
3. Commit this change as a new version.

---

## 🕒 Mission 3: The Multiverse (Branching & Conflicts)

**⏱️ Suggested Time:** 75 Minutes  
**Objective:** Manage parallel versions of a project and resolve timeline clashes.

### 3.1 Divergent Timelines (30 Mins)

Imagine a client wants a "Dark Mode" version of your profile, but you must keep the "Standard" version safe.

- **Task:** Create a new branch named `feature-dark-mode` and switch to it.
- **Modification:** Change the text style/content in `profile.md` to reflect a "Dark Theme." Commit this change.
- **The Jump:** Switch back to the main branch.
- **Critical Thinking:** What happened to the "Dark Mode" text you just wrote? Is it gone?

### 3.2 The Timeline Clash (Merge Conflict) (45 Mins)

1. Stay on the `main` branch. Change the first line of your bio and commit it.
2. Now, attempt to merge `feature-dark-mode` into `main`.
3. **The Incident:** You should see a "Merge Conflict" error.
4. **The Surgery:** Open VS Code. Look for the conflict markers.
   - **Task:** Manually edit the file to combine both versions into a perfect final draft. Finish by "sealing" the resolution with a final commit.

---

## 🕒 Mission 4: Social Coding (GitHub & Collaboration)

**⏱️ Suggested Time:** 60 Minutes  
**Objective:** Connect your local work to the cloud and contribute to a team project.

### 4.1 Creating the Remote Vault (25 Mins)

1. Create a new repository on GitHub.
2. **Task:** Link your local `multiverse-lab` folder to this new GitHub repository.
3. **Task:** "Push" your local history to the cloud. Verify that your code is now visible on your GitHub profile.

### 4.2 The Team Raid (Collaborative Guestbook) (35 Mins)

You are now going to contribute to the "Global Guestbook" hosted by the speaker.

1. **Find the Target:** Navigate to the Speaker's repository URL.
2. **The Fork:** Create your own cloud-copy of the project.
3. **The Clone:** Bring your copy down to your laptop.
4. **The Contribution:** Add a unique file with your name to the `Global Guestbook` directory.
5. **The Pull Request:** Push your change to your GitHub copy, then send a "Pull Request" to the Speaker's original project.

---

## ✅ Mission Completion Checklist

- [ ] I can verify my Git version in the terminal.
- [ ] I have at least 3 unique "save points" (commits) in my project history.
- [ ] I successfully jumped between two parallel branches.
- [ ] I manually fixed a merge conflict without deleting the whole folder.
- [ ] My code is live on GitHub and I have sent a Pull Request to the speaker.

---

> *"In the Multiverse of Code, Git is your anchor. Master the workflow, and you master the industry."*
