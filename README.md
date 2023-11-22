# How to Open a Pull Request on GitHub

> Note: Pull requests can technically be done without knowledge of Git, especially for small typo fixes, etc. that can be done completely in the browser. For bigger (code) changes, I recommend first learning [how to Git](https://github.com/avidrucker/how-to-git) on your computer locally.

## 1. Introduction to Pull Requests
- **What is a Pull Request?** A pull request (PR) is a method to submit contributions to a project on GitHub. It's how you propose changes and request that someone reviews and pulls your contribution into their branch.
- **Purpose:** Pull requests are central to collaboration in GitHub. They allow you to share your changes, discuss improvements, and collaborate with others.

## 2. Find a Project to Contribute To
- Explore GitHub to find a project you're interested in.
- Look for projects with a `CONTRIBUTING.md` file, as it often provides guidelines on how to contribute.

## 3. Fork the Repository
- **Forking:** Click the "Fork" button at the top-right of the repository page to create a copy of the project in your account.
- This allows you to freely experiment with changes without affecting the original project.

## 4. Clone the Forked Repository
- **Cloning:** Clone the forked repository to your local machine.
  ```bash
  git clone [URL of the forked repository]
  ```
- This step requires Git installed on your computer. See [How to Git](https://github.com/avidrucker/how-to-git) for instructions on how to install Git.

## 5. Create a New Branch
- Navigate into the cloned repository on your machine.
- Create a new branch for your changes:
  ```bash
  git checkout -b [new-branch-name]
  ```
- Keeping your changes in a separate branch allows for easier management and isolation of your contributions.

## 6. Make Your Changes
- Edit, add, or delete files in your local repository as necessary.
- Ensure your changes are aligned with the project's contribution guidelines.

## 7. Commit and Push Your Changes
- Commit your changes locally:
  ```bash
  git commit -m "Add a descriptive message about your changes"
  ```
- Push the changes to your forked repository on GitHub:
  ```bash
  git push origin [new-branch-name]
  ```

## 8. Open a Pull Request
- Go to your forked repository on GitHub.
- Click on "Pull requests" > "New pull request."
- Select your branch.
- Click "Create pull request."
- Add a title and description for your pull request.
- If the repository has a template for pull requests, fill it out to provide the necessary information.

## 9. Review and Submit
- Review your changes to ensure they are correct and complete.
- Submit the pull request.

## 10. Collaborate and Update
- Maintainers of the original repository might request changes. Be ready to collaborate.
- You can make additional changes in your branch and push them; they'll automatically show up in your pull request.
