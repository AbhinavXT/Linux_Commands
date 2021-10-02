# init

## Init is the parent of all processes, executed by the kernel during the booting of a system. Its principle role is to create processes from a script stored in the file /etc/inittab.

**To halt the system :**

```python
init 0
```

**To get the system down into single user mode :**

```python
init 1
```

**To get multiuser mode without networking :**

```python
init 2
```

**To get multiuser mode with networking :**

```python
init 3
```

**Not used :**

```python
init 4
```

**To get multiuser mode with networking and X windows :**

```python
init 5
```

**To reboot the system :**

```python
init 6
```
