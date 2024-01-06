# Important command which you should know in industry

**Follow these steps when merge commit issue**

**Move to the previous commit on which you want to add your code for good commit history**

```shell
This is the commit id for tester on the top of that I need to add my code.

```
```shell
1. git reset --hard previous-commit-id
2. git status

```
**Clean all the steps for instance .idea folder using command**
```shell
git clean -fd

```

**Now fetch the develop branch and rebase it with the commit id which we have mentioned in step1 *

```shell
git fetch origin develop
git rebase origin/develop

```

**Now added your changes that you want to add with good commit history**
```shell
git add docs && git commit -m "docs(architecture): updated the puml file CX-656"

```

**Forcefully push the changes**
```shell
git push --force origin fature/CX-656

```
```shell
Here is the screenshot of the commands which I am using currently.
```

![Alt Text](image/img1.jpeg)


