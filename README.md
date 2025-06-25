## gh-init
Initializes a local and a remote GitHub repo.

Use stand-alone or install as a `gh` extension with
```bash
gh extensions install fsncps/gh-init
```
Usage: `gh init` initializes a local repo with the name of the cwd, creates the same repo on GitHub and sets it as origin, then creates a minimal README and a default .gitignore, commits 'initial commit' and pushes to origin. You can set repo name, path, private/public and skip the README or .gitignore creation as follows:

```
$ gh init --help
usage: gh-init [-h] [-p PATH] [-n NAME] [--no-gitignore] [--no-readme] [-P] [-d DESC]

Initialize a local and remote GitHub repository.

options:
  -h, --help                    show this help message and exit
  -p PATH, --path PATH          Local path to initialize (default: current dir)
  -n NAME, --name NAME          Repository name (default: current dir name)
  --no-gitignore                Skip creating .gitignore
  --no-readme                   Skip creating README.md
  -P, --public                  Make the GitHub repo public
  -d DESC, --description DESC   Short description for the GitHub repo
```
---
