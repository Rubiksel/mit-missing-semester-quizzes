## Answers

1. Remapping Caps Lock to Escape or Control reduces finger movement and strain for users who use Vim or rely heavily on shortcuts.
2. Tools can distinguish between a quick tap (e.g. send Escape) and a long press (e.g. act as Control). This is useful for dual-function keys.
3. Hammerspoon is a macOS automation tool that uses Lua scripts to control window layouts, bind keys, and automate tasks.
4. Daemons are background processes often started at boot and not attached to a terminal. Their names typically end in `d`, like `sshd`.
5. `crond` is a daemon that runs scheduled commands listed in `crontab` files. It’s used for automation like backups or log rotation.
6. `curl https://api.example.com/data` makes an HTTP GET request. It can be used to download files or interact with APIs.
7. A token is a secret credential passed in headers or query parameters to authenticate API requests.
8. Leaking a token could allow attackers to access private data or perform actions as the user.
9. - `--help`: shows usage information.  
   - `--version`: shows program version.  
   - `--quiet`: suppresses output.  
   - `--dry-run`: simulates the action without doing it.
10. - `-i`: asks for confirmation before actions (e.g., `rm -i`).  
    - `-r`: applies actions recursively to directories (e.g., `cp -r`).
11. `--` stops option parsing, useful when filenames start with a dash. Example: `rm -- -file.txt`.
12. - Tiling: auto-arranges windows with no overlap.  
    - Floating: windows can overlap and be freely moved.  
    Tiling improves efficiency, floating allows flexibility.
13. A VPN routes your traffic through its server, hiding your IP from websites and changing your "visible" ISP.
14. At home, most traffic is already encrypted (HTTPS), and a VPN may not prevent your provider or destination from identifying you.
15. Some VPNs log your data, inject ads, or sell browsing history. It’s critical to research the provider.
16. Some VPNs have misconfigured servers that sent data unencrypted. Always verify that encryption is active, and use trusted providers.
17. DNS over TLS/HTTPS encrypts DNS queries, preventing ISPs or attackers from snooping on which domains you visit.
18. A daemon (or cron job) can automate backups at regular intervals, ensuring data protection without manual action.
19. Scripting allows reproducibility, flexibility, and automation, while GUI tools often lack that fine-grained control.
20. Markdown reads like plain text, making it intuitive and portable.
    - `# Heading`  
    - `**bold**`  
    - `* list item`  
    - `` `inline code` ``  
    - `[link](url)`  
