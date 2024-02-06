# Exercise 01: Git

## Title: Create your first Pull Request

### Type: Individual Assessment

### Score: Pass or Fail (10 Points)

#### Helpful Material for this Exercise: [Creating a Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

---

### Before the Exercise:

1. Find a partner to collaborate with. Add them as a collaborator in your GitHub repository.

2. You and your partner must clone your own GitHub classroom exercise 1 repository called “create-your-first-pull-request-<username>”. Note: Kindly disregard the feedback branch.

3. On your local repository, create a text file called "expectations.txt" and push it to your GitHub remote repository. You must add something inside "expectations.txt," particularly your expectations about your journey in CMSC 100.

---

### For this Activity:

#### As a Creator:

1. Clone your partner’s repository using the git clone command to duplicate their repository on your local machine.

2. While working with your partner’s repository, create a new branch with your surname as the branch name. Make changes to the cloned repository by editing their “expectations.txt”, ideally to express agreement or disagreement with your partner's thoughts.

3. Commit your changes from your partner’s repository with a descriptive commit message: 
   ```
   git commit -m “chore: Agreed with your expectations”
   ```

4. Push your changes to your partner’s repository.
   ```
   git push origin surname
   ```

#### As a Reviewer:

1. Visit your repository.

2. Select "New Pull Request" from the menu.

3. Choose the base repository and branch (typically the original repository's default branch).

4. Choose the "compare" branch to be your branch.

5. Give your pull request a clear title and description.

6. Select "Create Pull Request" from the menu.

7. Examine the pull request and, as necessary, provide comments or approvals.

8. Integrate the pull request into the basic repository if you're happy with the changes.

---

#### Result:

Your Repository (Student A):
- Branch: main

Your Partner’s Repository (Student B):
- Branch: Student A’s surname

Your Partner’s Repository (Student B):
- Branch: main

Your Repository (Student A):
- Branch: Student B’s surname
