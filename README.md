# GIT HANDS ON
## Short brief:
1. `.gitignore`
2. This project

## important GIT commands:
1. clone the project
    ```bash
    git clone https://github.com/<username>/<project>.git
    ```
2. check out to a new branch
    ```bash
    git checkout -b <branch-name> 
    ```
3. do some changes
    ```bash
    👨‍💻 CODE 👩‍💻
    ```

4. check status
    ```bash
    git status
    ```
4. add changes
    ```bash
    git add <file-name>
    # --- OR ---
    git add .
    ```
5. commit the changes
    ```bash
    git commit -m <meaningful-message>
    ```
6. push the chenges to the remote
    ```bash
    git push origin <branch-name>
    ```
(there will be continue)

## important GITHUB actions:
1. Open a `PR`
2. Where are we going to write a `CR`?
3. Resolve comments on review and make a discussion.

## important GIT commands - continue:
7. keep updated - on my branch
    ```bash
    git checkout main
    git pull 
    git checkout <branch-name>
    git merge main
    ```
8. resolve some conflicts
    ```bash
    # [looks like:]

    <<<<<< HEAD
    // Code from your branch
    =======
    // Code from the other branch
    >>>>>> main
    ```
9. Push your changes again: (see 4-6)
10. merge
    ```bash
    git merge <branch-name>
    ```