# qbase
Just a simple bash script I wrote for quickly rebasing the current branch against a target branch because I have to do this so damn often. Please let me know if there already exists another CLI tool for this that is better maintained.

## Quick Start

You must have git CLI tools installed, obviously, for this to work. Let me know if I should add this to the apt repo if there really isn't a tool that does this already (which I would find hard to believe).

```bash
$ mkdir -p ~/opt/bin
$ cd /tmp
$ git clone https://github.com/noodleofdeath/qbase
$ mv qbase/qbase ~/opt/bin
$ chmod +x ~/opt/bin/qbase
$ export PATH=$PATH:~/opt/bin
$ qbase
usage: qbase [-s] <target-branch>
```
