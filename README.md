# Simple Boot Base Template (Starter Template)

This is a quick template for creating a base project based on simple-boot-parent-java.
You may change parent to parent-java-web-jpa if you need to create a web project based on Rest and JPA.

You may follow one of the below options to make a copy of this repository and start working.

## Option 1
1. Fork repository
1. Change repository name
1. Clone the new repository to local
1. Use Refactor option in IDEs to change module name, package and Application name.
1. Update POM file.
1. Update contents of the readme file.
1. Run './mvnw clean compile' to make sure everything is fine.
1. Commit and push new changes


## Option 2
1. git clone https://github.com/heartin/simple-boot-base-template
1. cd simple-boot-base-template <br>
Note: You may change the folder name and then do cd into that folder: <br>
mv simple-boot-base-template new-repository-name <br>
cd new-repository-name <br>
1. git remote set-url origin new-repo-url <br>
1. git push origin master
Note: You may also make changes and then push using the above command in the end.
1. Use Refactor option in IDEs to change module name, package and Application name.
1. Update POM file.
1. Update contents of the readme file.
1. Run './mvnw clean compile' to make sure everything is fine.
1. Commit and push new changes


## Option 3
```
git clone --bare https://github.com/heartin/simple-boot-base-template.git
cd simple-boot-base-template
git push --mirror https://github.com/<user>/<new-repository>.git
```
Substitute <user> and <new-repository> with actual user and new repository name.
Reference: https://help.github.com/articles/duplicating-a-repository/

Later,
1. Clone new repo.
1. Use Refactor option in IDEs to change module name, package and Application name.
1. Update POM file.
1. Update contents of the readme file.
1. Run './mvnw clean compile' to make sure everything is fine.
1. Commit and push new changes


**IMP!** Make sure you change this readme file.