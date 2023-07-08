# V

- [vlang.io](https://vlang.io/)
- github: [vlang/v](https://github.com/vlang/v)
  - [docs](https://github.com/vlang/v/blob/master/doc/docs.md)
  - [examples](https://github.com/vlang/V/tree/master/examples)
  - [v.gitignore](https://github.com/vlang/v/blob/master/.gitignore)
- [vpm](https://vpm.vlang.io/): package manager

---

## Hello World

```bash
v run src/helloworld/hello.v

hello world
```

---

## Code

- [Hello World](src/helloworld/hello.v)

---

## Install

### from source

```bash
git clone https://github.com/vlang/v
cd v
make

...
V has been successfully built
V 0.4.0 4f518c2
```

### Install Binary

```bash
sudo ./v symlink
```

```bash
which v

/usr/local/bin/v
```

### Update V

```bash
v up
```

### Self Compile

```bash
v self

V self compiling ...
V built successfully as executable "v".
```

## Run

```bash
v
```

```bash
 ____    ____ 
 \   \  /   /  |  Welcome to the V REPL (for help with V itself, type  exit , then run  v help ).
  \   \/   /   |  Note: the REPL is highly experimental. For best V experience, use a text editor, 
   \      /    |  save your code in a  main.v  file and execute:  v run main.v 
    \    /     |  V 0.4.0 4f518c2 . Use  list  to see the accumulated program so far.
     \__/      |  Use Ctrl-C or  exit  to exit, or  help  to see other available commands.

>>> println('hello world')
hello world
>>> 
```

### Plugins

- [VSCode](https://github.com/vlang/vscode-vlang)
- [Vim](https://github.com/vlang/awesome-v#vim)
