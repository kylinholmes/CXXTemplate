# CXXTemplate
This is used to create a cpp project quickly

## Usage
use this template
```bash
git clone https://github.com/kylinholmes/CXXTemplate demo
cd demo && rm -rf .git && git init
```
*rename project manually*

### How to Build 
genorate build file
```bash
gn gen out
```

build 
```bash
ninja -C out
```
clean
```bash
rm -rf out
```

export compile_commands.json
```bash
ninja -C out/ -t compdb cc cxx > compile_commands.json
```

----
## Note
- `gn` is required, plz make sure you have installed. Or refer to https://gn.googlesource.com/gn/+/main/docs/quick_start.md
