# KSR-YK-JFS-NOV2026-ASSIGNMENTS

Java Full Stack, November 2026. This repo is only for **assignment submissions**.

Class code that the trainer types live is a different repo. Do not put class notes or the trainer's programs here.

This repo is public, so anyone can read it. You submit by opening a pull request, then pasting that link into PAMS. A direct push to `main` is rejected.

## Submit an assignment

1. Accept the GitHub invite, if you have not already.
2. Clone this repo and start from an updated `main`:

   ```bash
   git clone https://github.com/kyedumati/KSR-YK-JFS-NOV2026-ASSIGNMENTS.git
   cd KSR-YK-JFS-NOV2026-ASSIGNMENTS
   git checkout main
   git pull
   ```

3. Create a branch named `your-github-login/task-slug`. The task slug is the one written in the PAMS brief. Example: `RithwikReddy009/01-hello`.

   ```bash
   git checkout -b your-github-login/task-slug
   ```

4. Put your files only in this folder:

   ```text
   students/your-github-login/task-slug/
   ```

   Use your GitHub login, the same spelling as on github.com. Do not edit another student's folder. Do not commit `.class` files, `target/`, or `.idea/`.

5. Commit, push the branch, and open a pull request **into `main`**.

   ```bash
   git add students/your-github-login/task-slug
   git commit -m "01-hello"
   git push -u origin your-github-login/task-slug
   ```

   On GitHub, open the pull request. The base branch must be `main`.

6. Copy the pull request link and paste it into the assignment on PAMS. That hand-in is what the trainer marks.

`main` does not accept a direct push. Use a branch and a pull request, including when you use **Add file** on the GitHub website.

## Trainer

- Students are collaborators with **Write**. Only the trainer is an admin.
- `main` requires a pull request. Direct pushes are blocked for students. The trainer can still push the brief and this README.
- Marking happens in PAMS. Merging the pull request puts the work on `main` so the batch can read it.
- A pull request that changes files outside `students/<their-login>/<task-slug>/` goes back to the student.
