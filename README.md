Vundle
=========

Install and configure vim via vundle.

## Requirements

- User privileges to install vim package.

## Role Variables

See defaults/main.yml for all the options.
Most of the options are pulled from https://www.shortcutfoo.com/blog/top-50-vim-configuration-options/.

## Example Playbook
```
    - hosts: localhost 
      roles:
        - role: coreyramirezgomez.vundle
          vundle_vim_option_colorscheme: "neverland-darker"
          vundle_plugins_github:
            - "junegunn/fzf"
            - "lepture/vim-jinja"
            - "msanders/snipmate.vim"
            - "neverland.vim--All-colorschemes-suck"
            - "nginx.vim"
            - "SearchComplete"
            - "sexy-railscasts"
            - "Solarized"
            - "Syntastic"
            - "tpope/vim-surround"
            - "vim-ruby/vim-ruby"
            - "chase/vim-ansible-yaml"
          ...
```