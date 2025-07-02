## Answers

1. `SIGINT` (Ctrl+C) stops the current process.
2. `SIGQUIT` (Ctrl+\) stops the process and makes a core dump.
3. `Ctrl+Z` pauses the process (sends `SIGTSTP`).
4. `bg %1` resumes job 1 in the background.
5. `kill -STOP %1` suspends job 1 using `SIGSTOP`.
6. Use `jobs` to list background/suspended jobs.
7. `alias ll="ls -lah"` makes a shortcut; add to `.bashrc` to keep it.
8. Use `unalias` or remove it from your config file.
9. `alias mv="mv -i"` makes `mv` ask before overwriting (using -i by default).
10. Put aliases in `.bashrc`.
11. `.bashrc` runs when you open a shell; sets env, aliases, etc.
12. `~/.ssh/config` stores SSH settings so you can use short names.
13. Symlinks let you manage dotfiles from another folder.
14. Config files go in `~` so tools load them automatically.
15. `ssh jjgo@192.168.246.142` connects to that host.
16. `scp notes.md jjgo@192.168.246.142:foobar.md` copies and renames.
17. The command `rsync -avP . jjgo@192.168.246.142:cmd` recursively syncs the current directory to the remote `cmd` folder, showing progress and preserving file metadata.
18. Use version control (like Git) to share dotfiles.
19. Add:

    ```bash
    Host myserver
      User jjgo
      HostName 192.168.246.142
    ```

    Then just run `ssh myserver`.

20. `rsync` resumes transfers and sends only changes.
