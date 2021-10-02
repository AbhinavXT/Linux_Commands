# tar

tar is an archiving utility often combined with a compression methods such as gzip or bzip2.  

### Examples
- Create an archive and write it to a file:

```
tar cf {{target.tar}} {{file1}} {{file2}} {{file3}}
```

- Create a gzipped archive and write it to a file:

```
tar czf {{target.tar.gz}} {{file1}} {{file2}} {{file3}}
```

- Create a gzipped archive from a directory using relative paths:

```
tar czf {{target.tar.gz}} --directory={{path/to/directory}} .
```

- Extract a (compressed) archive file into the current directory verbosely:

```
tar xvf {{source.tar[.gz|.bz2|.xz]}}
```

- Extract a (compressed) archive file into the target directory:

```
tar xf {{source.tar[.gz|.bz2|.xz]}} --directory={{directory}}
```

- Create a compressed archive and write it to a file, using archive suffix to determine the compression program:

```
tar caf {{target.tar.xz}} {{file1}} {{file2}} {{file3}}
```

- List the contents of a tar file verbosely:

```
tar tvf {{source.tar}}
```

- Extract files matching a pattern from an archive file:

```
tar xf {{source.tar}} --wildcards "{{*.html}}"
```
