Tegra baseline test results for next-20170824


Here are some basic Tegra test results for Linux next-20170824.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170824/20170828133035/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

Boot to userspace: tegra_defconfig:
    WARN: ( 1/ 5): tegra20-trimslice
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

PM: System suspend: tegra_defconfig:
    WARN: ( 1/ 5): tegra20-trimslice
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20170824
Test-Serial: 20170828133035
Commit-ID: 9506597de2cde02d48c11d5c250250b9143f59f7
Test-Target-Board-Count: 9
Test-Boot-Count: 14
