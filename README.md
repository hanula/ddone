
ddone
======


### Installation

```
pip install -r requirements.txt
```

### Usage

```
> ddone add "Implemented feature X"
> ddone add "Found a bug in Y"
> ddone add --time yesterday "Setup new machine"

> ddone list
2022.08.23
    * Setup new machine
2022.08.24
    * Implemented feature X
    * Found a bug in Y

> ddone -h
usage: ddone [-h] {add,a,list,l,del,d} ...

positional arguments:
  {add,a,list,l,del,d}
    add (a)             Add task
    list (l)            List tasks
    del (d)             Delete tasks

options:
  -h, --help            show this help message and exit
```


