# CXXTemplate
This is used to create a cpp project quickly

## Usage
use this template, `${ProjectName}` should set by yourself
```bash
git clone https://github.com/kylinholmes/CXXTemplate ${ProjectName}
cd ${ProjectName} && rm -rf .git && git init
```

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
- if you use `vcpkg`, set a env variable `VCPKG_CMAKE`

like
```bash
export VCPKG_CMAKE=/Users/kylin/vcpkg/scripts/buildsystems/vcpkg.cmake
```
## Tag
`main` => command line app

~~`android` => android app with ndk~~