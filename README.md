# setup-Macintosh

Installs some packages (Homebrew etc.) and files by Ansible

# Environment
- macOS

# Requirements

- Ansible 2.11.3+
- Python 3.8.2+
- Homebrew
- mas 1.8.2+

# Execution

```
# Install packages
$ ansible-playbook -i localhost package.yml

# Install files
$ ansible-playbook -i localhost files.yml
```

# Caution
- Creating symbolic links for dotfiles is not included in this repository. Refer to [SatoruItaya/dotfiles](https://github.com/SatoruItaya/dotfiles).

# References 
- https://techte.co/2018/01/22/ansible-mac/
