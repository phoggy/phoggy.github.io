---
layout: home
title: Home
nav_order: 1
---

# rayvn

A shared library ecosystem for bash 5.3+.

See the [README](https://github.com/phoggy/rayvn#readme) on GitHub for a quick introduction, installation instructions and development setup.


---

## Projects

### [rayvn](/rayvn)
The core framework. Provides the `require` system, shared libraries (core, debug, terminal, prompt, secrets, OAuth, and more), and the `rayvn` CLI for generating and testing projects.

### [valt](/valt)
Encrypted file archive tool built on [age](https://github.com/FiloSottile/age) encryption. Uses rayvn shared libraries.

### [wardn](/wardn)
Encrypted Bitwarden vault backup tool. Uses rayvn and valt.

---
