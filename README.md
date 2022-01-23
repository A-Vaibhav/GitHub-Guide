# Way i Learned GitHub

Things i have learnt, Problems and Errors i have faced

# Scenario :- Create local project folder, now wanted to add the project dir to github.

1. Create repository in Github and copy the ssh or http link from clone secion.
2. Go in local Project directory, open Terminal and run following command :-
    create git repository
    ```
    git init
    ```
    ```
    git status
    ```
    ```
    git remote add origin  git@github.com:username/your_directory.git
    ```
    ```
    git add .
    ```
    ```
    git commit -m 'first commit'
    ```
    ```
    git branch -m master main
    ```
    ```
    git pull origin main --rebase
    ```
    ```
    git push origin main
    ```
3. check everythings upto date with 'git status' and you are all set.
