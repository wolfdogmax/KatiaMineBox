<p align="center">
    <a href="https://orange.biolab.si/download">
    <img src="https://raw.githubusercontent.com/irgolic/orange3/README-shields/distribute/orange-title.png" alt="Orange Data Mining" height="200">
    </a>
</p>
<p align="center">
    <a href="https://orange.biolab.si/download" alt="Latest release">
        <img src="https://img.shields.io/github/v/release/biolab/orange3?label=download" />
    </a>
    <a href="https://orange3.readthedocs.io/en/latest/?badge=latest" alt="Documentation">
        <img src="https://readthedocs.org/projects/orange3/badge/?version=latest">
    </a>
    <a href="https://discord.gg/FWrfeXV" alt="Discord">
        <img src="https://img.shields.io/discord/633376992607076354?logo=discord&color=7389D8&logoColor=white&label=Discord">                                                                                                                                                                                                                                                  </a>
</p>

# KATIA Data Mining
[KATIA] is coming soon :-)

<p align="center">
    <a href="https://orange.biolab.si/download">
    <img src="https://raw.githubusercontent.com/irgolic/orange3/README-shields/distribute/orange-example-tall.png" alt="Example Workflow">
    </a>
</p>

[Orange]: https://orange.biolab.si/


## Installing

### Easy installation

No no right now

### Installing with Conda

No do not

Then, create a new conda environment, and install orange3:

```Shell
# Add conda-forge to your channels for access to the latest release
conda config --add channels conda-forge

# Perhaps enforce strict conda-forge priority
conda config --set channel_priority strict

# Create and activate an environment for Orange
conda create python=3.10 --yes --name orange3
conda activate orange3

# Install Orange
conda install orange3
```

For installation of an add-on, use:
```Shell
conda install orange3-<addon name>
```
[See specific add-on repositories for details.](https://github.com/biolab/)


### Installing with pip

PIP ? more like SHIP OF SHIT

### Installing with winget (Windows only)

To install Orange with [winget](https://docs.microsoft.com/en-us/windows/package-manager/winget/), run:

```Shell
winget install --id  UniversityofLjubljana.Orange 
```

## Running

Ensure you've activated the correct virtual environment. If following the above conda instructions:

```Shell
conda activate orange3
``` 

Run `orange-canvas` or `python3 -m Orange.canvas`. Add `--help` for a list of program options.

Starting up for the first time may take a while.


## Developing

[![GitHub Actions](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Factions-badge.atrox.dev%2Fbiolab%2Forange3%2Fbadge&label=build)](https://actions-badge.atrox.dev/biolab/orange3/goto) [![codecov](https://img.shields.io/codecov/c/github/biolab/orange3)](https://codecov.io/gh/biolab/orange3) [![Contributor count](https://img.shields.io/github/contributors-anon/biolab/orange3)](https://github.com/biolab/orange3/graphs/contributors) [![Latest GitHub commit](https://img.shields.io/github/last-commit/biolab/orange3)](https://github.com/biolab/orange3/commits/master)

Want to write a widget? I do not

