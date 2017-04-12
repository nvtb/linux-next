Tegra baseline test results for next-20170412


Here are some basic Tegra test results for Linux next-20170412.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170412/20170412010034/


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
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big
    Pass: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20170412
Test-Serial: 20170412010034
Commit-ID: 1267f8fa29e1a6467bd70d1a77aa1934e3eabf5b
Test-Target-Board-Count: 9
Test-Boot-Count: 14
