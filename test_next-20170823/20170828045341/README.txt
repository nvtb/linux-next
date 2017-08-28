Tegra baseline test results for next-20170823


Here are some basic Tegra test results for Linux next-20170823.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170823/20170828045341/


Test summary
------------

Build: zImage:
    FAIL: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    WARN: ( 1/ 4): qemu-vexpress64
    Pass: ( 3/ 4): tegra132-norrin, tegra210-p2371-0000, tegra210-smaug



-------------------------------------------------------------
Branch: test_next-20170823
Test-Serial: 20170828045341
Commit-ID: cc6d46bb99b516b01f625fe35d100a5eb1031540
Test-Target-Board-Count: 9
Test-Boot-Count: 14
