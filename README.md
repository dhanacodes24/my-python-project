# Git & GitHub Assessment  

**Duration:** 30 Minutes  

---

## Question 1: Project Initialization & First Push  

### Objective  
Set up a new Git project and push it to a remote repository.  

### Scenario  
You are starting a new Python project. You need to track your work using Git and upload it to a remote repository.  

### Tasks  
1. Create a new folder for your project

<img width="1372" height="289" alt="image" src="https://github.com/user-attachments/assets/e5f7d162-d9d2-4fa6-a7e5-d66da49edf1c" />



3. Initialize a Git repository
   <img width="941" height="137" alt="image" src="https://github.com/user-attachments/assets/d5d18798-760b-470a-8d2d-8d1d6d01024a" />

5. Create a file named `app.py` and add some Python code
   <img width="2238" height="616" alt="image" src="https://github.com/user-attachments/assets/19a74aeb-fefc-4ad4-b831-ee1b200c47fc" />

7. Check the current Git status
   <img width="1980" height="378" alt="image" src="https://github.com/user-attachments/assets/12d89128-6b20-465b-869e-e079d24e7cc4" />

9. Stage the file

   <img width="1794" height="352" alt="image" src="https://github.com/user-attachments/assets/18dec46a-ae86-4541-bb2f-0e0cc49103ec" />
    
12. Commit with a meaningful message
    <img width="1918" height="304" alt="image" src="https://github.com/user-attachments/assets/6b3b3e98-2ed1-4d19-a41b-da70c0392e3e" />

14. Create a remote repository (GitHub or similar)
  <img width="1439" height="583" alt="image" src="https://github.com/user-attachments/assets/4c03433a-06ac-48fc-aac1-c022f97cebaa" />

16. Add the remote (`origin`) to your local repo

 <img width="2562" height="172" alt="image" src="https://github.com/user-attachments/assets/0b0e3d9d-6ffd-4baa-bacb-7a389c05dd91" />

    
18. Verify the remote configuration
    <img width="2788" height="234" alt="image" src="https://github.com/user-attachments/assets/612b35ad-55b6-45b5-b563-a04495fd9379" />

20. Push your code to the remote repository

<img width="1658" height="370" alt="image" src="https://github.com/user-attachments/assets/547679b3-4976-4a33-88d3-200b077d37f7" />

<img width="2124" height="702" alt="image" src="https://github.com/user-attachments/assets/b184ae18-12e1-4eac-b5ea-3f39eb8e25b6" />

---

## Question 2: Working with Changes & History  

### Objective  
Track code changes and manage commit history properly.  

### Scenario  
You are enhancing your existing `app.py` application with new features.  

### Tasks  
1. Modify `app.py` by adding new functionality
   <img width="1594" height="436" alt="image" src="https://github.com/user-attachments/assets/bcac8985-6bd9-410e-ad2f-7b4b128ea0d0" />

3. Check what changes are made before staging
   <img width="1898" height="352" alt="image" src="https://github.com/user-attachments/assets/696a3d35-f8ee-462a-8484-3d8625e02dfb" />

4. View differences in the file

    <img width="1874" height="592" alt="image" src="https://github.com/user-attachments/assets/fb493a18-cce5-43cd-9522-f6b9d68ca948" />

6. Stage only specific changes (if possible)
   <img width="1606" height="578" alt="image" src="https://github.com/user-attachments/assets/06cf391f-3f60-4f1a-a50c-4b27a243f1ed" />

8. Commit with a clear message
   <img width="1986" height="258" alt="image" src="https://github.com/user-attachments/assets/5027436c-a2bb-4411-aa17-f46112e5c102" />

10. Make another change in `app.py`
    <img width="1364" height="380" alt="image" src="https://github.com/user-attachments/assets/67dc3130-7db3-44d1-968b-96d14faa9d36" />

12. Stage all changes
    <img width="1552" height="112" alt="image" src="https://github.com/user-attachments/assets/2a25f107-01c0-4be3-ba94-04f3409b66bf" />

14. Commit again
    <img width="1552" height="112" alt="image" src="https://github.com/user-attachments/assets/1d55af02-0547-4887-ab8b-7e6012b915e2" />

16. View full commit history
    <img width="965" height="359" alt="image" src="https://github.com/user-attachments/assets/b66443b7-4a0c-41b5-accc-c655444c8f59" />

18. View compact (one‑line) history  

<img width="1646" height="324" alt="image" src="https://github.com/user-attachments/assets/98abac79-cf9c-4389-8a77-628330bf40ec" />

---

## Question 3: Branching & Feature Development  

### Objective  
Work with branches and manage feature development.  

### Scenario  
You are developing a new feature separately to avoid affecting the main code.  

### Tasks  
1. Create a new branch (e.g., `feature-update`)  
2. Switch to the new branch  
3. Modify `app.py` with new feature logic  
4. Stage and commit the changes  
5. Switch back to the `main` branch  
6. Merge the feature branch into `main`  
7. Verify changes are merged  
8. Delete the branch safely  
9. Try force deleting a branch (create a dummy branch for this)  

---

## Question 4: Handling Errors (Stash, Reset, Revert)  

### Objective  
Learn how to manage mistakes and unfinished work.  

### Scenario  
You are in the middle of development but need to handle urgent changes and fix mistakes.  

### Tasks  
1. Make changes to `app.py` but do **NOT** commit  
2. Stash the changes (include untracked files)  
3. Check the stash list  
4. Apply the stashed changes back  
5. Commit the changes  
6. Make another commit with incorrect code  
7. Undo the last commit using **reset**  
8. Make another commit  
9. Undo a commit using **revert** (create a new reversing commit)  
10. Verify the commit history  

---

## Pro Tips  
- Use **meaningful commit messages** (e.g., `feat: add login function`, `fix: resolve bug in app.py`).  
- Keep branches **feature‑focused** and merge often to avoid conflicts.  
- Practice **stash, reset, revert** to build confidence in handling mistakes.  

---

Designed for **hands‑on Git & GitHub mastery** 🚀
