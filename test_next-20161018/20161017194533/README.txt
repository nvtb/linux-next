Tegra baseline test results for next-20161018


Here are some basic Tegra test results for Linux next-20161018.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20161018/20161017194533/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): multi_v7_defconfig
    Pass: ( 1/ 2): tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20161018
Test-Serial: 20161017194533
Commit-ID: 406b05876c202a8f0ac5dc3805d13d7a80e6f9c9
Test-Target-Board-Count: 9
Test-Boot-Count: 14
