# Git and GitHub Team Practice

Welcome to our Git and GitHub practice repository! We will build a **Team Handbook** while learning how to track changes, review contributions and collaborate.

You do not need to write code for these exercises. Most activities use the GitHub website. The final activity uses GitHub Desktop or the Git command line.

## What you will learn

By the end of the session, you should be able to:

- Find branches, commits, issues and pull requests.
- Create a branch and commit a focused change.
- Open a pull request and respond to feedback.
- Review and merge a colleague’s contribution.
- Connect a completed contribution to an issue.
- Explain and demonstrate clone, commit, push and pull.

## Before you begin

1. Sign in to your GitHub account.
2. Confirm that you have write access to this repository. Ask the facilitator if you cannot create a branch.
3. Find a partner. Switch the person controlling the computer halfway through the session.
4. For the local exercise, install GitHub Desktop or Git and connect your account.

**Facilitator setup:** Give participants repository access before the session. Keep exercises in this practice repository and make sure participants can merge their reviewed pull requests, or arrange for the facilitator to merge them.

## Session schedule

| Time | Activity |
| --- | --- |
| 10 minutes | Opening questions and vocabulary |
| 10 minutes | Dashboard scavenger hunt |
| 10 minutes | Introduce yourself on a branch |
| 10 minutes | Review a colleague’s contribution |
| 15 minutes | Complete an issue |
| 15 minutes | Connect GitHub to local Git |

## Our working agreements

- Create a branch for each task and propose changes through a pull request.
- Keep each contribution focused on one task.
- Use clear branch names, commit messages and pull request descriptions.
- Read the changed files before approving or merging.
- Give specific, respectful feedback.
- Ask for help if you are unsure which branch you are editing or merging into.
- Use fictional or non-sensitive information in practice files.

## Activity 1 Dashboard scavenger hunt

Find these items in this repository:

- [ ] The README you are reading now.
- [ ] The current branch and branch selector.
- [ ] The latest commit and its author.
- [ ] The README’s change history.
- [ ] The Issues tab.
- [ ] The Pull requests tab and its open and closed filters.

**Discuss:** Where would you look to understand what changed, who changed it, and why?

**Complete when:** You can show your partner each item and explain its purpose. An empty Issues or Pull requests tab is fine—we will add items during the workshop.

## Activity 2 Introduce yourself on a branch

1. Open the branch selector and create a branch from `main` named `intro/your-name`, for example `intro/lesedi`.
2. Confirm that your new branch is selected.
3. Use **Add file → Create new file** and enter `team/your-name.md` as the filename. The slash creates the `team` folder when the file is committed.
4. Copy the template below and replace the example information.
5. Commit the file to your new branch with a message such as `Add Lesedi team introduction`.
6. Open a pull request from your branch into `main`. You can use **Compare & pull request**, or **Pull requests → New pull request**.
7. Give the pull request a clear title and describe what you added. Leave it open for your partner to review.

```markdown
# Your name

- Role: Your role
- Favourite AI tool: Your tool
- Daily goal: One thing you want to learn about Git or GitHub
```

**Complete when:** Your introduction exists on your branch and your pull request is open.

**Discuss:** Why has your file not yet appeared on `main`?

## Activity 3 Review relay

1. Open your partner’s pull request and read its description.
2. Open **Files changed** and check that the contribution matches the task.
3. Leave one useful comment, for example: “Please explain what you would like to learn about reviewing pull requests.”
4. The author edits the file on the **same branch** and commits the improvement. The existing pull request will include the new commit.
5. The reviewer checks the update and approves it if permissions allow.
6. Merge the pull request when it is ready. Ask the facilitator for help if merging is restricted.
7. Return to the repository, select `main`, and confirm that the introduction appears.

**Complete when:** The file appears on `main` and the pull request contains feedback and a follow-up change.

**Discuss:** What did the review improve? Why should you inspect the actual changes before merging?

## Activity 4 Complete an issue

Each pair chooses one task. Coordinate with the facilitator so pairs work on different files.

| Task | Suggested file | Expected contribution |
| --- | --- | --- |
| Add onboarding instructions | `handbook/onboarding.md` | A short checklist for new colleagues |
| Add meeting guidelines | `handbook/meetings.md` | Five useful team meeting rules |
| Explain the handbook | `handbook/about.md` | Describe its purpose and intended readers |
| Add a Git glossary | `handbook/git-glossary.md` | Define five common Git terms |

