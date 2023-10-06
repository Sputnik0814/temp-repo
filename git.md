# Git

## Changes vs. Snapshots
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/596f7277-4c2d-46e1-95fc-70649121bab8)

## Local, Centralized, and Distributed Version Control
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/1f0d7a9c-5a8f-41f3-8d01-b4d11fc5fb04)

## Three Staes in Git
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/aba6ae78-c537-407c-a456-acc67cbb3f77)

## Git config: First-time setup
- Git configurations are stored in three levels:

(1) System level: --system option. Affects all uses and repositories on the system (administrative)

    file: /etc/gitconfig

(2) Global (user) level: --global option. Affects all repositories of a current user

    file: ~/.config/git/config

(3) Local level: --local option. Specific to the current repository
    
    file: .git/gitconfig

* Each level overrides values in the previous level: system -> global -> local
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/01ddab4d-ec24-48a0-a0ae-9820c76774a2)
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/db8ee0f9-f235-4af9-8143-786d18d9431b)

## Initializing a Repository in an Existing Directory
$ git init
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/2dedf63b-a497-4b5e-9201-cb5c8db1cea4)

## Checking Repository Status
$ git status
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/9a7a4912-2f4d-40f9-b378-f85481a58b47)

## Adding a new file to be staged (tracked)
$ git add [file_name]
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/b94f29a4-711b-41c0-8541-db2a7796b189)

$ git add [file_name]
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/fbd4e5ff-476f-4e85-b80b-19b8a35f65c9)
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/3d254f43-9fc5-46c5-bb93-0edb5ab12ca1)
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/73ec7be3-e479-44ad-830f-b8bbb5fd00aa)

$ git add .

![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/c7bc6eb4-235c-42a2-9597-5be2c758e638)


## Unstaging a file
$ git rm –cached [file_name]
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/9f714d6f-ac6c-465e-a3cd-53c28fd29c2b)


## Ignoring a file
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/ca56b1ea-09a0-49e2-9483-a580f7f8117e)
.gitignore file
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/9e34e3c4-7ad0-4a73-b870-d78de3e61ab2)

## Commit
$ git commit -m “commit message”
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/d4742396-262d-4ded-ac65-a16c8e7c3bdc)


## Change branch name
![image](https://github.com/Sputnik0814/temp-repo/assets/143800230/c798662e-acc3-4eef-b9b6-ebacd6621a90)
