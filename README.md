# apt-sources.list

Utility to manage APT sources.list files


# Sample of use

## List available sources.list

```
apt-sources.list -l
```

## Enable wheezy backports

```
apt-sources.list wheezy-bpo on
```

## List the currently enabled lists

```
root# apt-sources.list -e
on   wheezy
on   wheezy-bpo-mozilla
```

## List the available lists

```
root# apt-sources.list -a
off  etch-archive
off  squeeze
off  squeeze-backports
off  squeeze-lts
off  wheezy-backports
off  wheezy-bpo
off  wheezy-lts
off  jessie
off  testing
off  unstable
off  sid
```

## List both (available and enabled) lists

```
root# apt-sources.list -l
on   wheezy
on   wheezy-bpo-mozilla
off  etch-archive
off  squeeze
off  squeeze-backports
off  squeeze-lts
off  wheezy-backports
off  wheezy-bpo
off  wheezy-lts
off  jessie
off  testing
off  unstable
off  sid
```


# License

License MIT
