# Shell Cheatsheet

- Replace a string on files in a specific path recursively

```
# grep -rl oldtext / | xargs sed -i 's/oldtext/newtext/g'
```
> **Explanation**
> | Options     | Function                                            |
> |:-----------:|-----------------------------------------------------|
> | `-r`        | recursively                                         |
> | `-l`        | files with matches                                  |

- Estimate file space usage

```
# du -sh /
```
> **Explanation**
> | Options     | Function                                            |
> |:-----------:|-----------------------------------------------------|
> | `-s`        | summarize                                           |
> | `-h`        | human-readable                                      |
