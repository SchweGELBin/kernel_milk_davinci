# MilkKernel

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/SchweGELBin/action_kernel_milk_davinci/total)

**Dynamic Kernel**

**For davinci | Mi 9T / Redmi K20**

**Includes KernelSU**

## Install

- Download **[latest release](https://github.com/SchweGELBin/action_kernel_milk_davinci/releases/latest/)**
- Flash via Recovery

## Build

- Fork **[this](https://github.com/SchweGELBin/action_kernel_milk_davinci/)** repository
- Run Action "CI Build"

## Thanks / Credits
- **[vantoman](https://github.com/vantoman/kernel_xiaomi_sm6150)** for the kernel
- **[tiann](https://github.com/tiann/KernelSU/)** for KernelSU and its manager
- **[AMWolfstein](https://github.com/AMWolfstein/action_kernelsu/)** for the build script
- **[osm0sis](https://github.com/osm0sis/AnyKernel3/)** for the packaging
- **[ZyCromerZ](https://github.com/ZyCromerZ/Clang/)** for the clang build
- **[llvm](https://github.com/llvm/llvm-project/)** for the compiler/toolchain
- For more credits, visit their repositories

## Add Branch
```
View branches: git branch --all
View upstream: git remote -v
In case of error "fatal: the remote end hung up unexpectedly":
    git config http.postBuffer 524288000
After adding: Add to Readme credits & Add to sync-upstream workflow
```
```
git clone https://github.com/[username]/kernel_milk_davinci.git

git remote add upstream [link].git
git fetch upstream

git checkout -b [new_branchname] upstream/[up_branchname]

git push -u origin [new_branchname]
```
