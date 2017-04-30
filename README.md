# gitkv

Easy key-value storage via git.


## Install

```sh
make DESTDIR=/ PREFIX=/usr install
```


## Usage

```sh
gitkv <cwd> <command> <...args>
```

### init

```sh
gitkv <cwd> init <remote>
```

### put

```sh
gitkv <cwd> put <key> <value>
```

### del

```sh
gitkv <cwd> del <key>
```


### get

```sh
gitkv <cwd> get <key>
```

### pull

```sh
gitkv <cwd> pull
```

### push

```sh
gitkv <cwd> push
```

### sync

```sh
gitkv <cwd> sync
```
