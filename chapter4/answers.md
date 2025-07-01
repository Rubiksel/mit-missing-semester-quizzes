## Answers

1. Lines that start with the string "foo".
2. It matches the end of a line.
3. It removes everything up to and including "Disconnected from ", leaving the rest of the line.
4. They define a capture group, which allows portions of the match to be referenced or reused.
5. A capture group captures part of the matched string, which can be referenced in the replacement using `\1`, `\2`, etc.
6. It makes the `*` quantifier non-greedy, matching the shortest possible string.
7. It counts the number of lines in the input.
8. `sort file.txt | uniq | wc -l`
9. It passes the output of one command as input to the next, enabling chaining of operations.
10. Example: `cat files.txt | xargs rm` — deletes files listed in `files.txt`.
11. Greedy matches as much text as possible; non-greedy (`?`) matches the shortest possible amount.
12. `sed 's/^[^:]*://'`
13. `grep -c 'ERROR' filename`
14. `cat files.txt | xargs rm`
15. [regex101.com](https://regex101.com) or [RegExr](https://regexr.com)
16. `uniq` only removes adjacent duplicate lines; `sort` ensures duplicates are next to each other.
17. It counts lines, useful for measuring data size or verifying output.
18. `grep '^[0-9]' filename`
19. Quoting preserves spaces in arguments; unquoted input may split on whitespace and break paths.
20. `sed 's/\t/,/g' file.tsv > file.csv`
