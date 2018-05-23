---
title: Getting Started
---

# Getting Started with Tintin

**Note:** Currently, `tintin` only supports [stack](https://haskellstack.org) projects.


## Requirements

### Stack

You'll have to have installed the [stack](https://haskellstack.org) Haskell build tool .
The installation is straightforward:

```bash
wget -qO- https://get.haskellstack.org/ | sh
```

## Installing

You can install Tintin by issuing the following command:

```bash
wget -qO- https://github.com/theam/tintin/raw/master/assets/install | sh
```

We invite you to [check the installation script](https://github.com/theam/tintin/blob/master/assets/install)
before you run it.

## Creating a new project with the Tintin template

We provide a Stack template for making your life easier when creating projects with Tintin:

```bash
stack new --resolver nightly <your-project-name> https://github.com/theam/tintin/raw/master/assets/template.hsfiles
```

_Note: The `--resolver nightly` is required, as the tintin dependencies are not in LTS yet._

You are ready to roll, proceed to [documenting your project](02-documenting-your-project.html)!
