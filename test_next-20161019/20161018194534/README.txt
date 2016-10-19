Tegra baseline test results for next-20161019


Here are some basic Tegra test results for Linux next-20161019.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20161019/20161018194534/


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
Branch: test_next-20161019
Test-Serial: 20161018194534
Commit-ID: ff9a1f89bf4512a0b628792c096aea0eced8b83c
Test-Target-Board-Count: 9
Test-Boot-Count: 14
