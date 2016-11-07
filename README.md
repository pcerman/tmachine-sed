# Turing Machine (tmachine-sed)

Funny implementation of a few Turing Machines in SED editor.

## License

This code is released under MIT License.  
Copyright (c) 2016 Peter Cerman (https://github.com/pcerman)

## Pre-requisites

I have used SED editor version 4.2.2. Probably other versions works too but
I have not tried them.

## Usage
```bash
echo 'aabb' | sed -rf tm.AnBn-1
echo 'aabb' | sed -rf tm.AnBn-2
echo '1100#0110' | sed -rf tm.and-1
echo '1100#0110' | sed -rf tm.and-2
echo '1100#0110' | sed -rf tm.and-3
echo '101' | sed -rf tm.cnt2
echo '12' | sed -rf tm.cnt10
```
