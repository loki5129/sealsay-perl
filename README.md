# sealsay

A seal that lives in your terminal. Inspired by cowsay!
OR

### Manual

1: Clone the repo:

```bash
 git clone https://github.com/loki5129/sealsay-perl
 cd sealsay
```

2: Make script executable & add it to PATH:

```bash
chmod +x sealsay

# Linux / macOS:
 sudo mv sealsay /usr/local/bin/sealsay
 sudo mv seals /usr/share/seals
```
After running the mv command, it is safe to delete the remains of the repo

## Usage

Same format as cowsay:

```bash
$ sealsay [-f sealfile] [-n] [-l] [-W wrapcolumn] [message]
```
```bash
#example
sealsay -f stare.seal seal
 ______ 
< seal >
 ------ 
\
	.---.
       /o   o\
    __(=  "  =)__
     //\'-=-'/\\
        )   (_
       /      `"=-._
      /       \     ``"=.
     /  /   \  \         `=..--.
 ___/  /     \  \___      _,  , `
`-----' `""""`'-----``"""`  \  \_/
                             `-`
:
```
