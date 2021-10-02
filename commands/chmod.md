# chmod 
**In Linux, access to the files is managed through the file permissions, attributes, and ownership. This ensures that only authorized users and processes can access files and directories.**

**In Linux, each file is associated with an owner and a group and assigned with permission access rights for three different classes of users:**
* The file owner.
* The group members.
* Others (everybody else).

**There are three file permissions types that apply to each class:**
* The read permission.
* The write permission.
* The execute permission.
This concept allows you to specify which users are allowed to read the file, write to the file, or execute the file.

## Some basic chmod commands to change the file permissions - 
* to see the help list -
```python
chmod --help
```

* to change the permissions recursively -
```python
chmod u=r --recursively [dir_name]
```

* to add the `execution` permission to the file (this will add the execution permission to everyone)- 
```python
chmod +x [file_name]
``` 

* to add the `execution` permission to a specific user, like any group -
```python
chmod g=x [file_name]
```

* Give the members of the group permission to read the file, but not to write and execute it:
```python
chmod g=r [file_name]
```

* Remove the execute permission for all users:
```python
chmod a-x [file_name]
```

* Recursively remove the write permission for other users:
```python
chmod -R o-w [dir_name]
```

* Remove the read, write, and execute permission for all users except the file’s owner:
```python
chmod og-rwx [file_name]
```

* The same thing can be also accomplished by using the following form:
```python
chmod og= [file_name]
```

* Give read, write and execute permission to the file’s owner, read permissions to the file’s group and no permissions to all other users:
```python
chmod u=rwx,g=r,o= [file_name]
```

* Add the file’s owner permissions to the permissions that the members of the file’s group have:
```python
chmod g+u [file_name]
```

* Add a sticky bit to a given directory:
```python
chmod o+t [dir_name]
```
