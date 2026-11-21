# Ansible Linux Hardening

Ansible roles that take a fresh Ubuntu server to a secured baseline the same way every time.

> **Status: planned.** This repository currently holds the project plan only. No working code has been published yet, and I will update this page as each part is built.

## Goal

Ansible roles that take a fresh Ubuntu server to a secured baseline the same way every time.

## Planned stack

Ansible, Ubuntu Server, UFW, SSH, systemd

## Scope

- [ ] Create a non-root admin user and install SSH keys
- [ ] Disable root login and password authentication
- [ ] UFW firewall with a default-deny policy
- [ ] Automatic security updates
- [ ] fail2ban for SSH
- [ ] Idempotent roles, with checks run in a container or VM

## What this repository will contain

Playbooks and roles, a test setup, and a checklist of what each setting protects against.

## Progress

| Stage | State |
| --- | --- |
| Plan and scope | Done |
| Build | Not started |
| Testing | Not started |
| Write-up | Not started |

## Author

Muhammad Abdullah, DevOps Engineer, London. [LinkedIn](https://www.linkedin.com/in/muhammadabdullaheh)
