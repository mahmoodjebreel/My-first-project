# My First Project

Includes [OpenMontage](https://github.com/OpenMontageInc/OpenMontage), an open-source AI video production studio, as a git submodule in `OpenMontage/`.

## Setup

```bash
git clone --recurse-submodules https://github.com/mahmoodjebreel/My-first-project.git
cd My-first-project/OpenMontage
make setup          # needs Python 3, Node.js 22+, FFmpeg
```

Already cloned without submodules? Run `git submodule update --init` first.

Optional: add API keys to `OpenMontage/.env` to unlock cloud image/video tools.

## Update OpenMontage

```bash
git submodule update --remote OpenMontage
git commit -am "Update OpenMontage"
```
