# Commentary-Capsule
## Background
Welcome to this project. I started it to not only showcase my experiences in local open source LLM development, but also give a path for others to do similar work.

## Getting Started
This repo uses git submodules to embed other repos. To get started, clone the repository and initialize the submodules:

If you would like a quick one line clone, you can use the following command:
```bash
git clone --recurse-submodules https://github.com/progressEdd/project-template.git
```

If you have already cloned the repository, you can initialize the submodules with the following commands:
```bash
git pull
git submodule update --init --recursive
```

If you only need specific submodules, you can initialize them individually:
```bash
# For just the dev-onboarding submodule
git submodule update --init 01-dev-onboarding
```
