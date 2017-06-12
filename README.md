# packer-virtualbox-alpine

Create a Alpine Linux VM with VirtualBox by using Packer.

## Usage

Install [Packer] and [VirtualBox].

* https://www.packer.io/downloads.html
* https://www.virtualbox.org/wiki/Downloads

Then, run packer.

```
$ packer build packer.json
```

## Directory Layout

```
packer-virtualbox-alpine/
├── README.md
├── answerfile
└── packer.json
```


[Packer]:https://www.packer.io/
[VirtualBox]:https://www.virtualbox.org/
