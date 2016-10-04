Tegra baseline test results for next-20161004


Here are some basic Tegra test results for Linux next-20161004.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20161004/20161003211534/


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
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20161004
Test-Serial: 20161003211534
Commit-ID: c7d3b912180a9bb0733e5cfab84e5a7493dd3599
Test-Target-Board-Count: 9
Test-Boot-Count: 14
