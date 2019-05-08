redis-read
=====

> reading redis source code

Info
-----
1. OS: Mac 10.14.3
2. Compiler: Xcode 10.1 (10B61)
3. IDE: Clion 2019.1.2
4. redis version: 5.0.4
    - http://download.redis.io/releases/redis-5.0.4.tar.gz

Setup
-----
1. Add `CMakeLists.txt` [#DONE](commit/524afe718ec89efa4562797b0fc2f4cb1e196eb9)
2. Fix `ae_kqueue.c` header include [#DONE](commit/1364f6966d739bbb64e55e769c1554e5e6136833)
3. Generate `release.h`
    - execute `mkreleasehdr.sh` before first run

Reference
-----
1. [CLion调试Redis5源码](http://beautyboss.me/2019/03/10/CLion调试Redis5源码/)