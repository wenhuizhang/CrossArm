# CrossArm
CrossToolNG for Cross Compiling Arm on Mac (Qemu i586 Zephyr OS)

```
$ mkdir x-tools
$ cp src/i586-zephyr-elf x-tools/i586-zephyr-elf
```
Then setup env:
```
export ZEPHYR_TOOLCHAIN_VARIANT=xtools
export XTOOLS_TOOLCHAIN_PATH=$PWD/x-tools
```

