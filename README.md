# logbooks

## Install Jrnl
```
# MacOS
brew install jrnl

# Linux
pipx install jrnl
```

## Clone logbooks
```
git@github.com:ajkingio/logbooks.git
```

## Setup Config file
```yaml
colors:
  body: none
  date: none
  tags: none
  title: none
default_hour: 9
default_minute: 0
display_format: markdown
editor: nvim
encrypt: false
highlight: true
indent_character: '|'
journals:
  cf:
    encrypt: true
    journal: ~/workspace/logbooks/cf.txt
  hl:
    encrypt: true
    journal: ~/workspace/logbooks/hl.txt
  pr:
    encrypt: true
    journal: ~/workspace/logbooks/pr.txt
  wr:
    encrypt: true
    journal: ~/workspace/logbooks/wr.txt
linewrap: auto
tagsymbols: '#@'
template: false
timeformat: '%F %r'
version: v4.0.1
