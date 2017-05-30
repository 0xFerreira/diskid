# diskid

get an UUID for your harddrive (md5sum)

## Installation

$ git clone _[repo_url]_

$ cd $repo

$ sudo cp diskid /usr/bin/


## Usage

$ sudo diskid

## Example
```bash
if [ "$(diskid)" == "b1a8a016f92cb93f12a9567fb3ce363a" ]
  then
    setxkbmap br
fi
```
