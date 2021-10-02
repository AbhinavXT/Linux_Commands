# git

## git config

**This command sets the author name and email address respectively to be used with your commits.**

```python
git config –global user.name “[name]”
git config –global user.email “[email address]”
```

## git init

**This command is used to start a new repository.**

```python
git init [repository name]
```

## git clone

**This command is used to obtain a repository from an existing URL.**

```python
git clone [url]
```

## git add

**This command adds a file to the staging area.**

```python
git add [file]
```

**This command adds one or more to the staging area.**

```python
git add *
```

## git commit

**This command records or snapshots the file permanently in the version history.**

```python
git commit -m “[ Type in the commit message]”
```

**This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.**

```python
git commit -a
```

## git diff

**This command shows the file differences which are not yet staged.**

```python
git diff
```

**This command shows the differences between the files in the staging area and the latest version present.**

```python
git diff –staged
```

**This command shows the differences between the two branches mentioned.**

```python
git diff [first branch] [second branch]
```

## git reset

**This command unstages the file, but it preserves the file contents.**

```python
git reset [file]
```

**This command undoes all the commits after the specified commit and preserves the changes locally.**

```python
git reset [commit]
```

**This command discards all history and goes back to the specified commit.**

```python
git reset –hard [commit]
```
