# qw3rtyy_

Network engineer. I build things that are meant to run unattended and stay quiet while they do.

- **Day job**  structured cabling, switching and routing, the physical layer.
- **Own project**  Nevery.cc, a panel for Discord bots on the Russian market. Private for now.
- **Open source**  first merged pull request: [nethercoded/heron](https://github.com/nethercoded/heron), two fixes to the installer's setup-code handling ([deploy/install.sh](https://github.com/nethercoded/heron/blob/main/deploy/install.sh)).

## Toolbelt

- Linux and the boring half of it: systemd units, system users, capabilities, `ProtectSystem=strict`
- POSIX shell  I read install scripts closely enough to find the line that lies to you
- Networking: addressing, VLANs, routing, and knowing which of the three is actually broken
- Discord bot infrastructure and the admin panel in front of it

## Learning in public

Go and SvelteKit, currently at the level of reading someone else's code and locating the bug in it. That is honestly the part I care about: a repository where I am not the only contributor forces a different standard of reading than a repository where I am.

I joined GitHub in October 2025 with no public repositories, so this page is a record of the beginning rather than a portfolio. If you are here about the heron work  the fix was that `crypto/rand.Text()` emits lowercase and the installer's regex only matched `[A-Z0-9]`.
