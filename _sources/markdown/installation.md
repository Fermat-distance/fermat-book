# Install Fermat 

There are two different ways of installing the Fermat package. If you just need to import and use Fermat in your own project, the best way of doing it is by installing Fermat with `pip` (Option 1). If instead you want to access the source code and change/add new features to the library, we recommend you to install it directly from the repository (Option 2). If you are intested in this second option, you may also be corious about ways of contributing to Fermat. 

## Option 1: User mode

The library is currently available from the [Python Package Index](). In order to install it, open a new terminal and  enter the command 
```bash
pip install fermat
```

## Option 2: Developer mode

You can direcly clone the [public source repository]() by
```bash
git clone ...
```
or make a fork of it in your own GitHub account (recommended if you are planning to commit changes to the library). From a new terminal move inside the folder of the repository and install Fermat from the source with
```bash
pip install .
```
Notice that if you later make changes on Fermat, these won't be implemented in the installed version immidiately. In order to do so, first you need to uninstall (`pip uninstall fermat`) and then install it again with the changes implememted. 