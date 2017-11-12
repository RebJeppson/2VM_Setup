# 2 VM Setup

## Purpose
To serve as a default development environment for any future projects.

## Prerequisites
1. VirtualBox (w/ Extension Pack)
1. Vagrant
1. Git
1. Authorized SSH key

## Getting Started
Clone this repository:
```
git clone git@github.com:scemud/scemud.git
cd scemud
```

Copy the `vars.example.rb` into a file named just `vars.rb` and substitute your configuration for the example values within it:
```
cp vars.example.rb vars.rb
vi vars.rb
  ...<substitute variable values and save>...
```

Start the VM:
```
vagrant up dev ide
```
> *if you don't have the right vagrant plugins you will be told how to install them--do so, then retry this command*

Wait for the VM to provision, and your done!