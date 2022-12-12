# CXXTemplate
这个模板用于快速创建C++项目
[English](https://github.com/kylinholmes/CXXTemplate#readme)
## 用法

```bash
git clone https://github.com/kylinholmes/CXXTemplate
cd CXXTemplate && rm -rf .git && git init
```
*需要手动重命名*
### 如何构建项目 
生成构建文件
```bash
mkdir build && cmake cmake -B build -S .
```
构建
```bash
cmake --build build/    
```
清除所有
```bash
rm -rf build
```

----
## 注意
- `cmake` 是必须的，请确保已经安装它. 或者参照 https://cmake.org/
- 如果你使用了`vcpkg`,请设置一个环境变量 `VCPKG_CMAKE`

如下：
```bash
export VCPKG_CMAKE=/Users/kylin/vcpkg/scripts/buildsystems/vcpkg.cmake
```


## 各个标签
`main` => 命令行程序

~~`android` => 使用NDK的安卓应用~~