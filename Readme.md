This projectos a collection of linux commands and their usage

## How to contribute

Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1632022983880/1cdrf-4y_.png)

## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1632023586276/2i0gB3t4X.png)

Open a terminal and run the following git command:

```
git clone 'copied-url'
```

For example:

```
git clone https://github.com/YOUR-USERNAME/repo-name.git
```

## Creating a new branch

Change the current working directory to the location ofyou the cloned directory using

```
cd Linux-Commands
```

Now create a branch using the `git checkout` command:

```
git checkout -b 'branch-name'
```

## Make changes to the files

Now open `commands.md` and see which command is not added in the list.

Afer this add a file with in form of `commandName.md` in the commands folder explaning the usage of the command.

Finally add the linux-command that you explained with the link to the file under the section represented by the first of the command.

Example:

```
Filename: ls.md

Add in commands.md: [ls](url-of-ls.md)
```

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing <add-your-branch-name> with the name of the branch you created earlier.

## Create a Pull Request

If you go to your repository on GitHub, you'll see a `Compare & pull request` button.
