# CXXTemplate
This is used to creating a cpp project quickly

## Usage
use this template, `${ProjectName}` should set by yourself
```bash
git clone https://github.com/kylinholmes/CXXTemplate ${ProjectName}
cd ${ProjectName} && rm -rf .git && git init
```

### build 
genorate build file
```bash
mkdir build && cmake cmake -B build -S .
```
build 
```bash
cmake --build build/    
```
## Note
- if you use `vcpkg`, set a env variable `VCPKG_CMAKE`

like
```bash
export VCPKG_CMAKE=/Users/kylin/vcpkg/scripts/buildsystems/vcpkg.cmake
```
## Tag
`main` => command line app

~~`android` => android app with ndk~~