---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Getting Started
gh-repo: https://github.com/whad-team/whad-client
---

# Install WHAD

**WHAD** is only available on Linux/Mac machines (at the moment) and does not work
on Windows system. This is due to some specific under-the-hood internals that are
not compatible with Microsoft Windows systems.

## Basic setup

**WHAD** is available on **pypi** and can be easily installed on a Linux-based host
using `pip`. We highly recommend to setup a dedicated *virtual environment* to avoid
any dependency issue or collision.

The following commands will install **WHAD** on your machine in a dedicated *virtual environment*:

```
$ python -m venv whad
$ . ./whad/bin/activate
(whad)$ pip install whad
```

## Install from git repository

**WHAD** can also be installed from the official git repository. This option may
be useful if you want to try an unstable or in-development version of **WHAD**.
It is recommended to install **WHAD** in a virtual environment:

```
git clone --recurse-submodules https://github.com/whad-team/whad-client.git
cd whad-client
python -m venv my_venv
. /my_venv/bin/activate
pip install .
```

# Explore and practice

## Discover the WHAD academy

Now that you have installed **WHAD** on your system, have a look at our [online academy](https://learn.whad.io) and make your
first steps with our framework. Discover how to interact with Bluetooth Low Energy devices using specific command-line tools,
create your own devices, sniff and capture packets into PCAP files through guided tutorials and examples.

## Explore our example scripts

**WHAD**'s repository also contains some [example Python scripts](https://github.com/whad-team/whad-client/tree/main/examples) you can explore, that demonstrate how to use WHAD's Python API
to interact with any sort of device.


# Need help ?

Our documentation features an [installation section](https://whad.readthedocs.io/en/latest/install.html) detailing all available options with
their corresponding prerequisites and dependencies. It also provides some tips and guidelines that may be useful if you face any
unexpected issue while trying to install our framework.

You can also join [our Discord server](https://discord.gg/bjNk8Sm59P) and ask for help !