1. Create an issue with a clear title and description of the expected result.
2. Assign an owner. If assignment is unavailable, name the owner in the issue description.
3. Create a branch from the latest `main`, such as `docs/onboarding-your-name`.
4. Add the agreed content and commit your changes.
5. Open a pull request into `main`. Include the actual issue number in the description, for example `Related to #3`.
6. Ask your partner to review it, respond to feedback, and merge when ready.
7. Confirm that the work meets the issue’s requirements, then close the issue if it is still open.

**Complete when:** Another colleague can trace the finished contribution back to the original task.

## Activity 5 Connect GitHub to local Git

Use GitHub Desktop or the Git command line. The facilitator can demonstrate the steps first.

1. Clone this repository onto your computer.
2. Create a branch from the latest `main` named `local/your-name`.
3. Edit your introduction file locally, adding one thing you learned during the workshop.
4. Commit the change locally.
5. **Before pushing**, check the repository on the GitHub website. Can you see your new commit there?
6. Push or publish your branch, then check GitHub again.
7. Open a pull request, ask your partner to review it, and merge when ready.
8. In your local repository, switch to `main` and pull the updated changes.

**Complete when:** You can show the change on GitHub and in your updated local `main` branch.

**Discuss:** Why could your colleague not see your local commit before you pushed it?

## Git vocabulary

| Term | Meaning |
| --- | --- |
| Git | A version control tool that tracks changes |
| GitHub | A service that hosts Git repositories and supports collaboration |
| Repository | A project’s files and version history |
| Branch | A separate line of work within a repository |
| Commit | A recorded snapshot of changes in Git history |
| Clone | Make a local copy of a repository |
| Push | Send local commits to the remote repository |
| Pull | Fetch and integrate remote changes into your current local branch |
| Pull request | A proposal to review and merge changes from one branch into another |
| Merge | Integrate changes from another branch |
| Issue | A place to describe and discuss a task, bug or idea |
| Merge conflict | A situation where Git cannot automatically reconcile competing changes |

## Discussion questions

Discuss these with your partner before opening the answer guide.

1. What is the difference between Git and GitHub?
2. Why do we use branches?
3. Is saving a file the same as committing it?
4. Does a local commit automatically appear on GitHub?
5. Is a pull request the same as a pull?
6. What makes a useful commit message?
7. What should you inspect before merging?
8. What causes a merge conflict?

<details>
<summary>Open the answer guide</summary>

1. Git tracks versions; GitHub hosts repositories and supports collaboration.
2. A branch lets you work on changes separately before integrating them.
3. No. Saving changes the file; committing records a snapshot in Git history.
4. No. You need to push a local commit to the remote repository.
5. No. A pull request proposes a merge; pull updates a local branch from a remote.
6. It clearly describes the change so others can understand it.
7. Inspect the changed files, review feedback and any relevant checks.
8. A conflict occurs when Git cannot automatically reconcile competing changes.

</details>

## Optional follow up Merge conflict challenge

With your facilitator, create two branches from the same starting commit and change the same line in a practice file to different text. Open a pull request for each branch and merge the first one. Inspect and resolve the conflict in the second, keeping the agreed final text. Review and merge the result.

## Completion checklist

Each participant should be able to complete these actions without their partner taking over:

- [ ] Navigate branches, commits, issues and pull requests.
- [ ] Create a branch and commit a focused change.
- [ ] Open a pull request and respond to feedback.
- [ ] Review and merge a contribution.
- [ ] Connect completed work to an issue.
- [ ] Clone a repository and demonstrate commit, push and pull.

Finish by showing your partner one complete contribution: **task → branch → commit → pull request → review → merge**.

## Reference guides

- [GitHub Hello World](https://docs.github.com/en/get-started/using-github/hello-world)
- [Getting started with GitHub Desktop](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop)
- [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
- <b>Resources<b>:
  <ul>
    <li>https://youtu.be/tRZGeaHPoaw?si=DWW0-jMsnwXl4kBg<li>
    <li>https://youtu.be/h2a3Kw-I_Ec?si=YuCyeDSGbVBp3j0j<li>
    <li>https://youtu.be/vA5TTz6BXhY?si=TKy67E8q6ZI1chp6<li>
    <li>https://youtu.be/4okmgMzPwZ8?si=ZZFDxw1WtGeXWT5K<li>
    <ul>
