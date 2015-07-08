Ansible playbook to bootstrap servers
=====================================

This is a simple playbook I use to boostrap my servers and have a uniform
environment across all of my machines. For the time being, it's meant to work
on Debian and Debian based distros.

This will setup a really simple monit config, some basic iptables (using ferm)
rules, create a user and copy some dotfiles from a git repo.
