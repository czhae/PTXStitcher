PTXStitcher
====================

## Dependencies ##

* libclc
* clang 3.4 >=
* llvm
* gcc4.8
* ptxjit
Note: Please refer to this [link](http://tiku.io/questions/484488/how-to-use-clang-to-compile-opencl-to-ptx-code) to configure libclc and clang with ptx support.

## Setup ##
1. Run `chmod +x cl2ptx.py` to make the python script executable
2. Add the path to `cl2ptx.py` to `PATH`.
3. Edit `config.cfg` with proper configuration.

## Usage ##
To check out available flags, run `./cl2ptx.py --help`.