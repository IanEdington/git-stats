## ``git-stats``
### *« Who did what in my git repository ?»*
Simply execute the bash script in a Git folder, to have a summary of statistics per author.

### [Example](example.txt)
```
$ git-stats.sh
git-stats.sh: do statistics on this git repository.
From https://github.com/Naereen/git-stats/.

Number of commits per author:
  - 33 : Superman
  - 4  : Batman

Statistics for: Superman
------------------------
- Number of files changed: 31
- Number of lines added: 5144
- Number of lines deleted: 972
- Number of merges: 0

Statistics for: Batman
----------------------
- Number of files changed: 9
- Number of lines added: 374
- Number of lines deleted: 3
- Number of merges: 0
```

## How to use it?
### Installation
Clone the repository, copy the [script (git-stats)](./git-stats) somewhere in your PATH (e.g., ``~/.local/bin/``):

```bash
$ wget https://raw.githubusercontent.com/Naereen/git-stats/master/git-stats
$ cp git-stats /path/to/a/directory/in/your/PATH/
```

## :scroll: License
Published under the terms of the [MIT license](http://lbesson.mit-license.org/).

[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/git-stats/README.md?pixel)](https://github.com/Naereen/git-stats/)
