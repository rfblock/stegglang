# Stegglang!
A steggy-complete interpreter using gcc paired with its own VS Code extension to give the full Stegglang programming experience!

## Install
Installation is simple! Simply download and run the executable:
```
git clone https://github.com/profsucrose/stegglang.git && cd stegglang && ./init.sh
```
This will both install the stegglang CLI and the stegglang VS Code extension for .stegg file support. Installing the VS Code extension requires you have the `code` command in your $PATH.

To run a .stegg file, simply run 
```
steggy-run myprogram.stegg
```

## Documentation
Stegglang is #1 easy and powerful language

**Hello Steggy**
```
startstegg

stegg

endofstegg
```
will print "Steggy!" the entry point for every stegg program is the codeblcok be in startstegg and endofstegg. all code be in main stegg block but make sure to put button outside main stegg block

**Logging**

```
stegg
```
to print "stegg" or
```
steggysays "Hello World!" steggystopssaying
```
to print the given string

**Steggpoint**

Steggy is strong dinoswoar and needs only one number to keep track of all of his data there is a single number and memory steggpoint

```
addsteggpoint
```
to add steggpoint one
```
losesteggpoint
```
to lose steggpoint one
```
whatissteggpoint
```
to print steggpoint

**Control Logic**

Steggy is smart and knows which stegglines to steggy

```
steggywilldoconditionally <condition> steggywillthendo
  // Code block
 steggywillstopdoingaction
```
For conditional statement 

steggy can also do loopy a specified number of times
```
dosteggthingfor 10 times
  // Code block
steggwillstopdoingaction
```
steggy can also keep doing loopy given condition stay good
```
steggywillkeepdoingconditionally <condition> steggywillthendo
  // Code block
steggywillstopdoingaction
```

**Steggy buttons**

Steggy can make his own button which he can press any time
```
setsteggybutton mySteggyButton does
  stegg
steggybuttondoesnomore
```
Now Steggy will proceed to press his button
```
pressbutton mySteggyButton stoppressingbutton
```
