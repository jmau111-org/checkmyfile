# checkmyfile

A simple Bash script to inspect a file using known Linux commands.

Inspired by [checklinux](https://github.com/jmau111-org/checklinux)

## How to use

```
git clone https://github.com/jmau111/checkmyfile
cd checkmyfile
bash checklinux /path/to/myfile > ~/results.log
less ~/results.log
```

As it's a binary, you can make it executable (`chmod +x checkmyfile`) and add it to your local usr folder (`sudo mv checkmyfile /usr/local/bin/`).

While it may be more convenient, it's not ideal.
