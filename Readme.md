This project is a collection of linux commands and their usage

## How to contribute

Fork this repository by clicking on the fork button on the top of this page. This will create a copy of this repository in your account.

![Screenshot from 2021-10-01 22-49-41](https://user-images.githubusercontent.com/56548922/135661426-212d2b42-d1e7-4802-b3e1-3f7a233316a5.png)


## Clone the repository

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the copy to clipboard icon.

![Screenshot from 2021-10-01 22-51-22](https://user-images.githubusercontent.com/56548922/135661678-02abdf2d-2db2-42be-bcd1-c65a6093dfc6.png)


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
You can also add more information about previously added commands by updating their files in `command` foldes

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing <add-your-branch-name> with the name of the branch you created earlier.

## Create a Pull Request

If you go to your repository on GitHub, you'll see a `Compare & pull request` button.
![Screenshot from 2021-10-01 22-59-49](https://user-images.githubusercontent.com/56548922/135662653-7d38ebb2-1caa-4afd-89e4-066f54e36826.png)

Now submit the pull request.
![Screenshot from 2021-10-01 23-03-03](https://user-images.githubusercontent.com/56548922/135663046-58455754-f140-4e47-9724-97c0d36556f4.png)

Soon I'll review and merge all your changes into the master branch of this project. You will get a notification email once the changes have been merged.

