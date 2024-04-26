# repo-mangopi

repo manifest for building linux image for MangoPi MQ

## Using repo to checkout needed meta layers

The following commands will checkout a working set of meta layers needed to build the image

```bash
mkdir mangopi-project
cd mangopi-project

repo init -u "https://github.com/amir-shahrokhi/repo-mangopi.git"
repo sync
```

## Acknowledgements

Special thanks to [Arash Golgol](https://github.com/ArashEM) for providing the base [meta-mangopi](https://github.com/ArashEM/meta-mangopi) BSP layer.
