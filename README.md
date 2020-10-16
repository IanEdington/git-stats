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
$ wget https://raw.githubusercontent.com/Naereen/git-stats/master/git-stats.sh
$ chmod +x git-stats.sh
$ cp git-stats.sh /path/to/a/directory/in/your/PATH/git-stats
```

## :scroll: License [![GitHub license](https://img.shields.io/github/license/Naereen/git-stats.svg)](https://github.com/Naereen/git-stats/blob/master/LICENSE)
Published under the terms of the [MIT license](http://lbesson.mit-license.org/) (file [LICENSE](LICENSE)).
© [Lilian Besson](https://GitHub.com/Naereen), 2016.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/git-stats/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/git-stats/README.md?pixel)](https://GitHub.com/Naereen/git-stats/)
[![made-with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg)](https://www.gnu.org/software/bash/)

[![ForTheBadge uses-badges](http://ForTheBadge.com/images/badges/uses-badges.svg)](http://ForTheBadge.com)
[![ForTheBadge uses-git](http://ForTheBadge.com/images/badges/uses-git.svg)](https://GitHub.com/)
