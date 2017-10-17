Tegra baseline test results for next-20171017


Here are some basic Tegra test results for Linux next-20171017.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20171017/20171017140034/


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
    WARN: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    WARN: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    WARN: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    WARN: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver
    FAIL: ( 1/ 5): tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20171017
Test-Serial: 20171017140034
Commit-ID: a7dd40274d75326ca868479c62090b1198a357ad
Test-Target-Board-Count: 9
Test-Boot-Count: 14
