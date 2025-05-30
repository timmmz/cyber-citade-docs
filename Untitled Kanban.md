---

kanban-plugin: board

---

## To do



## 🗓️ Week 3 — Entering Chroot & Building the Final System

- [ ] Enter chroot environment
- [ ] Rebuild toolchain from inside chroot
- [ ] Build essential tools (coreutils, bash, file, etc.)
- [ ] Configure basic system settings (hostname, locales, timezone)


## 🗓️ Week 4 — Kernel + Bootloader + System Boot

- [ ] Build and configure Linux kernel (custom config)
- [ ] Install and configure GRUB
- [ ] Test first boot into Cyber Citadel OS base system
- [ ] Write Kernel & GRUB hardening notes


## 🗓️ Week 5 — Initial Hardening Layer

- [ ] Implement filesystem protections (mount options, tmpfs, noexec, etc.)
- [ ] Configure strong user/group policies
- [ ] Enable kernel sysctl hardening options
- [ ] Set basic firewall (nftables)


## 🗓️ Week 6 — Authentication & User Space Hardening

- [ ] Harden PAM (strong password policies)
- [ ] Disable unused services
- [ ] Configure secure SSH (no root login, key-only auth)
- [ ] Configure sudo with auditing
- [ ] Add journaling and syslog configuration


## 🗓️ Week 7 — Sandboxing and Isolation

- [ ] Set up AppArmor or SELinux profiles
- [ ] Build minimal container/sandboxing setup (bubblewrap, firejail)
- [ ] Test app confinement
- [ ] Configure auditd and tripwire/snort basics


## 🗓️ Week 8 — Build Core Cybersecurity Stack

- [ ] Compile and configure: Nmap, Amass, Gobuster, Nikto
- [ ] Build Volatility + dependencies
- [ ] Build Metasploit (manual or package-based)
- [ ] Create install scripts for each tool


## 🗓️ Week 9 — Networking Tools & Pentest Frameworks

- [ ] Wireshark, tcpdump, netcat, socat
- [ ] Set up OpenVPN/Wireguard support
- [ ] Harden DNS resolvers (unbound, DNSSEC)
- [ ] Harden network interfaces & bridges


## 🗓️ Week 10 — ISO Build & Reproducibility

- [ ] Automate ISO creation (xorriso, isolinux/syslinux/grub)
- [ ] Test bootable ISO in QEMU/VirtualBox
- [ ] Make build reproducible (scripts + checksums)
- [ ] Write ISO build instructions and troubleshooting


## 🗓️ Week 11 — Documentation & Automation

- [ ] Review and polish Obsidian vault
- [ ] Create install/setup guide (markdown)
- [ ] Write bash scripts for setup tasks
- [ ] Create README and contribution notes


## 🗓️ Week 12 — Final Testing & Future Planning

- [ ] Stress-test the OS (boot, security, install tools)
- [ ] Try simple Red Team use cases
- [ ] List TODOs and improvements for future versions
- [ ] Version the final ISO and upload


## ⏳ Optional Extensions (Post-v1)

- [ ] GUI / TUI dashboard (Wayland / Suckless / Custom Shell)
- [ ] Integrate advanced kernel features (eBPF, KRSI)
- [ ] Add DFIR suite (Plaso, Autopsy)
- [ ] Package manager wrapper (custom minimal APT/yum)


## 🗓️ Week 2 — LFS Toolchain & Temporary System

- [ ] Build Binutils (pass 1)
- [ ] Build GCC (pass 1)
- [ ] Build Glibc
- [ ] Build the remaining temporary toolchain packages
- [ ] Document issues & solutions per package


## 🗓️ Week 1 — Project Setup & LFS Host Preparation

- [ ] Install required host system dependencies (Debian/Fedora/Arch)
- [ ] Partition and format the disk for LFS
- [ ] Mount and prepare the `$LFS` environment
- [ ] Set up LFS user and environment variables


## In progress

- [ ] Create and initialize the Obsidian vault
- [ ] Set up GitHub repo and push initial structure


## Done





%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[false,false,false]}
```
%%