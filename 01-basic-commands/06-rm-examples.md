1. you can delete multiple files with the `rm` command:

```bash
rm file1.txt file.txt
```

2. One way to check what file the rm command deleted is by using the `-v` (verbose) flag:

```bash
rm -v myfile.txt
```

3. You can use the `-i` (interactive) flag to confirm before deleting. 

```bash
rm -i myfile.txt
```

4. you can combine flags together:

```bash
rm -v -i myfile.txt
```

5. Another way to write the above command is:

```
rm -vi myfile.txt
```

or 

```
rm -iv myfile.txt
```