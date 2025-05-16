# 2_library
## How to run tests
To include test directory to your project, run:
```sh
cmake -DLIB_TEST=ON ..
```
Use ctest to run tests. Run:
```sh
ctest -C Debug
```
or
```sh
ctest -C Build
```
based on configuration you used during the building.