# Basic Git Commands for Tom & Jerry

## Adding Changes
```sh
# Check status of changes
git status
```
![Git Status](./img/git%20status.png)

```sh
# Add specific files to the staging area
git add index.html
```
![Git Add](./img/git%20add%20index.png)

## Committing Changes
```sh
# Commit changes with a meaningful message
git commit -m "Update navigation bar"
```
![Git Commit](./img/navbar%20commit.png)

## Creating and Switching Branches
```sh
# Create and switch to a new branch
git checkout -b add-contact-info
```
![Git Branch](./img/jerry%20banch%20created.png)

## Staging and Committing Changes
```sh
# Add specific files to the staging area
git add index.html
```
![Git Add](./img/jerry%20content.png)

```sh
# Commit changes with a descriptive message
git commit -m "Add contact information"
```
![Git Commit](./img/jerry%20commit.png)

## Pushing Changes
```sh
# Push the new branch to the remote repository
git push origin add-contact-info
```
![Git Push](./img/jerry%20push.png)

## Best Practices
- Always pull the latest changes before starting work.
- Use clear and descriptive commit messages.
- Keep branches well-organized and regularly clean up merged branches.
- Resolve conflicts carefully and test changes before pushing.

**Happy Coding! 🚀*