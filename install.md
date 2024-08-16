---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Installing WHAD
gh-repo: https://github.com/whad-team/whad-client
---

# Compatibility

**WHAD** is only available on Linux/Mac machines (at the moment) and does not work
on Windows system. This is due to some specific under-the-hood internals that are
not compatible with Microsoft Windows systems.

# Easy install with pip

**WHAD** is available on **pypi** and can be easily installed on a Linux-based host:

```
pip install whad
```

# Install from git repository

**WHAD** can also be installed from the official git repository. This option may
be useful if you want to try an unstable or in-development version of **WHAD**.
It is recommended to install **WHAD** in a virtual environment:

```
git clone https://github.com/whad-team/whad-client.git
cd whad-client
python -m venv my_venv
. /my_venv/bin/activate
pip install .
```
