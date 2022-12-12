# CXXTemplate
This is used to create a cpp project quickly

## Usage
use this template
```bash
git clone https://github.com/kylinholmes/CXXTemplate
cd CXXTemplate && rm -rf .git && git init
```
*rename project manually*
### How to Build 
genorate build file
```bash
mkdir build && cmake cmake -B build -S .
```
build 
```bash
cmake --build build/    
```
clean
```bash
rm -rf build
```

----
## Note
- `cmake` is required, plz make sure you have installed. Or refer to https://cmake.org/
- if you use `vcpkg`, set a env variable `VCPKG_CMAKE`

like
```bash
export VCPKG_CMAKE=/Users/kylin/vcpkg/scripts/buildsystems/vcpkg.cmake
```


## Tag
`main` => command line app

~~`android` => android app with ndk~~