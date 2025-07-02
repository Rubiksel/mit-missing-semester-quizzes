## Questions

1. What signal is sent when you press `Ctrl+C`, and what does it typically do?
2. What is the purpose of the `SIGQUIT` signal and how is it triggered from the keyboard?
3. What is the effect of pressing `Ctrl+Z` while a foreground job is running?
4. What does the `bg %1` command do?
5. What does `kill -STOP %1` do in terms of job control?
6. How can you list all current background and suspended jobs in your shell?
7. What does `alias ll="ls -lah"` do and how do you make it persistent?
8. How can you remove an alias temporarily or permanently?
9. What does `alias mv="mv -i"` change about the default `mv` behavior?
10. Where should you define persistent aliases in a bash shell environment?
11. What is the purpose of the `.bashrc` file?
12. What is the purpose of the `~/.ssh/config` file, and how does it simplify SSH usage?
13. How can you use symbolic links to manage your dotfiles?
14. Why should configuration files be stored in the user's home directory?
15. How would you SSH into a remote machine with the IP `192.168.246.142` as user `jjgo`?
16. How can you securely copy a file named `notes.md` to a remote machine and rename it `foobar.md`?
17. What does the `rsync -avP . jjgo@192.168.246.142:cmd` command do?
18. What’s a common way to manage your dotfiles (like `.bashrc`, `.vimrc`) across multiple machines?
19. How can you define a shortcut for SSH-ing to a specific host using the `~/.ssh/config` file?
20. What is one benefit of using `rsync` over `scp` for large or interrupted transfers?
