```bash
git clone git@github.com:masahiro-kubota/bash_alias.git
echo "if [ -f \"$(pwd)/bash_alias/bash_alias.bash\" ]; then
    . \"$(pwd)/bash_alias/bash_alias.bash\"
fi" >> ~/.bashrc
. ~/.bashrc
```

