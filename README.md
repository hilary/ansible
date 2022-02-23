# Hilary's Laptop Playbook

Ansible playbook (using [`ansible-pull`](https://docs.ansible.com/ansible-core/devel/user_guide/playbooks_intro.html#ansible-pull)) to manage my Oryx laptop, running Ubuntu 20.

## Why?

All my data, code, etc., is backed up locally (external drive) and in the cloud (SpiderOakONE). While it doesn't make sense to backup system files, I wanted a way to capture / recreate my laptop setup without having to do it manually.

What finally pushed me over the edge from thinking about putting my laptop config in ansible to actually doing it is that I'm planning on upgrading from Ubuntu 20 to 22 real soon now.

## Why Ansible?

I'm fluent in a bunch of configuration systems, so why choose Ansible, in which I'm verging on a total noob? I like the combination of lightweight and power.
