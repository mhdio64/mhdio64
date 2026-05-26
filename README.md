╭───────────────────────────────────────────────────────────────────────────╮
│ 🔴 🟡 🟢  dev@local: ~                                                   │
├───────────────────────────────────────────────────────────────────────────┤
│ dev@local:~$ ssh vagrant@production-node                                  │
│                                                                           │
│ ┌──────────────────────────────────────────────────┐                      │
│ │  vagrant@production-node:~# ./whoami.sh          │                      │
│ │  > Enforcing KISS principles...                  │                      │
│ │  > Applying Zero Trust policies...               │                      │
│ │  > Access granted.                               │                      │
│ └──────────────────────────────────────────────────┘                      │
│                                                                           │
│ vagrant@production-node:~# cat /etc/motd                                  │
│                                                                           │
│ Linux SysAdmin & DevOps Engineer.                                         │
│ Advocate for Clean Code and the KISS principle.                           │
│ Unnecessary complexity is the enemy of stability.                         │
│                                                                           │
│ vagrant@production-node:~# ls -1 /opt/stack/                              │
│                                                                           │
│ ansible                                                                   │
│ docker                                                                    │
│ gitlab                                                                    │
│ kubernetes                                                                │
│                                                                           │
│ vagrant@production-node:~# ./banner.sh                                    │
│                                                                           │
│   █▀▄ █▀▀ █ █ █▀█ █▀█ █▀                                                  │
│   █▄▀ ██▄ ▀▄▀ █▄█ █▀▀ ▄█                                                  │
│                                                                           │
│   Systems that scale, simply.                                             │
│                                                                           │
│ vagrant@production-node:~# █                                              │
╰───────────────────────────────────────────────────────────────────────────╯
