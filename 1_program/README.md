# program
Here is the C++/CMake template for programs.
## How to build
```sh
$ cd build
$ cmake ..
$ cmake --build .
```
If you want to build in release mode:
```sh
cmake --build . --config Release
```
## How to use git
Commit saves changes locally, push transfers local commits to the remote
server (i.e. Github).
```sh
$ git add .
$ git commit -m "."
$ git push origin main
```