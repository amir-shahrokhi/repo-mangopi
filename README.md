# repo-mangopi

repo manifest for building linux image for MangoPi MQ using official OpemEmbedded meta layers

## Using repo to checkout needed meta layers

The following commands will checkout a working set of meta layers needed to build the image

```bash
mkdir mangopi-project
cd mangopi-project

repo init -u "https://github.com/amir-shahrokhi/repo-mangopi.git" -b mainline-master -m mainline-latest.xml
repo sync
```
