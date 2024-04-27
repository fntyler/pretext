# pretext

## Setup Environment

Install ansible and go.

```sh
mkdir -vp ~/do && cd ~/do
curl https://raw.githubusercontent.com/fntyler/pretext/main/setup-env.sh | sh
```

## Usage Guide

```sh
$ cd ~/do/pretext
$ ansible-playbooks playbooks/base.yml
$ ansible-playbooks playbooks/xdg.yml
$ ansible-playbooks playbooks/browser.yml
$ ansible-playbooks playbooks/neovim.yml
$ ansible-playbooks playbooks/repo.yml
```

```mermaid
flowchart TD
    A[base.yml] --> B[xdg.yml]
    A[base.yml] --> C[browser.yml]
    A[base.yml] --> D[neovim.yml]
    A[base.yml] --> E[repo.yml]
```
